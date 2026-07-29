# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 1 correctas de 26 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,25 @@
 apellido1 | apellido2 | nombre
+Sánchez | Pérez | Salvador
+Saez | Vega | Juan
+Ramirez | Gea | Zoe
+Heller | Pagac | Pedro
+Schmidt | Fisher | David
+Koss | Bayer | José
+Strosin | Turcotte | Ismael
+Lemke | Rutherford | Cristina
+Herzog | Tremblay | Ramón
+Spencer | Lakin | Esther
+Herman | Pacocha | Daniel
+Streich | Hirthe | Carmen
+Stiedemann | Morissette | Alfredo
+Hamill | Kozey | Manolo
+Kohler | Schoen | Alejandro
+Fahey | Considine | Antonio
+Ruecker | Upton | Guillermo
+Monahan | Murray | Micaela
+Lakin | Yundt | Inma
+Schowalter | Muller | Francesca
+Gutiérrez | López | Juan
 Domínguez | Guerrero | Antonio
+Hernández | Martínez | Irene
 Gea | Ruiz | Sonia
-Gutiérrez | López | Juan
-Heller | Pagac | Pedro
-Herman | Pacocha | Daniel
-Hernández | Martínez | Irene
-Herzog | Tremblay | Ramón
-Koss | Bayer | José
-Lakin | Yundt | Inma
-Saez | Vega | Juan
-Sánchez | Pérez | Salvador
-Strosin | Turcotte | Ismael
```

⏱ Tiempo: 0.38 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,8 @@
-nombre | apellido1 | apellido2
+Nombre | Apellido 1 | Apellido 2
 Pedro | Heller | Pagac
 Ismael | Strosin | Turcotte
+Esther | Spencer | Lakin
+Carmen | Streich | Hirthe
+Antonio | Fahey | Considine
+Guillermo | Ruecker | Upton
+Francesca | Schowalter | Muller
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 3: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-id | nombre | apellido1 | apellido2 | fecha_nacimiento
-7.00 | Ismael | Strosin | Turcotte | 1999-05-24
-22.00 | Antonio | Domínguez | Guerrero | 1999-02-11
+Nombre | Apellido 1 | Apellido 2 | NIF | Fecha Nacimiento
+Ismael | Strosin | Turcotte | 97258166K | 1999-05-24
+Antonio | Domínguez | Guerrero | 41491230N | 1999-02-11
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,6 @@
-nombre | apellido1 | apellido2 | nif
-Antonio | Fahey | Considine | 10485008K
-Guillermo | Ruecker | Upton | 85869555K
+Nombre | Apellido
+Esther | Spencer
+Carmen | Streich
+Antonio | Fahey
+Guillermo | Ruecker
+Francesca | Schowalter
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,7 +1,42 @@
-id | nombre | cuatrimestre | curso | id_grado
-72.00 | Bases moleculares del desarrollo vegetal | 1.00 | 3.00 | 7.00
-73.00 | Fisiología animal | 1.00 | 3.00 | 7.00
-74.00 | Metabolismo y biosíntesis de biomoléculas | 1.00 | 3.00 | 7.00
-75.00 | Operaciones de separación | 1.00 | 3.00 | 7.00
-76.00 | Patología molecular de plantas | 1.00 | 3.00 | 7.00
-77.00 | Técnicas instrumentales básicas | 1.00 | 3.00 | 7.00
+Asignatura
+Álgegra lineal y matemática discreta
+Cálculo
+Física para informática
+Introducción a la programación
+Organización y gestión de empresas
+Arquitectura de Computadores
+Estructura de Datos y Algoritmos I
+Ingeniería del Software
+Sistemas Inteligentes
+Sistemas Operativos
+Desarrollo de interfaces de usuario
+Ingeniería de Requisitos
+Integración de las Tecnologías de la Información en las Organizaciones
+Modelado y Diseño del Software 1
+Multiprocesadores
+Seguridad y cumplimiento normativo
+Sistema de Información para las Organizaciones
+Tecnologías web
+Teoría de códigos y criptografía
+Administración de redes y sistemas operativos
+Almacenes de Datos
+Fiabilidad y Gestión de Riesgos
+Líneas de Productos Software
+Procesos de Ingeniería del Software 1
+Tecnologías multimedia
+Biologia celular
+Física
+Matemáticas I
+Química general
+Química orgánica
+Botánica agrícola
+Fisiología vegetal
+Genética molecular
+Ingeniería bioquímica
+Termodinámica y cinética química aplicada
+Bases moleculares del desarrollo vegetal
+Fisiología animal
+Metabolismo y biosíntesis de biomoléculas
+Operaciones de separación
+Patología molecular de plantas
+Técnicas instrumentales básicas
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
-apellido1 | apellido2 | nombre | departamento
-Fahey | Considine | Antonio | Economía y Empresa
+Apellido 1 | Apellido 2 | Nombre | Departamento
+Ramirez | Gea | Zoe | Informática
 Hamill | Kozey | Manolo | Informática
+Schmidt | Fisher | David | Matemáticas
 Kohler | Schoen | Alejandro | Matemáticas
 Lemke | Rutherford | Cristina | Economía y Empresa
+Fahey | Considine | Antonio | Economía y Empresa
+Spencer | Lakin | Esther | Educación
+Streich | Hirthe | Carmen | Educación
+Ruecker | Upton | Guillermo | Educación
 Monahan | Murray | Micaela | Agronomía
-Ramirez | Gea | Zoe | Informática
-Ruecker | Upton | Guillermo | Educación
-Schmidt | Fisher | David | Matemáticas
+Stiedemann | Morissette | Alfredo | Química y Física
 Schowalter | Muller | Francesca | Química y Física
-Spencer | Lakin | Esther | Educación
-Stiedemann | Morissette | Alfredo | Química y Física
-Streich | Hirthe | Carmen | Educación
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | anyo_inicio | anyo_fin
+Asignatura | Año inicio | Año fin
 Álgegra lineal y matemática discreta | 2014.00 | 2015.00
 Cálculo | 2014.00 | 2015.00
 Física para informática | 2014.00 | 2015.00
```

