Retomando la idea anterior de que una variable es como una caja, tratemos de imaginar la siguiente situación<br>

Nos encontramos con 2 tipos de "cajas":

* Caja de zapatos
+ Pecera con agua

<img src="https://raw.githubusercontent.com/otto-krause/mumuki-guia-c-introduccion/master/assets/CORTADA_CAB_BLAN_BLAN_m_1540418719897.jpg" alt="CORTADA_CAB_BLAN_BLAN_m_1540418719897.jpg" width="auto" height="auto">
<img src="https://raw.githubusercontent.com/otto-krause/mumuki-guia-c-introduccion/master/assets/resultadoAc_1540419061768.jpg" alt="resultadoAc_1540419061768.jpg" width="400" height="auto">
<br>
Y ahora imaginemos que tenemos:

* Un pez
+ Un par de zapatos

Si pusiéramos al pez dentro de la pecera y al par de zapatos dentro de la caja de zapatos, estaríamos siguiendo el propósito natural para el que fueron creadas estas cajas.<br>

**¿Qué pasaria si no siguieramos este propósito natural?**<br>
Simplemente pensémoslo:<br>

* _Pongo el pez dentro de la caja de zapatos, probablemente el pez **muera**.<br>_
+ _Pongo el par de zapatos dentro de la pecera, probablemente se **arruinen**.<br>_

<br>
Tenemos diferentes **tipos de objetos** (el pez y los zapatos) y diferentes **tipos de cajas** (la de zapatos, la pecera) y acabamos de ver las consecuencias negativas de poner las cosas en lugares que no corresponden. <br>

Podemos llevar esta misma idea a la programación, existen diferentes **tipos de datos** (números, cadenas, banderas, etc) y diferentes **tipos de variables**, que veremos a continuacion: 

> `int`: Sirve para almacenar números enteros<br>
`float`: Sirve para almacenar números con _coma flotante_<br>
`char`: Sirve para almacenar un caracter<br>
`bool`: Sirve para almacenar un valor de tipo bandera (`true` o `false`)<br>

Ejemplo de uso:

``` c
int num = 3; //Número entero
char car = 'j'; //Caracter j
float num2 = 14.23; //Número con coma flotante
```

<br>
Algunas consideraciones a tener en cuenta:

* Para asignar un valor a una variable de tipo char se deben utilizar comillas
+ Todo lo que está después de `//` son comentarios, es decir que no provocan ningún efecto durante la ejecución del programa
+ Si no te acordás de que es un número entero, podés entrar [acá](https://es.wikipedia.org/wiki/N%C3%BAmero_entero)

