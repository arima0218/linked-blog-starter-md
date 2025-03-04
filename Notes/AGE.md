#sql

función para saber la diferencia de tiempo entre dos fechas

```sql
SELECT AGE('fecha1','fecha2');
```

output
a year b months c days, con a b c entero [[INT]] 

si quiero seleccionar una parte especifica de la fecha puedo usar [[DATE_PART]] 

```sql
SELECT DATE_PART('year', AGE('date1', 'date2'));
```