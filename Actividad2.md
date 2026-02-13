## Actividad 2

### Bitacora:

![símbolos de operación de un algoritmo con un diagrama de flujo](./img/DIAGRAMA1.JPG)

---

### Diagrama de flujo

![Diagrama de flujo Ej.](./img/Diagrama2.png)

---

## Pseudocodigos


### Un acuario necesita determinar cuántos litros o galones de agua caben en un acuario, pero solo dispone de una cinta métrica. Diseña un algoritmo para solucionar el problema.

**Valores de entrada**

|dato|Descripción|
|----|-----------|
|Largo |Largo del tanque en cm |
|Ancho |Ancho del tanque en cm |
|Alto|Alto del tanque en cm    |
|Unidad|Unidad de medida (litro o galón) del volumen total|

**Valores de salida**

|dato|Descripción|
|-|-|
|Vol_L|Volumen total del tanque en litros|
|Vol_G|Volumen total del tanque en litros|


#### pseudocodigo
Inició

mostrar"igrese medidas del tanque"

Leer Largo, Ancho, Alto

Mostrar"ingrese L para litros y G para galones"

Leer Unidad

Volumen= largo*Ancho*Alto

Vol_L= Volumen/1000

 si unidad = "L"

Mostrar Vol_L

si no 
    
vol_G= Vol_L*0.26

fin si 

fin

---

### Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo.

**Valores de entrada**

|dato|Descripción|
|----|-----------|
|CL| cantidad de lápices|
|||

**Valores de salida**

|dato|Descripción|
|-|-|
|PP|cuánto se debe pagar por equis cantidad de lápices |

**Valores intermedios**

|dato|Descripción|
|-|-|
|pre|precio asignado dependiendo de la cantidad|

#### pseudocodigo

inicio

mostrar "Ingresa la cantidad de lápices que comprara"

leer cl

si cl<1000

    pp= cl*90

si no

    pp= cl*85

fin si

Mostra pp

fin

---

### Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá. Represéntelo mediante el pseudocódigo y el diagrama de flujo.

**Valores de entrada**

|dato|Descripción|
|-|-|
|VC|Valor de la compra|


**Valor de salida**

|dato|Descripción|
|-|-|
|PF|precio final|

**Valores intermedios**

|dato|Descripción|
|-|-|
|Des|descuento asignado dependiendo el valor total de la compra|

Incio

mostar "ingrese el valor de la compra"

leer VC

si VC>250000

    PF= VC*0.15

si no

    PF=VC*0.08

fin si

Mostrar PF

fin.

----

### Una empresa necesita calcular el ingreso total y el promedio mensual del sueldo de un empleado durante 6 meses. Diseña un algoritmo para solucionar el problema.

**Valores de entrada**

|dato|Descripción|
|----|-----------|
|ID|Identificador del empleado (numérico)|
|S1|Sueldo del mes 1|
|S2|Sueldo del mes 2|
|S3|Sueldo del mes 3|
|S4|Sueldo del mes 4|
|S5|Sueldo del mes 5|
|S6|Sueldo del mes 6|

**Valores de salida**

|dato|Descripción|
|-|-|
|Total|Ingreso total de los 6 meses|
|Prom|Promedio mensual|
|ID|Identificador del empleado|

**Valores intermedios**

|dato|Descripción|
|-|-|
|Total|Suma de los 6 sueldos|

#### pseudocodigo
Inicio

mostrar "Ingrese el ID del empleado"

Leer ID

mostrar "Ingrese los 6 sueldos"

Leer S1, S2, S3, S4, S5, S6

Total = S1 + S2 + S3 + S4 + S5 + S6

Prom = Total / 6

Mostrar ID

Mostrar Total

Mostrar Prom

Fin
---