⏱ Tiempo: 0.51 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif, PRIMARY

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre
+Departamento
 Informática
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY,id_departamento, PRIMARY

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | apellido1 | apellido2
+Nombre | Apellido 1 | Apellido 2
 Inma | Lakin | Yundt
 Irene | Hernández | Martínez
 Sonia | Gea | Ruiz
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-departamento | apellido1 | apellido2 | nombre
+Departamento | Apellido 1 | Apellido 2 | Nombre
 Agronomía | Monahan | Murray | Micaela
 Economía y Empresa | Fahey | Considine | Antonio
 Economía y Empresa | Lemke | Rutherford | Cristina
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 11: Incorrecto
```diff
--- 
+++ 
@@ -1 +1 @@
-apellido1 | apellido2 | nombre
+Apellido 1 | Apellido 2 | Nombre
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 12: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre
+Departamento
 Filología
 Derecho
 Biología y Geología
```

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-apellido1 | apellido2 | nombre
+Apellido 1 | Apellido 2 | Nombre profesor
 Schmidt | Fisher | David
 Kohler | Schoen | Alejandro
 Lemke | Rutherford | Cristina
```

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ❌ Query 14: Incorrecto
```diff
--- 
+++ 
@@ -1,63 +1,63 @@
-id | nombre
-22.00 | Ingeniería de Requisitos
-23.00 | Integración de las Tecnologías de la Información en las Organizaciones
-24.00 | Modelado y Diseño del Software 1
-25.00 | Multiprocesadores
-26.00 | Seguridad y cumplimiento normativo
-27.00 | Sistema de Información para las Organizaciones
-28.00 | Tecnologías web
-29.00 | Teoría de códigos y criptografía
-30.00 | Administración de bases de datos
-31.00 | Herramientas y Métodos de Ingeniería del Software
-32.00 | Informática industrial y robótica
-33.00 | Ingeniería de Sistemas de Información
-34.00 | Modelado y Diseño del Software 2
-35.00 | Negocio Electrónico
-36.00 | Periféricos e interfaces
-37.00 | Sistemas de tiempo real
-38.00 | Tecnologías de acceso a red
-39.00 | Tratamiento digital de imágenes
-40.00 | Administración de redes y sistemas operativos
-41.00 | Almacenes de Datos
-42.00 | Fiabilidad y Gestión de Riesgos
-43.00 | Líneas de Productos Software
-44.00 | Procesos de Ingeniería del Software 1
-45.00 | Tecnologías multimedia
-46.00 | Análisis y planificación de las TI
-47.00 | Desarrollo Rápido de Aplicaciones
-48.00 | Gestión de la Calidad y de la Innovación Tecnológica
-49.00 | Inteligencia del Negocio
-50.00 | Procesos de Ingeniería del Software 2
-51.00 | Seguridad Informática
-52.00 | Biologia celular
-53.00 | Física
-54.00 | Matemáticas I
-55.00 | Química general
-56.00 | Química orgánica
-57.00 | Biología vegetal y animal
-58.00 | Bioquímica
-59.00 | Genética
-60.00 | Matemáticas II
-61.00 | Microbiología
-62.00 | Botánica agrícola
-63.00 | Fisiología vegetal
-64.00 | Genética molecular
-65.00 | Ingeniería bioquímica
-66.00 | Termodinámica y cinética química aplicada
-67.00 | Biorreactores
-68.00 | Biotecnología microbiana
-69.00 | Ingeniería genética
-70.00 | Inmunología
-71.00 | Virología
-72.00 | Bases moleculares del desarrollo vegetal
-73.00 | Fisiología animal
-74.00 | Metabolismo y biosíntesis de biomoléculas
-75.00 | Operaciones de separación
-76.00 | Patología molecular de plantas
-77.00 | Técnicas instrumentales básicas
-78.00 | Bioinformática
-79.00 | Biotecnología de los productos hortofrutículas
-80.00 | Biotecnología vegetal
-81.00 | Genómica y proteómica
-82.00 | Procesos biotecnológicos
-83.00 | Técnicas instrumentales avanzadas
+Asignatura
+Ingeniería de Requisitos
+Integración de las Tecnologías de la Información en las Organizaciones
+Modelado y Diseño del Software 1
+Multiprocesadores
+Seguridad y cumplimiento normativo
+Sistema de Información para las Organizaciones
+Tecnologías web
+Teoría de códigos y criptografía
+Administración de bases de datos
+Herramientas y Métodos de Ingeniería del Software
+Informática industrial y robótica
+Ingeniería de Sistemas de Información
+Modelado y Diseño del Software 2
+Negocio Electrónico
+Periféricos e interfaces
+Sistemas de tiempo real
+Tecnologías de acceso a red
+Tratamiento digital de imágenes
+Administración de redes y sistemas operativos
+Almacenes de Datos
+Fiabilidad y Gestión de Riesgos
+Líneas de Productos Software
+Procesos de Ingeniería del Software 1
+Tecnologías multimedia
+Análisis y planificación de las TI
+Desarrollo Rápido de Aplicaciones
+Gestión de la Calidad y de la Innovación Tecnológica
+Inteligencia del Negocio
+Procesos de Ingeniería del Software 2
+Seguridad Informática
+Biologia celular
+Física
+Matemáticas I
+Química general
+Química orgánica
+Biología vegetal y animal
+Bioquímica
+Genética
+Matemáticas II
+Microbiología
+Botánica agrícola
+Fisiología vegetal
+Genética molecular
+Ingeniería bioquímica
+Termodinámica y cinética química aplicada
+Biorreactores
+Biotecnología microbiana
+Ingeniería genética
+Inmunología
+Virología
+Bases moleculares del desarrollo vegetal
+Fisiología animal
+Metabolismo y biosíntesis de biomoléculas
+Operaciones de separación
+Patología molecular de plantas
+Técnicas instrumentales básicas
+Bioinformática
+Biotecnología de los productos hortofrutículas
+Biotecnología vegetal
+Genómica y proteómica
+Procesos biotecnológicos
+Técnicas instrumentales avanzadas
```

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,5 +1,4 @@
-nombre
-Informática
+Departamento
 Matemáticas
 Economía y Empresa
 Educación
```

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_profesor, id_departamento

