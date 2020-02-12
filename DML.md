DML-> Data Manipulation Language / Lenguaje de Manipulacion de Datos.  
SELECT-> Indica lo que se quiere extraer de una base de datos. (SELECT actor.name) <br>
FROM-> Indica de que tabla o tablas se extraen los elementos indicados en el SELECT. (FROM actor) <br>
WHERE-> Indica una condición que debe cumplirse para que se puedan extraer los elementos del SELECT. (WHERE age=30) <br><br>

ESTRUCTURA BÁSICA<br>
SELECT nombreElemento<br>
FROM nombreTabla<br>
WHERE condición;<br><br>

OTROS ELEMENTOS <br>
DISTINCT-> Pertenece al SELECT. Evita que el elemento que se extrae no se repita. (SELECT DISTINCT(actor.name))<br>
GROUP BY-> Agrupa los elementos del SELECT y se utiliza con consultas de funciones agragadas. Se añade despues del WHERE. (GROUP BY actor.name) <br>
