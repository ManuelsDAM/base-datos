<div align="justify">


# Tema 3 Tarea-9 Lenguajes de definición/consulta y manipulación de información en Base de Datos (Trabajo con join y funciones matemáticas).

- Obtener el nombre del alumno y el nombre de la clase en la que está inscrito.
<details open>
<summary>Solución</summary>
  <''' sqlite> select * from Clases;
+----+------------------------+-------------+------------+
| id |         nombre         |   materia   |  profesor  |
+----+------------------------+-------------+------------+
| 1  | Matemáticas 101        | Matemáticas | Profesor X |
| 2  | Historia Antigua       | Historia    | Profesor Y |
| 3  | Literatura Moderna     | Literatura  | Profesor Z |
| 4  | Biología Avanzada      | Biología    | Profesor W |
| 5  | Química Orgánica       | Química     | Profesor V |
| 6  | Física Cuántica        | Física      | Profesor U |
| 7  | Arte Contemporáneo     | Arte        | Profesor T |
| 8  | Inglés Avanzado        | Idiomas     | Profesor S |
| 9  | Economía Internacional | Economía    | Profesor R |
| 10 | Derecho Penal          | Derecho     | Profesor Q |
+----+------------------------+-------------+------------+
sqlite> select * from Inscripciones;
+----+-----------+----------+
| id | id_alumno | id_clase |
+----+-----------+----------+
| 1  | 1         | 1        |
| 2  | 1         | 2        |
| 3  | 2         | 3        |
| 4  | 2         | 4        |
| 5  | 3         | 5        |
| 6  | 3         | 6        |
| 7  | 4         | 7        |
| 8  | 4         | 8        |
| 9  | 5         | 9        |
| 10 | 6         | 10       |
+----+-----------+----------+
sqlite> select * from Alumnos;
+----+--------+------+-----------+
| id | nombre | edad | direccion |
+----+--------+------+-----------+
| 1  | Juan   | 20   | Calle A   |
| 2  | María  | 21   | Calle B   |
| 3  | Pedro  | 19   | Calle C   |
| 4  | Laura  | 22   | Calle D   |
| 5  | Carlos | 20   | Calle E   |
| 6  | Ana    | 19   | Calle F   |
| 7  | Sofía  | 21   | Calle G   |
| 8  | Diego  | 20   | Calle H   |
| 9  | Lucía  | 22   | Calle I   |
| 10 | Miguel | 19   | Calle J   |
+----+--------+------+-----------+
  '''>
  </details>

---------------
- Obtener el nombre del alumno y la materia de las clases en las que está inscrito.

- Obtener el nombre del alumno, la edad y el nombre del profesor de las clases en las que está inscrito.

- Obtener el nombre del alumno y la dirección de las clases en las que está inscrito.

- Obtener el nombre del alumno y el nombre de la clase junto con el profesor.

- Obtener el nombre del alumno, la materia y el nombre del profesor de las clases en las que está inscrito.

- Obtener el nombre del alumno, la edad y la materia de las clases en las que está inscrito.

- Obtener el nombre del alumno, la dirección y el profesor de las clases en las que está inscrito.

- Obtener el nombre del alumno y la materia de las clases en las que está inscrito, ordenado por el nombre del alumno.

- Contar cuántos alumnos están inscritos en cada clase.

:tm: :shipit: :recycle: :goberserk:
 </div>