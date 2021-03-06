# UT07. MÉTODOS Y SENTENCIA RETURN


__Ejercicio 1__

Crear un método llamado _imprimirMensaje()_ que imprima un mensaje por pantalla. Este mensaje debe pedirse por teclado al usuario y también debe pasarse como parámetro al método _imprimirMensaje()_.

> El tipo de la variable _mensaje_ ha de ser de tipo _String_ y ha de usarse el método de la clase Scanner _nextLine()_ para leer el mensaje por teclado.

__Ejercicio 2__

Crear un método llamado _sumarNumeros()_ que llamaremos desde el método _main()_ y que obtenga el sumatorio entre los números 1 y n, siendo n un número entero introducido por teclado. El número n ha de pasarse como parámetro al método _sumarNumeros().

__Ejercicio 3__

Crear un método llamado _imprimirPares()_ que imprima los números pares que existen del 1 al 20.

__Ejercicio 4__

Crear un método llamado _imprimirImpares()_ que imprima los números impares que existen del 1 al 20. Aparte, crear un menú para permitir al usuario si quiere imprimir los números impares del 1 al 20 o si por el contrario desea imprimir los números pares del 1 al 20 mediante el método desarrollado en el _Ejercicio 3_.

Un ejemplo de la salida podría ser la siguiente:

```bash
Menú:
1. Imprimir números pares del 1 al 20.
2. Imprimir números impares del 1 al 20.
0. Salir.
Su opción: 1
2 4 6 8 10 12 14 16 18 20

Menú:
1. Imprimir números pares del 1 al 20.
2. Imprimir números impares del 1 al 20.
0. Salir.
Su opción: 2
1 3 5 7 9 11 13 15 17 19

Menú:
1. Imprimir números pares del 1 al 20.
2. Imprimir números impares del 1 al 20.
0. Salir.
Su opción: 0
Saliendo del programa
```

__Ejercicio 5__

Crear un programa que, mediante un menú, le de al usuario la opción de:

1. Convertir de grados Centígrados a grados Fahrenheit.
2. Convertir de grados Fahrenheit a grados Centígrados.

Crear un método distinto para cada una de las dos opciones.


__Ejercicio 6__

Crear un método llamado _calcularAnyoBisiesto()_ que imprima si un año es bisiesto o no. Para ello el programa deberá pedir un año por teclado y pasárselo por parámetro al método calcularAnyoBisiesto()_.

> Los años bisiestos son aquellos que duran 366 días en vez de los 365 normales. El día de más que tiene el año es el 29 de febrero. Esto sucede para corregir el desfase real de la duración de un año, que es de 365 días y 6 horas.

Para saber si un año es bisiesto se puede aplicar una simple formula, la cual dice que un año es bisiesto si es divisible por cuatro, excepto los principios de año (los divisibles por 100), que para ser bisiestos deben de ser divisibles también por 400.

> Java ofrece una forma más sencilla de resolver si un año es bisiesto. Y es que nos proporciona la clase __GregorianCalendar__ y en concreto el método __.isLeapYear(anyo)__. Este método devolverá true o false, según corresponda:

```java
GregorianCalendar calendar = new GregorianCalendar();
 
if (calendar.isLeapYear(anyo))
	System.out.println("El año es bisiesto");
else
	System.out.println("El año no es bisiesto");
```