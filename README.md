<h1 align="center">	Ejercicios  entrega individual</h1>
<h2>Repositorio:</h2>

Este es el link del [repositorio](https://github.com/albabernal03/Ejercicios-individuales)
***

<h2>¿De qué trata esta tarea?</h2>

En esta tarea resolvemos una serie de ejercicios con el uso del **pseudocódigo**.

***

## Indice
1. [Ejercicio 1](#id1)
2. 2
3. 2
4. 2
5. 2


***

## Ejercicio 1:<a name="id1"></a>

Este ejercicio consta de dos apartados. El primero de ellos nos pide calcular el precio con IVA incluido y el segundo el interés generado con un tiempo y una tasa de interés dada.

**APARTADO 1:**

```
Algoritmo precio con IVA

#Vamos a calcular el precio fonal con el IVA incluido

Entrada
 c: REAL #coste final
 i: REAL #impuesto sobre la venta
 
Resultado: REAL #precio final con el IVA incluido 

Precondición
 c ≥ 0
 impuesto sobre venta > 0
 
Realización
 Resultado <-- c + (c x i)

Poscondición
 Resultado = c + (c x i)
 
fin cálculo 

```

**APARTADO 2:**

```

Algoritmo interés generado

#Vamos a calcular el interés generado con un capital inicial, tiempo e interés dado.

Entrada
 c: REAL #importe del capital inicial
 t: REAL #tiempo expresado en meses
 i: REAL #tasa de interés

Resultado: REAL

Precondición
 c ≥ 0
 t > 0
 i > 0
 
Realización
 Resultado <-- c x t x i
 
Poscondición
 Resultado = c x t x i

fin calculo interés generado

```
***

## Ejercicio 2: 

En este ejercicio se nos pide dos cosas. En primer lugar se nos pide calcular un algoritmo que calcule la media aritmética de tres números dados. Por otra parte en el segundo nos pide los mismo pero para una cantidad de números indefinifos, los cuales tienes diversos coeficientes de poderación.

**APARTADO 1:**

```
Algoritmo media arimética

#vamos a calcular un algoritmo que calcule la media aritmética de tres números dados

Entrada
 n1, n2, n3: REAL #los números con los que se obtendrá la media
 
Precondición
 n1, n2, n3 ≥ 0

Realización
 Resultado <-- (n1 + n2 + n3) / 3
 
Poscondición
 Resultado = (n1 + n2 + n3) / 3
 
fin cálculo media aritmética
 
```
