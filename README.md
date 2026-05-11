# Laboratorio 2 - Python

## 📌 Descripción  
Este laboratorio tiene como objetivo que los estudiantes fortalezcan sus conocimientos relacionados con **Python** y la programación funcional.

---

## 🛠️ Instrucciones Generales  

1. **Fork del repositorio**  
   - Realice un **fork** de este repositorio en su cuenta personal de GitHub.  
   - No realice cambios directamente sobre el repositorio original.  

2. **Estructura de carpetas**  
   - Dentro de su fork, cree una carpeta llamada **`lab02/`**.  
   - Cada ejercicio debe resolverse en un archivo **independiente** con el siguiente formato:  
     ```
     lab02/ejercicio01.ipynb
     lab02/ejercicio02.ipynb
     ...
     ```  

3. **Resolución de ejercicios**  
   - Desarrolle los programas en Google Colab.  
   - Una vez finalizados, copie el código a los archivos `.ipynb` correspondientes en su repositorio.  
   - Cada archivo debe contener:
     - La implementación de su solución.  

4. **Buenas prácticas**  
   - Use **nombres de predicados claros y significativos**.
---

## 🚀 Entrega  

- **Plazo**: La entrega debe realizarse a mas tardar el proximo lunes, se habilitara una tarea en Moodle para adjuntar el link del repositorio.

---

## ✅ Criterios de Evaluación  

1. **Correctitud de las soluciones** (funcionalidad de los predicados).  
2. **Cumplimiento de la estructura solicitada** (archivos independientes en `lab02/`).  
3. **Claridad en la codificación** (nombres, comentarios y legibilidad).  
4. **Uso adecuado de variables** (incluyendo variables anónimas donde corresponda).  

---

## 💡 Recomendaciones  

- Antes de subir sus archivos, **ejecute y verifique** cada consulta en el compilador en linea.  
- Mantenga su repositorio organizado y actualizado.

---

## Ejercicio 1 - Funciones lambdas

1. Definir las siguientes funciones usando lambdas.

```  
a. Crear una lambda que reciba un número y devuelva True si es múltiplo de 3, False en caso contrario.
b. Crear una lambda que reciba un número y devuelva su cubo.
c. Crear una lambda que reciba dos números y devuelva su producto.
d. Crear una lambda que reciba dos números y devuelva el mayor.
e. Crear una lambda que reciba una palabra y devuelva True si empieza con la letra “A" (o “a”).
f. Crear una lambda que reciba una temperatura en Celsius y la convierta a Fahrenheit.
```

2. Realizar el siguiente ejercicio usando lambdas

    Crear una lista que contenga tres lambdas:
    * Una que duplique un número
    * Una que le sume 10
    * Una que calcule su cuadrado

    Luego, pedir un número al usuario y aplicar cada lambda a ese número, mostrando los resultados.
    
    ```
    Ingrese un número: 5
    10
    15
    25
    ```

---

## Ejercicio 2 - listas de compresión

1. Realizar los siguientes ejercicios usando listas de compresión.

```  
a. Generar una lista con tuplas (n, n^2) para una lista de numeros.
b. Generar una lista con cubos de los números mayores a 10.
c. Generar una lista con solo los numeros pares.
d. Dada la lista numeros, producir:

    ["valor: 10", "valor: 15", ...]
e. Generar una lista con la conversion correspondiente a grados Fahrenheit.
f. Generar una lista filtrando las palabras de mas de 5 letras.
g. Generar una lista con solo las iniciales de las palabras.
h. Generar una lista indicando "par" o "impar" dada una lista de numeros.
i. Dada una lista de listas (matriz), aplanala.

    [[1,2,3], [4,5,6], [7,8,9]] = [1,2,3,4,5,6,7,8,9]
```


---

## Ejercicio 3 - Map

1. Realizar los siguientes ejercicios usando map.

```
a. Dada una lista de temperaturas en Celsius, convertirlas a Fahrenheit.
b. Dadas dos listas con la misma cantidad de elementos, generar una nueva sumando cada elementos (primer elemento de lista 1 + primer elemento lista 2).
c. Dada una lista de radios de circulos, generar la lista de sus areas.
d. Dada un diccionario, generar una lista de tuplas (nombre, valor+10%)

  {"pan": 1000, "leche": 2500, "café": 5000}

e. Dada una matriz, multiplicar todos los elementos por 10.
```

----


## Ejercicio 4 - Filter

1. Realizar los siguientes ejercicios usando filter.

```
a. Dada una lista de palabras, filtrar solo aquellas con mas de 4 letras.
b. Dada una lista filtrar los elementos que son nulos (None).
c. Dada una lista de palabras, filtrar aquellas que empiezan pro una vocal.
d. Dada una lista de palabras, filtrar aquellas que son palindromos.
e. Dada una lista de numeros, filtrar los que terminan en 5.
f. Dada una lista de diccionarios, filtrar los productos con precio mayor a 100.

  productos = [
    {"nombre": "Teclado", "precio": 80},
    {"nombre": "Mouse", "precio": 40},
    {"nombre": "Monitor", "precio": 300},
    {"nombre": "Webcam", "precio": 150}
]

```


