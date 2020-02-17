# APUNTES

SQL

El SQL es un lenguaje de consulta para administrar información en sistemas de bases de datos.

Las sentencias principales para realizar una consulta son: 

SELECT- Esta sentencia se usa para seleccionar la información que se quiere.

FROM- Escoge la tabla de donde se sacará la información escogida.

WHERE- Sirve para especificar las condiciones que queremos para realizar la consulta.

Otras sentencias que también se pueden utilizar para consultas más específicas son:

ORDER BY- sirve para ordenar los resultados de la consulta alfabética o numéricamente y en orden ascendente (ASC) o desdencente (DESC).

HAVING- especifica una condición que debe tener el resultado después de ordenarlos mediante ORDER BY o una función de agregado.

GROUP BY:  esta sentencia se usa para recoger los resultados en grupos especificados y dividirlos por filas.


OPERADORES

- LIKE: este operador se usa con WHERE y se usa para introducir un patrón o expresión para buscar los resultados que deseemos que aparezcan.

- BETWEEN: se utiliza con WHERE para seleccionar valores entre un rango de dos números.

- AND: este operador lógico es usado para combinar 2 condiciones que tienen que ser ciertas para cumplirse.

- OR: este, por otro lado, combina 2 condiciones de las que una tiene que ser cierta.

- IN: es utilizado para devolver los resultados que coincidan en la tabla con el valor que se indica.

- DISTINCT: usado para recibir los resultados sin tener repeticiones.


FUNCIONES DE AGREGADO

- AVG: devuelve el valor correspondiente a la media de los resultados de la tabla escogida.

- COUNT:  cuenta el número de elementos que devuelve el resultado.
 
- MAX/MIN: devuelve el valor máximo o mínimo de los resultados de la tabla escogida.
 
- SUM: suma los valores de la tabla escogida.







 Hay otras cláusulas utilizadas para mejorar el rendimiento del lenguaje tales como:

- JOIN: esta sentencia permite combinar datos de varias tablas.

	- INNER: devuelve los resultados de las dos tablas seleccionadas.	
	- LEFT: devuelve los resultados de la tabla de la izquierda que coincidan en la de laderecha.
	- RIGHT: devuelve los resultados de la tabla de la derecha que coincidan en la de la izquierda.
	
