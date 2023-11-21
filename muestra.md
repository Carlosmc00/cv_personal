# Ejemplos de código

## Kotlin
```kotlin
fun main() {
    val numero = readln()

    if (numero.toInt() % 2 == 0){
        println("$numero es un número par")
    }
    else if (numero.toInt() % 2 != 0){
        println("$numero es un número impar")
    }
}
```
## Java
```java
class prog{
    public static void main (String [] args){
        for (int i=0; i<100; i++){
	    int numero = i;
        int cuadrado = i*numero;
	    String numeroFormateado = String.format("%04d", cuadrado);
	    System.out.print(numeroFormateado + "  ");
	    if ((i + 1) % 10 == 0){
	    	System.out.println("");
	        }
        }
    }
}
```
## C
```c
#include <stdio.h>

int esPrimo(int num) {
    if (num <= 1) {
        return 0; // 0 y 1 no son primos
    }

    for (int i = 2; i * i <= num; i++) {
        if (num % i == 0) {
            return 0; // No es primo
        }
    }

    return 1; // Es primo
}

int main() {
    int numero;

    printf("Ingrese un número: ");
    scanf("%d", &numero);

    if (esPrimo(numero)) {
        printf("%d es un número primo.\n", numero);
    } else {
        printf("%d no es un número primo.\n", numero);
    }

    return 0;
}

```

## Muestra de trabajo en Github
[Click aquí para acceder al repositorio](https://github.com/Carlosmc00/libro-git)