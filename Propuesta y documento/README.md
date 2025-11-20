# Propuesta inicial para el proyecto
En esta carpeta se encuentra un documento .pdf que explica nuestra propuesta, así como también una carpeta data que contine el archivo *query.csv* inicial descargado desde USGS y el archivo *query_limpio.csv* creado en el notebook *limpieza_de_datos*, luego está la carpeta *Preguntas* que contiene nobooks respondeinedo cada una de las preguntas objetivo de nuestro proyecto

Librerías necesarias para ejecutar los notebooks:
-pandas
-pathlib
-os
-geopandas
-matplotlib
-seaborne
-numpy
-plotly 
-sklearn

Flujo adecuado para visualizar los notebooks:
1. Ejecutar el notebook *Limpieza_de_datos* para revisar, ordenar y almacenar la información de un modo más adecuado.
2. Ejecutar el notebook en Regresion lineal para visualizar los datos a partir de una regresion lineal.
3. Acceder a la carpeta Preguntas y ejecutar los notebooks
4. Ejecutar el notebook *pregunta_1* para conocer la información que registramos en nuestro archivo.
5. Ejecutar el notebook *pregunta_2* para visualizar los mayores terremotos por región.
6. Ejecutar el notebook *pregunta_3* para encontrar el area de mayor riesgo en el país.
7. Ejecutar el notebook *pregunta_4* para calcular el tiempo promedio en que ocurren los terremotos
8. Ejecutar el notebook *pregunta_5* para generar el modelo predictivo de lugares de riesgo
