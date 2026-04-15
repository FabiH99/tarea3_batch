Procesamiento Batch con PySpark - Tickets

Descripción
En este trabajo lo que hice fue procesar un archivo de datos usando PySpark. 
El archivo contiene información de tickets de mesa de ayuda. Básicamente cargué 
el archivo, revisé los datos y saqué algunos resultados como el total de registros 
y cuántos tickets hay por cada categoría.

Fuente de datos
Los datos los descargué de la página de datos abiertos de Colombia:
https://www.datos.gov.co/

El archivo utilizado es:
tickets.csv

Tecnologías utilizadas
- Apache Spark
- Python (PySpark)
- Máquina virtual con Ubuntu

Ejecución

1. Descargar el archivo:
wget -O tickets.csv "https://www.datos.gov.co/resource/iupi-ay2g.csv"

2. Ejecutar el programa:
spark-submit spark_batch.py

Resultados obtenidos
Cuando se ejecuta el programa se puede ver:
- Los primeros registros del archivo
- Las columnas del dataset
- El total de registros (aprox 1000)
- La cantidad de tickets por categoría

Observación
Este trabajo es batch porque los datos se procesan todos de una sola vez, 
no en tiempo real.
