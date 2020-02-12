**DML**-> Data Manipulation Language / Lenguaje de Manipulacion de Datos.  
**SELECT**-> Indica lo que se quiere extraer de una base de datos. (```sql SELECT actor.name```)  
**FROM**-> Indica de que tabla o tablas se extraen los elementos indicados en el **SELECT**. (```FROM actor```)  
**WHERE**-> Indica una condición que debe cumplirse para que se puedan extraer los elementos del **SELECT**. (```WHERE age=30```)  

ESTRUCTURA BÁSICA 
```sql
SELECT nombreElemento  
FROM nombreTabla  
WHERE condición;  
```
OTROS ELEMENTOS  
**DISTINCT**-> Pertenece al SELECT. Evita que el elemento que se extrae no se repita. (SELECT DISTINCT(actor.name))  
**GROUP BY**-> Agrupa los elementos del SELECT y se utiliza con consultas de funciones agragadas. Se añade despues del WHERE. (GROUP BY actor.name)  
**HAVING**-> Su función es similar al **WHERE**, pero la condición se aplica a las funciones de agragado. Siempre va acompañado de **GROUP BY**
