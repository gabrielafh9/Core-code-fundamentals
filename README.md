<h1 align="center">Core Code Fundamentals</h1>

- [Week 1](https://github.com/Gabrielafh9/core-code-fundamentals/edit/main/README.md#week1-)
- [Week 2](#Week-2)
- [Week 3](#Week-3)
- [Week 4](#Week-4)

<h1 align="center">Algortihms - Week 1</h1>


<h1 align="left">Monday</h1>


## Preparar la base de la pizza
Los ingredientes para la base de la pizza son: 
- harina, levadura y agua

1. Mezclar la harina y levadura
2. Añadir el agua a la harina y levadura
3. Mezclar bien la masa
4. Dejar reposar la masa durante 15 minutos
5. Extender la masa para hacer un círculo
6. Untar con salsa de tomate y añadir el queso y el jamón
7. Hornear la pizza
8. Cortar la pizza
0. Comer la pizza


## Fahrenheit to Celsius Conversion
 
1. Inicio
2. Pedir temperaturas a convertir y asignar nombre T
3. Preguntar si la temperatura es Celsius o Fahrenheit
4. Si la temperatura esta en grados Celsius 
   - Solicitar formula de conversión a grados Fahrenheit (T*1.8) + 32
   - Realizar conversión paso a paso
   - Reemplazar en fórmula los grados Celsius
   - Multiplicar por 1.80
   - Sumar 32 al resultado de la multiplicación
   - Guardar el resultado obtenido
5. Si la temperatura son grados Fahrenheit
   - Solicitar fórmula de conversión a grados Celsius  (T - 32)*1.80
   - Realizar la conversión paso a paso
   - Reemplazar en la fórmula los grados F
   - Restar 32 a grados asignados
   - Multiplicar 1.80 al resultado de la resta
   - Guardar resultados onbtenidos

Fin


## Some Geometry

Diseñar un algoritmo para calcular el volumen de una pirámide, un cubo y una esfera

1. Inicio
2. Imprimir en la pantalla las opciones "1 Pirámide 2 Cubo 3 Esfera"

3. Si la opción es "1"
   - Calcular el volumen de la pirámide con la fórmula (1/3)(Bh)
   - Multiplicar el área de la base por altura
   - Dividir entre tres
   - Calcular el resultado
   - Imprimir el volumen de la pirámide
4. Si la opción es "2"
   - Calcular el volumen del cubo con la fórmula a × a × a = a³
   - Calcular el resultado
   - Imprimir el volumen del cubo
5. Si la opción es "3"
   - Definir el radio de la esfera
   - Calcular el volumen de la esfera con la fórmula (4/3)*π*r3
   - Asignar el volumen de la esfera
   - Imprimir el volumen de la esfera
   
 Fin

<h1 align="left">Tuesday</h1>

## Numbers
Diseña un algoritmo para comprobar si un número es par o impar
1. Inicio
2. Tomar variable entera A 
3. Asignar valor a la variable A
4. Ejecutar A/2 = X
5. Si X  es un número entero diferente de cero, es un número par
6. Si X es cero o no es un número entero, es un número impar
7. Fin

## Date of birth

Escribir un algoritmo que calcule la edad de una persona a partir de la fecha de nacimiento

1. Inicio
2. Requerir fecha de nacimiento
3. Almacenar fecha de nacimiento en variable "DOB"
4.Calcular la fecha actual
5. Almacenar fecha actual en la variable "TODAY"
6. Realicar resta de las variables "TODAY" - "DOB" y almacenar en variable Y
7.Imprimir edad
8. FIN

## Treasures

Identificar qué cofres tienen tesoros

1. Cofre 1: 
  "El cofre de en medio tiene el tesoro" sin embargo, como es mentira el cofre 2 no tiene tesoro.
2. Cofre 2:
   "Ninguno de los cofres tiene tesoro" sin embargo, como es mentira sabemos que al menos un cofre tiene tesoro.
3. Cofre 3:
   "Solo un cofre tiene tesoro" sin embargo como es mentira sabemos que más de un cofre tiene tesoro.

Conclusion: A y C tienen tesoro.

FIN

<h1 align="center">Week 2</h1>

<h1 align="left">Monday</h1>

## Logic Problem

The teacher asks his 5 students if they studied mathematics yesterday

- Alice: "Nobody studied math yesterday"
- Bob: "1 person studied math yesterday"
- Charlie: "2 people studied math yesterday"
- Dan: "3 people studied mathematics yesterday"
- Eva: "4 people studied mathematics yesteday"

The teacher knows that only those who studied would be telling the truth and those who didn't would be lying. Who is telling the truth?

Alice says that nobody studied math yesterday, but if she's included in that it doesn't make sense, she's not gonna tell the teacher she has not studied. 
Eva says 4 people studied mathematics yesterday, that's not real because only the ones who studied are telling the true, that statement contradicts the other students.
If Dan is telling the true he's contradicting his classmates and the same logic applies to Charlie.

Therefore, Bob is telling the truth because he's not contradicting anyone and he's the one who studied math.

## Cereal vs milk

Cereal vs milk

1. Start 
2. Gather  your supplies: bowl, spoon, milk, a box a cereal
3. Get a bowl
4. Add cereal
5. Add milk
6. Pick up a spoon
7. End

[![milk-or-cereal.png](https://i.postimg.cc/J7vk6zT3/milk-or-cereal.png)](https://postimg.cc/23dy3rN3)

<h1 align="left">Tuesday</h1>

Print my name

[![My-Name.png](https://i.postimg.cc/Bv39KBpV/My-Name.png)](https://postimg.cc/PCSRGZBW)

Print my name & age

[![My-name-and-age.png](https://i.postimg.cc/Y9CFXDYP/My-name-and-age.png)](https://postimg.cc/VS25vR79)

<h1 align="left">Wednesday</h1>

## Algortithm game

[![Algorithm-game.png](https://i.postimg.cc/90qrS6ML/Algorithm-game.png)](https://postimg.cc/D4nv4Y1G)

## Mod

[![Mod.png](https://i.postimg.cc/bNpZLBP9/Mod.png)](https://postimg.cc/XX1NYxpr)

## Register Form

[![Register-Form.png](https://i.postimg.cc/kGcXk7CF/Register-Form.png)](https://postimg.cc/T5K6bMpp)

<h1 align="left">Thursday</h1>

## Truth Tables

-  T & T = T ✅
-  T & F = F ✅
-  F & T = T ❌
-  F & F = F ✅
-  T | T = T ✅
-  T | F = F ❌
-  F | T = T ✅
-  F | F = F ✅
-  ~T = T ❌
-  ~f = T ✅
-  (T & F) | (~F) = T ✅
-  (T | F) & (F | F) = T ❌
-  ~((T | F) & (F | F)) & F = F ✅
-  ~((T | F) & (F | F)) & T = T ✅

## Boolean results

[![Boolean-Values1.png](https://i.postimg.cc/fR0kbnfZ/Boolean-Values1.png)](https://postimg.cc/MnqzsLLr)

## Identify odd and even numbers

[![calculadora-Eor-O.png](https://i.postimg.cc/Dwdk6x2L/calculadora-Eor-O.png)](https://postimg.cc/dh1xtmZV)

<h1 align="center">Week 3</h1>

<h1 align="left">Monday</h1>

## Simple calculator

[![simple-calculator.png](https://i.postimg.cc/kXh2NrN6/simple-calculator.png)](https://postimg.cc/qzyB0554)

## Special number

[![Special-number.png](https://i.postimg.cc/tgGCD9sT/Special-number.png)](https://postimg.cc/SnVhxF7F)

<h1 align="left">Tuesday</h1>

## Simple calculator with Switch

[![Calculador-Switch.png](https://i.postimg.cc/SQg6Pv7q/Calculador-Switch.png)](https://postimg.cc/ThW5LQ4H)

## Multi Option program

[![Multi-Opcion.png](https://i.postimg.cc/DfpG6bnw/Multi-Opcion.png)](https://postimg.cc/Yjgjq0v5)

<h1 align="left">Wednesday</h1>

## Multiplication Tables

[![Tabla-de-multiplicar.png](https://i.postimg.cc/HLTjdpdN/Tabla-de-multiplicar.png)](https://postimg.cc/qNZpGHtc)

## Simple calculator with Do While

[![DoWhile.png](https://i.postimg.cc/76d2xpBT/DoWhile.png)](https://postimg.cc/MM0T5rJW)

<h1 align="left">Thursday</h1>

## Multiplication tables with For

[![Multiplication-tables-with-for-111.png](https://i.postimg.cc/cHpBDgGj/Multiplication-tables-with-for-111.png)](https://postimg.cc/cgc3CJHM)

## Ascending and Descending Numbers

[![Ascendente-Descendente1.png](https://i.postimg.cc/V6Cjbf0F/Ascendente-Descendente1.png)](https://postimg.cc/sQ3BkRcB)

## Greetings

[![Greetings1.png](https://i.postimg.cc/jjJWM8qx/Greetings1.png)](https://postimg.cc/bGpNJ92W)

<h1 align="center">Pseudocode & Pause Day - Week 4</h1>

<h1 align="left">Monday</h1>

## Average sales and comission

[![averagesalesw4.png](https://i.postimg.cc/TwGzmxrm/averagesalesw4.png)](https://postimg.cc/FfWC52Cs)

## Even or Odd

<img width="806" alt="image" src="https://user-images.githubusercontent.com/116181766/209196840-d69511b0-e414-43c7-85bf-9ff418e6ce0a.png">

<h1 align="left">Tuesday</h1>

## Full name

[![Full-Namew4.png](https://i.postimg.cc/C1sqk7Hv/Full-Namew4.png)](https://postimg.cc/sQ1xRpLS)

## Throw dice

[![Throw-Dice.png](https://i.postimg.cc/R06hPQrT/Throw-Dice.png)](https://postimg.cc/wtz9MNjt)

<h1 align="left">Wednesday</h1>

## Distance to zero

[![Distancetozerow4.png](https://i.postimg.cc/sfJJTpTQ/Distancetozerow4.png)](https://postimg.cc/rzKWmtXM)


