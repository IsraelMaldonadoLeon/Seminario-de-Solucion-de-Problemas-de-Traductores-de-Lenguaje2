# Seminario-de-Solucion-de-Problemas-de-Traductores-de-Lenguaje2
Mini Analizador Lexico: Este pequeño programa analiza una cadena y determina si esta es una cadena simple o si es un entero o flotante. 

![2Szbrjy1d7](https://user-images.githubusercontent.com/111924527/205465074-2a425c21-6bc3-4907-acf4-72380107a017.png)

Analizador Léxico / Modulo 1: Utilice el código que el profesor compartió previamente como base del analizador léxico, primero lo analice para comprender cómo funcionaba y que era lo que hacia y después proseguí a hacer cambios como borrar ciertas funciones que no utilizaba, y que analizara palabra por palabra en lugar de caracter por caracter; así mismo agregue más palabras reservadas y finalmente arregle un error que tenía el código original en el cual analizó basura del sistema es decir no se detenía donde terminaba la cadena que el usuario le daba.

![Modulo 1](https://user-images.githubusercontent.com/111924527/205465149-8d3c6c3f-b0e5-43de-bd36-dc97ae1e8850.png)

Analizador sintactico Modulo 2: Generar un algoritmo para analizar los Ejercicios 1 y 2 del archivo (PracticaAnalizadorSintactico.pdf) Este analizador sintactico se basa en una pila de enteros que es la que va guardando el estado y las reglas con forme se va analizando la cadena hasta que llegamos a un estado de aceptacion Entrada para el Ejercicio 1 hola+mundo

![Modulo 2](https://user-images.githubusercontent.com/111924527/205465155-e1969955-e4fd-4451-9b11-fd7f08e27f7e.png)

Entrada para el Ejercicio 2 a+b+c+d+e+f

![Modulo 2 1](https://user-images.githubusercontent.com/111924527/205465293-0f21838b-42d7-4f9e-830e-c8552365100c.png)

![Modulo 2 2](https://user-images.githubusercontent.com/111924527/205465298-89da0490-a112-40ba-a9bd-ccb275c87489.png)

![Modulo 2 3](https://user-images.githubusercontent.com/111924527/205465304-77a357ea-17da-41a5-a0ea-d98360c9edfb.png)


Analizador sintactico(objetos) / Modulo 3: En esta practica utilizaras una pila de objetos en lugar de enteros, de esta forma al momento que imprimas la pila apareceran los simbolos de forma similar a cuando realiza el analisis manualmente. Ejercicio 2

![Modulo 3](https://user-images.githubusercontent.com/111924527/205465310-8bd0f8a5-1621-41c7-b9e4-ec278f97d361.png)


Gramatica del compilador / Modulo 4: Utilizando tu analizador léxico y tu algoritmo para trabajar con las tablas lr. Carga e implementa la gramática. Ejemplo : int hola ( int y ) { }

![Modulo 4](https://user-images.githubusercontent.com/111924527/205465314-6be90075-9571-4f6b-90c7-111d2116a56f.png)

Arbol Semantico / Modulo 5 : Generacion de un arbolcon las reglas y los datos que se estan analizando asi como una tabla de simbolos de estaforma lainformacion no se pierde. Ejemplo Árbol 10

![Modulo 5](https://user-images.githubusercontent.com/111924527/205465324-8d4e5892-2fd6-4d8d-8ef0-b0328000fe9d.png)

Analisis Semantico: el 0 que se observa en la ultima linea es el dato que se paso a memoria para compilar Se junta la gramatica del compilador con el arbol sintactico asi mismo agregamos jeneracion de codigo Ejemplo: int x (int y) {int j; j = 7 ; char letra ; devuelve 7 + 8 ; } Declaración de variable

![Analisis semantico](https://user-images.githubusercontent.com/111924527/205465398-499420f0-e6b2-43e2-97f8-309d452d9dab.png)

Declaracion de variable: la a que se observa en la ultima linea es el dato que se paso a memoria para complilar

![Declaracion de variable](https://user-images.githubusercontent.com/111924527/205465406-18482940-6027-414a-b6da-0626a365f754.png)

Suma en ensamblador:

![Suma en ensamblador](https://user-images.githubusercontent.com/111924527/205465416-c807b7c1-5548-406f-8249-ab3ba2c88fba.png)

Tabla de símbolos:

![Tabla de simbolos](https://user-images.githubusercontent.com/111924527/205465422-f9172130-cd98-4148-88d7-71570b8521be.png)

Aceptacion :

![Aceptacion](https://user-images.githubusercontent.com/111924527/205465428-d7928dea-f852-445a-8d96-d009f844b996.png)
