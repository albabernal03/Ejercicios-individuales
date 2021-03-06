<h1 align="center">	Ejercicios  entrega individual</h1>
<h2>Repositorio:</h2>

Este es el link del [repositorio](https://github.com/albabernal03/Ejercicios-individuales)
***

<h2>¿De qué trata esta tarea?</h2>

En esta tarea resolvemos una serie de ejercicios con el uso del **pseudocódigo**.

***

## Indice
1. [Ejercicio 8](#id1)
2. [Ejercicio 9](#id2)
3. [Ejercicio 10](#id3)
4. [Ejercicio 11](#id4)
5. [Ejercicio 12](#id5)


***

## Ejercicio 8:<a name="id1"></a>

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

## Ejercicio 9:<a name="id2"></a>

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

**APARTADO 2:**

```
Algoritmo media aritmética

#vamos a calcular un algoritmo que calcule la media aritmética de distintos números con diversos coeficientes de ponderación.

Entrada

 n1, n2, n3.....nk: REAL #los números con los que se obtendrá la media aritmética

 c1, c2, c3....ck: REAL #coeficientes de poderación / 100

Precondición
 
 n1, n2, n3...nk ≥ 0

 0 < c1, c2, c3 ...ck ≤ 1 #esto es para indicar que cuando sea 5% se pondrá como 0,05 
 
 
 Realización
  Resultado <-- Σ(nxc)
  
 Poscondición
  Resultado <-- Σ(nxc)
  
 fin cálculo media arirmética
  
  ```
  ***
  
  ## Ejercicio 10:<a name="id3"></a>
  
  En este ejercico nos piden calcular el área de un triángulo dado un lado y la altura relativa a este lado. 
  
  **APARTADO 1:**
  
  
  ```
  Algoritmo área triángulo
  
  #vamos a calcular el área del tríangulo dado un lado y la altura relativa a este.
  
  Entrada
   l:REAL #lado triángulo (el cual ejerce como base)
   h: REAL #altura relativa al lado dado
   
  Precondición
   l > 0
   h > 0
  
  Realización
   Resultado <-- (l x h) / 2
   
  Poscondición
   Resultado = (l x h) / 2
   
  fin calcular área triángulo
   
  ```
  **Observación:** Se puede utilizar este algoritmo para un triángulo rectángulo si se dan las medidas de sus dos lados perpendiculares
  
  
  ## Ejercicio 11: <a name="id4"></a>
  
En este ejercicio se nos pide escribir un algoritmo el cual calcule el importe de las horas extra que hay que pagar, a partir del salario mensual bruto y de la cantidad de horas extra.  

```

Algoritmo calculo sueldo básico por hora

Entrada 
 sueldo_mensual_bruto: REAL #sueldo total que se cobra en el mes
 horas_mes: REAL #horas totales del mes
  
Precondición 
 sueldo_mensual bruto > 0
 horas_mes > 0

Realización
 Resultado <-- sueldo_mensual_bruto / horas_mes
 
Poscondición 
 Resultado = sueldo_mensual_bruto / horas_mes
 
 
Algoritmo calculo importe horas extras 

#vamos a calcular el importe de las horas extras que hay que pagar, a partir del salario mensual bruto y la cantidad de horas extras.


Entrada
 sueldo_básico_por_hora: REAL 
 remuneración_horas_extras_tipo1: REAL #son las horas entre la 36.ª y la 43.ª (125% = 1,25)
 remuneración_horas_extras_tipo2: REAL #son las horas extras 44.ª (150% = 1,5)

Precondición
 sueldo_básico_por_horas > 0
 0 ≤ remuneración_horas_extras_tipo1 < 2
 0 ≤ remuneración_horas extras_tipo2 < 2
 
Realización
 Resultado <-- horas_extras_tipo1 = sueldo_básico_por_hora x remuneración_horas_extras_tipo1
               horas_extras_tipo2 = sueldo_básico_por_hora x remuneracióm_horas_extras_tipo2
Poscondición

Resultado = horas_extras_tipo1 = sueldo_básico_por_hora x remuneración_horas_extras_tipo1
            horas_extras_tipo2 = sueldo_básico_por_hora x remuneracióm_horas_extras_tipo2

Algoritmo cálculo importe total a pagar teniendo en cuenta las horas extras

Entrada:
 Sueldo_mensual_bruto: REAL
 horas_extras_tipo1: REAL
 horas_extras_tipo2: REAL
 
Precondición
 Sueldo_mensual_bruto ≥ 0
 horas_extras_tipo1 ≥ 0
 horas_extras_tipo2 ≥ 0
 
Realización
 Resultado <-- sueldo_mensual_bruto + horas_extras_tipo1 + horas_extras_tipo_2

Poscondición
 Resultado = sueldo_mensual_bruto + horas_extras_tipo1 + horas_extras_tipo_2
 
fin calculo sueldo a pagara total


```
***

## Ejercicio 12:

En este ejercicio nos piden que 

1. Definir el tipo de datos CUENTA..

2. Definir las operaciones aplicables.

En determinadas circunstancias y para determinados clientes, la banca autoriza un descubierto limitado y temporal.

3. Volver a hacer las definiciones previas para permitir estos descubiertos

```
Algoritmo cuenta del depósito

Entrada
 datos_cuenta: TEXTO
 saldo_cuenta: REAL
 dinero_extraer: REAL 
 
 Resultado: BOOLEANO

Precondición
 ninguna

Realización

 si saldo cuenta > dinero_extraer entonces
  resultado <-- no puede extraer dinero
  
 si no 
 #saldo cuenta < dinero_extraer
  resultado <-- puede extraer dinero 
                saldo_actual = saldo_cuenta - dinero_extraer
                
fin cálculo cuenta
 

  
