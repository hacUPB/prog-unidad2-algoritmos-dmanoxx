# Actividad 1 

### Ejemplo 1

Compro un producto que cuesta $150.000 con la tarjeta de credito. La tasa de interes del 2.1% mensual. Se difiere la compro a 9 cuotas.

¿ Cuánto se debe pagar cada mes?

Datos de entrada

- Valor de la compra
- Tasa de interés 
- Número de cuotas

Datos de Salida 

- Valor de la compra
- Saldo
- Cuotas restantes 

Operaciones 

Repetir 9 veces

- Cuota-sin-interes= saldo/numero-de-cuotas
- Cuota-con-interes= Cuota-sin-interes * Tasa-de-interes
- Saldo= Valor-de-la-compra - cuota-sin-interes
- Muestre cuota-con-interes, saldo

# Ejercicio 1

1. Investiga cuáles son los símbolos que se utilizan para representar cada operación de un algorimo con un diagrama de flujo. Asegúrate de que la fuente es confiable, discute lo que encontraste con tus compañeros y con el profe. Cuando estés seguro/a de tener los símbolos correctos, consigna la información en la bitácora.

* Los diagramas de flujo utilizan símbolos estandarizados por normas ISO 5807 y ANSI X3.5 para representar las operaciones de un algoritmo. Los principales símbolos son:

* Óvalo: Inicio y Fin.

* Rectángulo: Proceso o instrucción.

* Paralelogramo: Entrada o salida de datos.

* Rombo: Decisión (condición).

* Flechas: Dirección del flujo.

* Círculo: Conector.

* Rectángulo con doble línea: Subproceso.

# Ejercicio 2.1

* Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo.
```
Inicio 

Mostrar "Por favor ingresar la cantidad de lápices que desea comprar"  

Leer cantidad   

Si cantidad >= 1000 
     precio= 85$

Si no 
    precio = 90$  

Fin Si     

total = cantidad * precio

Mostrar "Total a pagar: $", total

Fin

```


# Ejercicio 2.2

* Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá.

```
Inicio  

Mostrar "Ingrese el valor total de la compra"

Leer valor 
    Si valor > $ 250 000 
    precio= valor - valor * 0.15
    
Si no 
    precio= valor - valor 0.8

Fin Si  

Mostar "Total a pagar: $", precio 

Fin
```

# Ejercicio 2.3

* El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.


```

Inicio 

Mostrar "Ingrese la cantidad de alumnos que viajaran"

Leer cantidad 
    Si cantidad >= 100
        precio = cantidad * 65.00

    Sino   50<= cantidad <= 99
        precio = cantidad * $70.00

    Sino   30<= cantidad <= 49
        precio = cantidad * $90.00 

    Sino   cantidad < 30
        precio= cantidad * $95.00

    Sino totalpagar < $4000.00
        precio= totalpagar/cantidad

    Fin Si

    Mostrar " Costo por alumno: $", precio
    Mostrar "Total a pagar a la compañia:$", totalpagar
    
```
# Ejercicio 2.4

```
Inicio
SU = 0
VA = 0
Mientras VA != -1
    Leer VA
    SU= SU + VA
    C= C+1
Fin mientras
Escribir SU
Fin 
```
# Ejercicio Final 

## Parte 1: Identificar Algoritmos

* Una página web.
No es un algoritmo.
Una página web es un conjunto de contenidos como texto, imágenes y enlaces. Puede contener algoritmos en su programación, pero en sí misma no es un conjunto de pasos ordenados para resolver un problema.

* Una receta para hacer un pastel, donde se indican ingredientes y pasos a seguir.
Sí es un algoritmo.
Contiene pasos ordenados y definidos que permiten obtener un resultado específico.

* "Piensa en un número y multiplícalo por otro".
No es un algoritmo completo.
Es una instrucción general, pero no especifica pasos detallados ni define claramente inicio y fin.

* Un manual de instrucciones para armar un mueble, con pasos detallados y un orden claro.
Sí es un algoritmo.
Presenta una secuencia ordenada de pasos para lograr un objetivo determinado.

* Una lista de compras organizada en orden alfabético.
No es un algoritmo.
Es solo una lista de elementos, no describe un procedimiento paso a paso para resolver un problema.

### Parte 2: Variables y Constantes

* El valor de la gravedad en la Tierra, 9.8 m/s².
Constante.
Es un valor fijo que no cambia.

* La edad de una persona calculada con base en el año actual y su año de nacimiento.
Variable.
Cambia con el paso del tiempo.

* La cantidad de dinero en una cuenta bancaria.
Variable.
Puede aumentar o disminuir.

* La velocidad de la luz en el vacío, 299,792,458 m/s.
Constante.
Es un valor fijo en física.

* El radio de un círculo.
Variable.
Puede tomar distintos valores según el círculo considerado.

### Parte 3: Características de los Algoritmos

* No cumple completamente.
La expresión "cuando los cambios en la distancia parecen lo suficientemente pequeños" no es precisa. Un algoritmo debe ser claro y definido, sin ambigüedades.

* No cumple completamente.
Es demasiado general. No especifica claramente los pasos ni define con precisión el inicio y el final.

* Sí cumple.
Tiene un propósito claro y puede describirse mediante pasos definidos para calcular el área.

* Sí cumple.
Tiene un inicio claro, un proceso definido y una condición explícita de finalización cuando se ingresa el valor -1.

### Parte 4: Comprensión de Herramientas

* Falso.
El pseudocódigo no utiliza símbolos gráficos estándar; eso corresponde a los diagramas de flujo.

* Verdadero.
Los diagramas de flujo representan gráficamente un algoritmo.

* Falso.
El pseudocódigo no debe estar escrito en un lenguaje de programación específico.

* Verdadero.
Un diagrama de flujo debe tener inicio y fin claramente definidos.

### Parte 5: Estructuras de Control

* Las estructuras de control sirven para dirigir el flujo de ejecución de un algoritmo. Permiten tomar decisiones, repetir acciones o ejecutar instrucciones en un orden determinado.

* Ejemplo de la vida diaria:
Si está lloviendo, llevo paraguas. Si no está lloviendo, no lo llevo.
Aquí se utiliza una estructura condicional para tomar una decisión.

* Ejemplo con cálculos matemáticos:
Si el promedio de mis calificaciones es mayor o igual a 3, apruebo la materia. Si es menor a 3, repruebo.
Se realiza un cálculo y, según el resultado, se toma una decisión.