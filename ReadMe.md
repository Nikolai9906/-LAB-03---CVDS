# Clases de Equivalencia

|  Número        |Clase de equivalencia (en lenguaje natural o matemático).|Resultado correcto / incorrecto.        |
|----------------|-----------------------------------|-----------------------------|
|1		 |edad<18 \|\| edad>0                |Menor de edad           	   |
|2               |No esta vivo		             |Muerto                       |
|3	         |edad <= 0 \|\| edad > 150            |Edad Invalida|
|4	         |Id < 0|ID invalido        |
|5	         |Nombre NO SEA nulo && Nombre NO SEA vacio |Valido|

## AeroDescuentos

|  Número        |Clase de equivalencia (en lenguaje natural o matemático).|Resultado correcto / incorrecto.        |Resultado Esperado / Tarifa de 1000|
|----------------|-----------------------------------|-----------------------------|-----------------------------|
|1		 |diasAntelacion > 20 |Descuento 15%           	   |850|
|2               |edad < 18 |Descuento 5%                       |950|
|3	         |edad > 65|Descuento 8%|920
|4	         |diasAntelacion > 20 && edad < 18|Descuento 20%       |800|
|5	         |diasAntelacion > 20 && edad > 65|Descuento 23%|770|
|6	         |18 <= edad <= 65 \|\| 0 => diasAntelacion < 20 |Descuento 0%|1000|
|7	         |0 < edad  \|\| diasAntelacion < 0  |Incorrecto|Datos Invalidos |
|8	         |diasAntelacion = 20  |Incorrecto|Libreria perzonalizada tiene un error |


* A partir de las clases de equivalencia establecidas, las condiciones de limite o de frontera son:
- Edad < 18
- Edad = 18
- Edad > 18
- Edad > 65
- Edad = 65
- Edad < 65
- DiasAntelacion < 20
- DiasAntelacion = 20
- DiasAntelacion > 20

## Informacion Adicional
> Nos damos cuenta que existe un error en la libreria, debido a que cuando los dias de Antelacion es 20,no toma ningun caso referente a la edad. Lo cual implica que no se cumpla los esquemas de Clases de Equivalencia con las fronteras establecidas.
