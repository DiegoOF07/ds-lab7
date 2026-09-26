# Laboratorio 7

Análisis de salarios de asalariados con las bases de **Personas** de la ENEIC (INE Guatemala), usando PySpark 3.5 y `pyspark.ml`.

## Estructura

```
dockerfile, docker-compose.yml     Ambiente del curso (+ openpyxl para leer .xlsx)
notebooks/
  01_carga_calidad.ipynb           Punto 1: carga, armonización, calidad, filtros, Parquet
  02_eda_segmentacion.ipynb        Puntos 2-4: descriptivos, correlaciones, KMeans
  03_regresion_lineal.ipynb        Punto 5: pipeline de regresión lineal y regularización
  04_random_forest.ipynb           Punto 6: pipeline de Random Forest y comparación
working_dir/eneic/                 Bases .xlsx y diccionarios del INE
working_dir/eneic_parquet/         Salidas generadas por los notebooks (Parquet, CSV y modelos/)
```