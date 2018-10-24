Te acordas de que es un operador? Si no te acordas, te refrescamos la memoria.<br>
Un operador es el símbolo que se usa para representar a una operación, para que lo entiendas mejor:
> El operador **( + )** representa a la suma<br>
El operador **( - )** representa a la resta<br>
El operador **( * )** representa a la multiplicacion<br>
El operador **( / )** representa a la division<br>
El operador **( % )** representa al resto de una division<br>

Ahora sí, un operador lógico es un operador que sirve para evaluar una condicion, por ejemplo:

Si yo digo que 4 es mayor a 3 => el resultado de esa condicion es **verdadero**<br>

A la condición _es mayor a_ le corresponde un operador lógico! Y la misma se escribiria de la siguiente forma:<br>

### 4 **>** 3
<br>

El resultado de esta condicion sería `true`.
<br>

El resto de los operadores lógicos que conocemos son:<br>

> El operador **( > )** significa **mayor a**<br>
El operador **( < )** significa **menor a**<br>
El operador **( >= )** significa **mayor o igual a**<br>
El operador **( <= )** significa **menor o igual a**<br>
El operador **( == )** significa **igual a**<br>
El operador **( != )** significa **distinto a**<br>

Veamos algunos ejemplos de uso:<br>

``` c
3 < 2     ム false
6 >= 1    ム true
12 == 12  ム true
```
<br>
Existen otros 2 operadores lógicos, pero estos son un poco especiales, actúan sobre otras condiciones ya creadas.
> El operador **( && )** significa **AND** y devuelve verdadero cuando se cumplen las 2 condiciones<br>
El operador **( || )** significa **OR** y devuelve verdadero cuando se cumple alguna de las 2 condiciones<br>

Ejemplos de uso:<br>

``` c
(3 < 2) && (6 >= 1)   ム false
(3 < 2) || (6 >= 1)   ム true
(12 == 12) && (4 > 3) ム true

((3 < 2) && (6 >= 1)) || ((12 == 12) && (4 > 3)) ム true
```