---

## ❌ Query 16: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-total
+Total alumnos
 12.00
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 17: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-total
+Alumnos nacidos en 1999
 2.00
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-departamento | total
+Departamento | Total profesores
 Educación | 3.00
 Informática | 2.00
 Matemáticas | 2.00
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
-departamento | total
+Departamento | Total profesores
+Educación | 3.00
 Informática | 2.00
 Matemáticas | 2.00
 Economía y Empresa | 2.00
-Educación | 3.00
+Química y Física | 2.00
 Agronomía | 1.00
-Química y Física | 2.00
 Filología | 0.00
 Derecho | 0.00
 Biología y Geología | 0.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-grau | total
+Grado | Total asignaturas (↓)
 Grado en Ingeniería Informática (Plan 2015) | 51.00
 Grado en Biotecnología (Plan 2015) | 32.00
 Grado en Ingeniería Agrícola (Plan 2015) | 0.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-grau | total
+Grado | Total asignaturas
 Grado en Ingeniería Informática (Plan 2015) | 51.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-grau | tipo | total_creditos
+Grado | Tipo asignatura | Total créditos
 Grado en Ingeniería Informática (Plan 2015) | básica | 72.00
 Grado en Ingeniería Informática (Plan 2015) | obligatoria | 54.00
 Grado en Ingeniería Informática (Plan 2015) | optativa | 180.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,14 @@
