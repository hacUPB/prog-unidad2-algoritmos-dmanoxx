# **Ejercicios con condicionales**

1. **Verificación de peso de despegue**
    
    En una pista de pruebas de aeronaves, el sistema debe verificar si el peso total de la aeronave, incluyendo combustible y carga, supera el límite máximo permitido para el despegue. Dependiendo del resultado, el sistema deberá indicar si la aeronave está lista para despegar o si debe reducir carga o combustible.

    **RESPUESTA**

Variables de inicio 
* Peso aeronave
* Peso combustible    
* Peso carga 

Variables de Salida
* Peso total aeronave   

```
    Inicio
    
    Mostrar "Ingrese el peso de la aeronave sin combustible ni carga"
    Leer peso_aeronave

    Mostrar "Ingrese el peso del combustible"
    Leer peso_combustible

    Mostrar "Ingrese el peso de la carga" 
    Leer peso_carga
    
    Mostrar "Ingrese el limite maximo permitido para el despegue"
    Leer limite_maximo

    peso_total= peso_aeronave + peso_combustubible + peso_carga

    Si peso_total <= limite_maximo
        Mostrar "La Aeronave esta lista para despegar"

    Si no   
        Mostrar "La Aeronava supera el limite permitido"
        Mostrar "Retire carga de la aeronave y hazlo de nuevo"

     Fin Si
     Fin   
    
```




2. **Control de temperatura del motor**
    
    Durante una inspección de rutina, se mide la temperatura de un motor de turbina. Si la temperatura es mayor a un valor crítico, se debe indicar "Peligro: sobrecalentamiento". Si está dentro del rango seguro, indicar "Operación normal". Si es demasiado baja, indicar "Motor frío – Calentar antes de operar".

    **RESPUESTA**

    Variables de inicio

    * Temperatura
    * Limite minimo
    * Limite maximo 

    Variable de salida

    * Peligro: sobrecalentamiento
    * Motor frio - Calentar antes de operar
    * Operacion normal


    ```

    Inicio 

    Mostrar "Ingrese la temperatura actual del motor:"
    Leer temperatura

    Mostrar "Ingrese el límite minimo seguro:"
    Leer limiteBajo

    Mostar "Ingrese el límite maximo seguro:"
    Leer limiteAlto

    Si temperatura > limiteAlto Entonces
        Mostrar "Peligro: sobrecalentamiento"

        Sino temperatura < limiteBajo Entonces
            Mostar "Motor frio – Calentar antes de operar"
        Sino
            Mostrar "Operacion normal"

    FinSi
    Fin
    ```


    ### **Ejercicios con bucles**

1. **Registro de altitudes de vuelo**
    
    Un sistema debe registrar la altitud de vuelo cada 10 minutos durante una hora y mostrar todas las mediciones al final.

    **RESPUESTA**

    **Variable de inicio**

    * altitud[6]
    * i= contador

    **Variable Salida**
    * altitud [6]

    ```
    Inicio 

    Si i<=5 
        Mostrar "Ingrese la altitud",i * 10
        Leer altitudes [i]
    
    Fin Si

    Mostrar "Mediciones de altitud 
    Mostar "Minuto, i * 10, : , altitudes[i],  metros"

    Fin
    ```

2. **Control de combustible en pruebas**
    
    Durante un ensayo en banco de un motor a reacción, se mide el nivel de combustible cada minuto y se detiene el registro cuando el combustible baja del 10%. Mostrar el tiempo total de operación antes de llegar a ese punto.
    
    **RESPUESTA**


    **Variable Inicio**

    * nivel_combustible
    * tiempo 

    **Variable salida**

    * tiempo total



### **Ejercicios con bucle y condicionales**

1. **Detección de turbulencia en trayecto**
    
    Un sensor mide la aceleración vertical de la aeronave en intervalos de un segundo durante un trayecto de 2 minutos. Si el valor medido supera un umbral, indicar que se ha detectado turbulencia en ese instante. Al final, mostrar cuántas turbulencias se detectaron.
    
    **RESPUESTA**

    *
    
2. **Control de temperatura en cabina**
    
    Un sistema mide cada 5 minutos la temperatura en cabina durante una hora. Si en algún momento se detecta una temperatura mayor a 27°C o menor a 18°C, debe indicar que se active el sistema de climatización.

    **RESPUESTA**

    *
    
3. **Simulación de conteo de pasajeros**
    
    Durante el abordaje, un sistema cuenta a los pasajeros que ingresan. Si el número total supera la capacidad máxima, el sistema debe detener el conteo y mostrar un mensaje de alerta.
    
    **RESPUESTA**

    *


### **Ejercicios de mayor complejidad**

1. **Planificación de misión satelital**
    
    Desarrollar un algoritmo que reciba datos de consumo de energía por hora de un satélite durante un día completo. Si en cualquier hora el consumo excede un límite crítico, debe registrarse como una alerta. Al final, mostrar el consumo total y el número de alertas generadas.

    **RESPUESTA**

    *
    
2. **Simulación de carga y balanceo de aeronave**
    
    Una aeronave tiene varias bodegas de carga. El sistema debe permitir ingresar el peso cargado en cada bodega y verificar que:
    
    - El peso total no exceda el máximo permitido.
    - Ninguna bodega individual supere su límite.
        
        Mostrar mensajes de advertencia si alguna condición no se cumple.

        **RESPUESTA**

    *
        
3. **Monitoreo de aproximación a pista**
    
    Durante la aproximación, un sistema recibe datos de altitud y velocidad cada 5 segundos hasta el aterrizaje. Si la velocidad excede el valor máximo seguro o la altitud no desciende adecuadamente, debe indicarse un mensaje de corrección de maniobra. Mostrar un resumen final de todos los avisos emitidos.

    **RESPUESTA**

    *