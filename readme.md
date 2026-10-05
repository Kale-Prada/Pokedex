# Aprendiendo a consumir API - Pokedex

**Consumiendo API con la librería de Python: REQUEST**


- El cliente (mi programa): Envía una petición (request) a través de una dirección web o URL (endpoints).
- El intermediario (la API): Recibe la petición, sigue un conjunto de reglas y se comunica con el servidor.
- El servidor: Procesa la información y devuelve una respuesta en formato JSON.

## Detalles de este ejercicio:

- La API accede a los datos contenidos en el endpoint https://pokeapi.co/api/v2/pokemon/ 
- El programa tiene un menú de opciones para buscar un Pokémon o salir del programa. 
- Al elegir buscar Pokémon, debo introducir el nombre del Pokémon para ver la información de la especie. 
- Si escribes mal el nombre del Pokémon o no existe en PokeAPI, envía mensaje de error y retorna al menú de opciones. 
- La consulta devuelve una lista en formato JSON con todas las categorías que se han dado de alta en el programa. Ejemplo de salida en pantalla al buscar el Pokémon "kakuna" 

```
==============================
     INFORMACIÓN DEL POKÉMON
==============================
Nombre: Kakuna
ID: 14
Altura: 0.6 m
Peso: 10.0 kg

Tipos:
- Bug
- Poison

Habilidades:
- Shed-skin

Estadísticas:
- Hp: 45
- Attack: 25
- Defense: 50
- Special-attack: 25
- Special-defense: 25
- Speed: 35

Primeros 10 movimientos:
- String-shot
- Harden
- Iron-defense
- Bug-bite
- Electroweb
```

## Detalles para ejecutar la API en tu entorno


### Instalación y Ejecución

1. Clona o descarga el repositorio en tu equipo.
2. Abre la carpeta del proyecto en Visual Studio Code.
3. Crea y activa un entorno virtual:
    ```bash
    # Para crear el entorno: 
    # En Windows: 
    python -m venv entorno
    
    #Otra opción: 
    py -m venv entorno 

    # En MacOS: 
    python3 -m venv entorno

    # Para activar el entorno: 
    # En Windows (PowerShell):
    .\entorno\Scripts\activate

    # En macOS/Linux:
    source entorno/bin/activate
    ```
    _Tu entorno estará activo cuando veas el nombre (entorno) al principio de la línea de comandos de tu terminal._
   
4. Instala las librerías necesarias ejecutando:
   ```bash
   # En Windows:
   pip install -r requirements.txt

   # En macOS/Linux:
   pip3 install -r requirements.txt
   ```


## Licencia

Autor = Ejercicio en el curso de programación cero con Keepcoding España S.L.U. 

## Acerca de Pokeapi: 

**Ver Web:** [Pokeapi.co](https://pokeapi.co/)
