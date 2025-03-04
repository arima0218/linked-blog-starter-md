2025-03-04 

#Bases-de-Datos-2

- dentro de las consultas con varchar debería de tener en cuenta si lo que me piden tiene que ser una coincidencia exacta o puede variar en cuestión de mayúsculas.

- debo acostumbrarme a usar el order by en caso de que no este disponible el usar los filtros de dbeaver
```sql
select count(*) as cuenta, b.autor
from books b 
group by autor
order by cuenta desc;
```

- antes de modificar datos hacer una consulta 
```sql
select LENGTH(titulo), titulo
from books b
where LENGTH(titulo) -->, <, = a un dato; 
```
> función [[LENGTH]] 
- la función [[AGE]] me sirve para saber cuanto tiempo ha pasado entre una fecha y otra
[[ejercicios de datalemur]] 

- 