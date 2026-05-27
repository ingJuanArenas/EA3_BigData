EA3. procesamiento de datos en infraestructura cloud usando **Databricks Free Edition** y **Apache Spark**. Se trabajó con el dataset *THE World University Rankings 2016–2026* descargado de Kaggle, cargado en DBFS/Volumes y procesado con PySpark y Spark SQL.

---

## Dataset

| Campo | Detalle |
|---|---|
| Nombre | THE World University Rankings 2016–2026 |
| Filas | 16,713 |
| Columnas | 14 |
| Años cubiertos | 2016 – 2026 |
| Formato | CSV |

---

## Contenido del notebook

| Sección | Descripción |
|---|---|
| Diseño del esquema | Diccionario de datos, DDL Spark SQL y diagrama del esquema |
| Configuración Databricks | Versión Spark 4.1, Python 3.11 |
| Ingesta del dataset | Carga desde Volumes con esquema definido, persistencia como tabla Delta |
| Validaciones Spark | `printSchema`, `describe`, `COUNT`, nulos, `GROUP BY`, filtros |
| Validaciones SQL | `DESCRIBE TABLE`, `SELECT`, `GROUP BY`, `LIMIT`, filtros equivalentes |
| SQL vs PySpark | Tabla comparativa con ventajas y desventajas basadas en la práctica |

---

## Tecnologías

- Databricks Free Edition
- Apache Spark 4.1
- Python 3.11
- PySpark
- Spark SQL
- Delta Lake
- Kaggle

---
