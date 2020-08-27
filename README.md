# Examen Entropia

### Datos
La base de datos corresponde a las quejas de usuarios de productos financieros. Para cada tipo de producto
(crédito hipotecario; crédito de consumo; tarjeta de crédito, etc) existe una en texto que describe la queja.
La base de datos incluye los siguientes campos: 1) Fecha; 2) Producto; 3) Subproducto; 4) Problema; 5)
Sub-problema; 6) Texto de la queja; 4) Acción tomada por el banco/empresa; 5) Nombre de la compañía; 6)
Estado; 7) Código Postal.

## Archivos
* prueba.ipynb: Jupyter Notebook no ejecutada completamente
* prueba-ejecutada.ipynb: Jupyter Notebook ejecutada completamente
* Consumer_Complaints.csv: Datos

### Preguntas
a. Presenta una o varias estadísticas descriptivas que den una idea de cómo se comportan
los datos (en el tiempo, en el espacio, en ambas dimensiones; por nombre del banco, tipo de
queja, etc.) Las estadísticas deben acompañarse por una breve explicación que les dé sentido.
b. Como parte de la pregunta anterior, o en adición, crea una o varias visualizaciones que
pienses que es importante para entender la base de datos. Sé selectiv@, de modo que tu(s)
visualizacion(es) cuenten una historia con los datos. Puedes usar visualizaciones dinámicas
(plotly, bokeh, etc.) o estáticas (matplotlib, seaborn, plotnine etc.)

c. Utilizando un algoritmo de “edit-distance” o alguno otro que consideres pertinente, nor-
maliza los nombres de los bancos y genera un gráfico de barras que muestre la frecuencia de

quejas por banco.
d. ¿De qué temas hablan las quejas?
e. Desarrolla un modelo de aprendizaje no supervisado para entender una dimensión de los
datos en la que son claramente clusterizables.
f. Desarrolla un modelo de machine learning que prediga el tipo de producto con base en el
texto. Puedes usar la técnica que desees, pero debes explicar qué métricas de evaluación usas
para determinar tu elección del modelo.