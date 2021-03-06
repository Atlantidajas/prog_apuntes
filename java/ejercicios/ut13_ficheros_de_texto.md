# UT13. Ficheros de Texto


__Ejercicio 1__

Escribe un programa que guarde en un fichero con nombre primos.dat los números primos que hay entre 1 y 500.

__Ejercicio 2__

Realiza un programa que lea el fichero creado en el ejercicio anterior y que muestre los números por pantalla.

__Ejercicio 3__

Escribe un programa que guarde en un fichero el contenido de otros dos ficheros, de tal forma que en el fichero resultante aparezcan las líneas de los primeros dos ficheros mezcladas, es decir, la primera línea será del primer fichero, la segunda será del segundo fichero, la tercera será la siguiente del primer fichero, etc.

Hay que tener en cuenta que los ficheros de donde se van cogiendo las líneas pueden tener tamaños diferentes.

__Ejercicio 4__

Realiza un programa que sea capaz de ordenar alfabéticamente las palabras contenidas en un fichero de texto. El nombre del fichero que contiene las palabras se debe pasar como argumento en la línea de comandos. El nombre del fichero resultado debe ser el mismo que el original añadiendo la coletilla sort, por ejemplo palabras_sort.txt. Suponemos que cada palabra ocupa una línea.

__Ejercicio 5__

Escribe un programa capaz de quitar los comentarios de un programa de Java. Crea un fichero con nombre holav2.java que contiene el código de hola.java, pero sin los comentarios.

__Ejercicio 6__

Realiza un programa que diga cuántas ocurrencias de una palabra hay en un fichero.

## Ejercicios CSV

__Ejercicio 7__

Dado el fichero _datos.csv_ con la siguiente información:

```bash
2001;Jorge Luis Garcia Sifuentes;jlgarcias@gmail.com
2002;Miguel Jose Guevara Martinez;mguevara@yahoo.com
2003;Juan Carlos Mendoza Cruz;jcmendoza@hotmail.com
```

Cargar los datos del fichero en una estructura que permita ordenarlos por nombre. Una vez ordenado, guardarlo en el fichero _datos_ordenados.csv_.

__Ejercicio 8__

Dado el fichero [books.csv](https://gist.githubusercontent.com/jaidevd/23aef12e9bf56c618c41/raw/c05e98672b8d52fa0cb94aad80f75eb78342e5d4/books.csv), realizar un programa que permita cargar los datos en memoria y luego ordenados por nombre y guardar los datos ordenados en el fichero _libros_ordenados.csv_.

> __Nota__: Tener en cuenta que este fichero contiene una cabecera (primera línea con los nombres de los campos).