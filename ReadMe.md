# Clases de Equivalencia

|  Número        |Clase de equivalencia (en lenguaje natural o matemático).|Resultado correcto / incorrecto.        |
|----------------|-----------------------------------|-----------------------------|
|1		 |edad<18 \|\| edad>0                |Menor de edad           	   |
|2               |No esta vivo		             |Muerto                       |
|3	         |edad <= 0 \|\| edad > 150            |Edad Invalida|
|4	         |Id < 0|ID invalido        |
|5	         |Nombre NO SEA nulo && Nombre NO SEA vacio |Valido|

## AeroDescuentos

|  Número        |Clase de equivalencia (en lenguaje natural o matemático).|Resultado correcto / incorrecto.        |
|----------------|-----------------------------------|-----------------------------|
|1		 |diasAntelacion > 20 |Descuento 15%           	   |
|2               |edad < 18 |Descuento 5%                       |
|3	         |edad > 65|Descuento 8%|
|4	         |diasAntelacion > 20 && edad < 18|Descuento 20%       |
|5	         |diasAntelacion > 20 && edad > 65|Descuento 23%|
|6	         |18 <= edad <= 65 \|\| 0 => diasAntelacion <= 20 |Descuento 0%|
|7	         |0 < edad  \|\| diasAntelacion < 0  |Incorrecto|