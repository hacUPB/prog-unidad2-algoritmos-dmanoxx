# Actividad 1

### Ejercicios

1. Convierte el número decimal 22 a binario.


#### RESPUESTAS

|   |   |  |   |  |   | 
| --- | --- | --- |  --- | --- | --- | 
| 32 | 16 | 8 | 4 | 2 | 1 | 
|  0 | 1 | 0 | 1 | 1 | 0

* El número decimal 22 en binario es igual a 10110.
 
2. ¿Cuál es el resultado en decimal del número binario 10110?


10110 =

 1 *2^4 + 0 *2^3 + 1 *2^2 + 1 *2^1 + 0 *2^0 =

16+0+4+2+0= 22

* El número binario 10110 en decimal es igual a 22


 # Actividad 2

### Ejercicios

1. ¿Qué número binario representa el carácter 'C' en ASCII?

* Al investigar en la tabla ASCII el caracter "C" en número decimal es 67 y en número binario es igual a 01000011

2. Convierte el número flotante 5.75 a binario (explica los pasos).

* Para realizar esto se debe separar la parte entera y la decimal y lo convertimos a binario

* El entero 5 en binario es igual a 101 y
el decimal 0.75 es igual a 0.11

* Al hacer esto se deben unir ambas partes y obtenemos el número binario, en este caso seria 101.11


# Actividad 3

### Ejercicios

1. ¿Cuántos bytes se necesitan para almacenar la palabra “Hola” en ASCII?

* La palabra "Hola" se almacena en 4 bytes.

2. ¿Cuántos bits hay en 5 KB?

* La cantidad de bits en 5 KB son 40960.

# Actividad 4 

### Ejercicios

1. Convierte el número decimal 255 a hexadecimal.

* Dividimos entre 16:

* 255 ÷ 16 = 15, residuo 15

* 15 ÷ 16 = 0, residuo 15

* En hexadecimal es igual a F

2. ¿Cuál es el valor hexadecimal de la secuencia binaria 11010110?

* La secuencia binaria 11010110 se divide en dos grupos de 4 bits:

* 1101 → D
* *110 → 6

* el valor hexadecimal es D6


# Actividad Final

1. Explica, en tus propias palabras, por qué es necesario que las computadoras representen los datos en binario.

* Las computadoras usan binario porque su hardware solo puede distinguir con fiabilidad dos estados (encendido y apagado). Representarlos como 0 y 1 hace el sistema más simple, estable y resistente a errores, y con combinaciones binarias se puede representar cualquier tipo de información.

2. Convierte el número binario 10011011 a decimal y a hexadecimal.

* En Decimal es igual a 155
* En Hexadecimal 9B

3. Investiga y describe cómo se representa una imagen en formato PNG en el disco.

* Una imagen PNG se guarda en el disco como un archivo binario organizado. Empieza con una firma que identifica el formato y luego contiene varios bloques (chunks).
Algunos bloques guardan información básica de la imagen (tamaño, color), otros almacenan los datos de los píxeles comprimidos sin pérdida, y uno final indica el cierre del archivo.

4. Analiza la siguiente situación: ¿Qué sucede si intentas almacenar un número mayor al que puede representar un byte (por ejemplo, 300)? ¿Cómo lo maneja Python?

*  Un byte solo puede representar valores de 0 a 255, así que intentar guardar 300 provoca un desbordamiento en sistemas de tamaño fijo.
En Python, los enteros (int) no tienen ese límite: usan precisión arbitraria, por lo que 300 se almacena sin problemas.
El error solo aparece si se fuerza el uso de un byte, por ejemplo con bytes, que solo acepta valores entre 0 y 255.
