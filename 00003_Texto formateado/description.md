Ahora vamos analizar cómo está compuesto nuestro código.

``` c
/* Programa: Hola mundo */

#include <conio.h>
#include <stdio.h>

void main()
{
    printf( "Hola mundo.\n" );

    getch(); // Pausa 
}
```

> En el código anterior vemos dos maneras de comentar, la primera en la línea superior, delante y detrás de "Programa: Hola mundo" y se utilizan para comentar entre ambos caracteres (/* */).<br>La segunda, después de la sentencia getch, utiliza una doble barra (//) que también sirve para comentar, pero sólo hasta el final de la línea.

Dentro del printf, también vemos un par de caracteres que parecen un poco raros: `\n`.<br> Estos 2 caracteres sirven para indicarle al **compilador** que hay que hacer un salto de línea cuando muestre el texto por pantalla.<br>

Podemos ver algunos de estos caracteres especiales en la siguiente tabla:

<img src="https://raw.githubusercontent.com/otto-krause/mumuki-guia-c-introduccion/master/assets/Texto%20formateado_1540500170073.PNG" alt="Texto formateado_1540500170073.PNG" width="auto" height="auto">