## Ejercicio 4 - Reduce

1. Realizar los siguientes ejercicios usando reduce.

```
a. Dada una lista de numeros, calcula la multiplicación de estos.
b. Dada una lista de palabras, concetenalas en una sola.
c. Dada una lista, hallar el mayor de todos, define una función auxiliar que dado dos numeros retorne el mayor
```


---

## Ejercicio 4 - Sorted

1. Realizar los siguientes ejercicios usando sorted.

```
a. Ordenas una lista de palabras alfabeticamente.
b. Ordenar una lista de tuplas por el primer elemento.
c. Dada una lista de diccionarios, ordenar por precio (mayor a menor), y luego por nombre

  productos = [
      ("Camisa", 30),
      ("Pantalón", 55),
      ("Medias", 10),
      ("Chaqueta", 80)
  ]

d. Dada una lista de palabras, ordenarlas según su longitud.
e. Dada una lista de numeros, ordenarlos de tal forma que aparezcan primero los pares y luego los impares.
f. Convertir una palabra a un diccinario que cuente la aparicion de cada letra, ordenar dicho diccionario según la frecuencia de aparicion.
g. Dada una lista de tuplas, ordenar la primero por el departamento del empleado y luego por la edad.

    empleados = [
      ("Maria", "Ventas", 30),
      ("Luis", "Tecnología", 25),
      ("Ana", "Ventas", 25),
      ("Pedro", "Tecnología", 28)
    ]

```

---


## Ejercicio 5

1. Realizar los siguientes ejercicios usando sorted.

```
a. Filtrar números pares y luego elevarlos al cuadrado.
b. Dada una lista de numeros, elevar cada número al cubo, filtrar los mayores que 100, convertirlos a cadenas.
c. Dada una lista de numeros, filtrar números mayores que 10, elevarlos al cuadrado, ordenarlos de mayor a menor.
```

---

## Ejercicio 6 - Minimax

```
Dado el juego conocido como NIM, implementar una solución a este usando el algoritmo minimax visto en clase

En este juego hay una pila de piedras (por ejemplo 10).

En cada turno un jugador puede quitar 1, 2 o 3 piedras.

Pierde el jugador que no puede mover (porque ya no quedan piedras).

MAX = Computadora

MIN = Humano

Dado lo anterior y el algoritmo visto en clase, modelar el juego y simularlo donde MAX sera la cpu y MIN el humado el cual interactua mediante el input, el primer turno sera el de MIN
```

---


## Retrospectiva
1. ¿Cuál fue el tiempo total invertido en el laboratorio por cada uno de ustedes? (Horas/Hombre)
El tiempo total invertido fue aproximadamente de 6 horas/hombre. Este tiempo incluyó el análisis del problema, el diseño del algoritmo Minimax, la implementación en Python, las pruebas del programa y la corrección de errores.
2. ¿Cuál es el estado actual del laboratorio? ¿Por qué?
El laboratorio se encuentra finalizado y funcional. El programa permite jugar correctamente contra la computadora utilizando el algoritmo Minimax, validando movimientos y determinando adecuadamente el ganador de la partida.
3. ¿Cuál consideran fue el mayor logro? ¿Por qué?
El mayor logro fue implementar correctamente el algoritmo Minimax aplicado al juego NIM. Esto permitió que la computadora tomara decisiones óptimas en cada turno, demostrando el funcionamiento de la inteligencia artificial en juegos de estrategia.
4. ¿Cuál consideran que fue el mayor problema técnico? ¿Qué hicieron para resolverlo?
El mayor problema técnico fue comprender la lógica recursiva del algoritmo Minimax y establecer correctamente los casos base. Para resolverlo, se realizaron pruebas paso a paso, diagramas del árbol de decisiones y validaciones manuales de las jugadas posibles.
5. ¿Qué hicieron bien como equipo? ¿Qué se comprometen a hacer para mejorar los resultados?
Se trabajó de manera organizada y constante, dividiendo las tareas entre análisis, programación y pruebas. Para mejorar los resultados, se propone optimizar el código, mejorar la interfaz del juego y documentar de manera más detallada cada función implementada.
6. ¿Qué referencias usaron? ¿Cuál fue la más útil? Incluyan citas con estándares adecuados.
Referencias:
Python Documentation
Documentación oficial utilizada para manejo de funciones, estructuras de control y recursividad.
GeeksforGeeks - Minimax Algorithm in Game Theory
Explicación del algoritmo Minimax y ejemplos de aplicación en juegos.
Wikipedia - Nim
Información general sobre las reglas y estrategia del juego NIM.
La referencia más útil fue la explicación de GeeksforGeeks, ya que permitió entender la lógica del algoritmo Minimax y cómo aplicarlo al problema planteado.