-anyo_inicio | total
-2014.00 | 3.00
-2018.00 | 3.00
+Año inicio curso | Año fin curso | Asignatura | Alumnos
+2014.00 | 2015.00 | Álgegra lineal y matemática discreta | 3.00
+2018.00 | 2019.00 | Álgegra lineal y matemática discreta | 3.00
+2014.00 | 2015.00 | Cálculo | 3.00
+2018.00 | 2019.00 | Cálculo | 3.00
+2014.00 | 2015.00 | Física para informática | 3.00
+2018.00 | 2019.00 | Física para informática | 3.00
+2018.00 | 2019.00 | Introducción a la programación | 3.00
+2018.00 | 2019.00 | Organización y gestión de empresas | 3.00
+2018.00 | 2019.00 | Estadística | 3.00
+2018.00 | 2019.00 | Estructura y tecnología de computadores | 3.00
+2018.00 | 2019.00 | Fundamentos de electrónica | 3.00
+2018.00 | 2019.00 | Lógica y algorítmica | 3.00
+2018.00 | 2019.00 | Metodología de la programación | 3.00
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
-id | nombre | apellido1 | apellido2 | total
-14.00 | Manolo | Hamill | Kozey | 11.00
+ID Profesor | Nombre | Primer apellido | Segundo apellido | Total asignaturas
 3.00 | Zoe | Ramirez | Gea | 10.00
 5.00 | David | Schmidt | Fisher | 0.00
-15.00 | Alejandro | Kohler | Schoen | 0.00
 8.00 | Cristina | Lemke | Rutherford | 0.00
-16.00 | Antonio | Fahey | Considine | 0.00
 10.00 | Esther | Spencer | Lakin | 0.00
 12.00 | Carmen | Streich | Hirthe | 0.00
+13.00 | Alfredo | Stiedemann | Morissette | 0.00
+14.00 | Manolo | Hamill | Kozey | 11.00
+15.00 | Alejandro | Kohler | Schoen | 0.00
+16.00 | Antonio | Fahey | Considine | 0.00
 17.00 | Guillermo | Ruecker | Upton | 0.00
 18.00 | Micaela | Monahan | Murray | 0.00
-13.00 | Alfredo | Stiedemann | Morissette | 0.00
 20.00 | Francesca | Schowalter | Muller | 0.00
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 26: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,11 @@
 apellido1 | apellido2 | nombre
 Schmidt | Fisher | David
-Kohler | Schoen | Alejandro
 Lemke | Rutherford | Cristina
-Fahey | Considine | Antonio
 Spencer | Lakin | Esther
 Streich | Hirthe | Carmen
+Stiedemann | Morissette | Alfredo
+Kohler | Schoen | Alejandro
+Fahey | Considine | Antonio
 Ruecker | Upton | Guillermo
 Monahan | Murray | Micaela
-Stiedemann | Morissette | Alfredo
 Schowalter | Muller | Francesca
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---
