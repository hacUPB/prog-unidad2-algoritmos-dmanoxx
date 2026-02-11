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

