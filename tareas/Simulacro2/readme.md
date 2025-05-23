<div align="justify">

#  Unidad 2 Tarea 2: Modelo Entidad/Relación

##  🔎 Parte 1: Consultas SQL

### A. Consultas simples: 
1.  Mostrar todos los cursos disponibles.
```console
SELECT * from cursos
```
|id|	nombre|	profesor_id	|creditos |
---|---------|--------|----------------|
|1	|Ãlgebra Lineal 	|1	|6 |
|2|	ProgramaciÃ³n I	|2|	5|
|3|	MecÃ¡nica ClÃ¡sica|	3|	6|
|4|	Estructuras de Datos|	2|	5|
|5|	CÃ¡lculo I	|1|	6| 


2. Mostrar el nombre de todos los profesores.

```sql
seelct nombre from profesores;
```

|nombre|
|-------|
|Dra. Ana Torres|
|Dr. Luis GÃ³mez|
|Dra. Marta DÃ­az|

3. Listar todas las matrículas.

```sql
select * from matriculas;

```
|id	|estudiante_id	|curso_id	|fecha|
|-|--|---|--|
|1|	1|	1|	2021-09-01|
|2|	2|	2|	2022-09-01|
|3|	3|	3|	2023-09-02|
|4|	4|	4|	2024-09-03|
|5|	1|	5|	2020-09-04|
|6|	2|	4|	2022-09-05|
|7|	3|	1|	2023-09-06|
|8|	4|	2|	2024-09-06|


4. Ver los nombres y correos de los estudiantes.

```sql
```

5. Ver los cursos y su número de créditos.

```sql
```
---

### B. Consultas con `WHERE`. Obligatorio utilizar **WHERE** donde se **combine dos o más tablas**

1. Obtener los cursos impartidos por profesores del departamento de Informática.

```sql
```

2. Obtener los estudiantes que viven en Madrid.

```sql
```

3. Mostrar los cursos con más de 5 créditos.

```sql
```

4. Ver las matrículas realizadas después del año 2022.

```sql
```

5. Ver los cursos impartidos por la profesora “Dra. Ana Torres”.

```sql
```

---

### C. Consultas con `JOIN`.  Obligatorio utilizar **JOIN** donde se **combine dos o más tablas**

> (Devuelven el mismo resultado que las anteriores, pero usando combinaciones de tablas)

1. Mostrar cursos impartidos por profesores del departamento de Informática.

```sql
```

2. Obtener estudiantes que viven en Madrid.

```sql
```

3. Mostrar cursos con más de 5 créditos.

```sql
```

4. Listar matrículas realizadas después del año 2022.

```sql
```

5. Mostrar los cursos impartidos por la profesora “Dra. Ana Torres”.

```sql
```
---

### D. Consultas con Subconsultas

> (Devuelven el mismo resultado que las anteriores, pero usando subconsultas)

1. Cursos impartidos por profesores del departamento de Informática.

```sql
```

2. Estudiantes que viven en Madrid.

```sql
```

3. Cursos con más de 5 créditos.

```sql
```

4. Matrículas realizadas después del año 2022.

```sql
```

5. Cursos impartidos por la profesora “Dra. Ana Torres”.

```sql
```

---

## 📂 Parte 2: Índices

1. Crear un índice en la columna `ciudad` de la tabla `estudiantes`.

```sql
```

2. Crear un índice en la columna `departamento` de la tabla `profesores`.

```sql
```

3. Consultar los índices creados.

```sql
```

4. Eliminar ambos índices.

```sql
```
---

## 🪞 Parte 3: Vistas

1. Crear una vista llamada `vista_matriculas_completas` que muestre:
   - nombre del estudiante,
   - nombre del curso,
   - fecha de la matrícula.

```sql
```

2. Consultar datos desde la vista, mostrando el nombre del estudiante y la fecha de matrícula.

```sql
```

3. Eliminar la vista.

```sql
```

---

## ⚙ Parte 4: Procedimiento Almacenado

1. Crear un procedimiento llamado `cursos_por_profesor` que reciba el nombre del profesor como parámetro y devuelva los cursos que imparte y su número de créditos.

```sql
```

2. Ejecutar el procedimiento con el nombre “Dr. Luis Gómez”.

```sql
```

3. Eliminar el procedimiento.

```sql
```

---

## 🔢 Parte 5: Función Definida por el Usuario

1. Crear una función llamada `total_creditos_estudiante` que reciba el ID de un estudiante y devuelva el total de créditos que ha matriculado.

```sql
```

2. Ejecutar la función para un estudiante específico.

```sql
```

3. Eliminar la función.

```sql
```


 :recycle: :goberserk: :tm:
</div>