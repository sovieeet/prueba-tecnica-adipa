# Caso práctico: Análisis de rendimiento de búsquedas en un sitio web

Este repositorio consiste en el desarrollo de la [prueba técnica](prueba_tecnica.ipynb), el cuál el desarrollo se encuentra [aquí](desarrollo.ipynb).

Para empezar a desarrollar la prueba, primero hay que preparar el ambiente. Para este caso se hicieron los siguientes pasos de manera local:

1. Se creó un ambiente virtual de Python con la versión 3.9.13 y se procedió a activarlo.
2. Se instalaron las librerías a usar indicadas un poco más abajo.
3. Se creó un nuevo notebook Jupyter para el desarrollo.
4. Se creó una carpeta llamada `datasets` y se movió el archivo `df_tecnical_test.csv` ahí para más orden dentro del repositorio.

El desarrollo consiste primero en convertir el csv a dataframe, realizar una exploración de los datos, luego una limpieza (eliminar nulos, duplicados, etc.), luego optimizar los tipos de datos y normalización de la columna query (los términos de busqueda), para luego resolver las preguntas basada en los datos del dataframe usando gráficos para generar insights y recomendaciones en base a los datos para la toma de decisiones (data driven).

Para el desarrollo de la prueba técnica, se usó en Jupyter, con la librerías `pandas` y `unidecode` para la creación y transformación correspondiente de los datos, mientras que `matplotlib` y `seaborn` se usa para los gráficos de los datos.

Todo el código del desarrollo **se encuentra documentado**, además, dentro del archivo se encuentran las respuestas, insights y recomendaciones de los datos.

Este código se encuentra subido también en Github de manera privada usando las buenas prácticas de Gitflow. El link corresponde al [siguiente][repo].

[repo]: https://github.com/sovieeet/prueba-tecnica-adipa

Personalmente me gustaría destacar dos cosas:

- Al recibir la prueba tecnica en formato `.zip`, estaba presente el archivo `__MACOSX`, lo que es un archivo innecesario e indica que la prueba se realizó desde un dispositivo MAC.

- Si bien es bueno simular casos reales en las pruebas técnicas, encuentro que el `df_tecnical_test.csv` posee muchos datos para una prueba técnica, además de pesar bastante (425 MB aproximadamente).