
# Práctico 5: Aprendizaje No Supervisado

### Objetivos: 

Realizar un k-means clustering para clasificar los países (o regiones) según alguna(s) variable(s) de interés.

### Consigna:

En la notebook tienen un ejemplo de k-means clustering para series de tiempo utilizando la variable *casos_nuevos* de cada provincia. 
Revisen el modelo propuesto y luego discutan/ debatan/ respondan/ propongan:

 + ¿Qué número de clusters k les parece más conveniente utilizar y por qué? 
 + Correr el modelo con ese valor de k.
 + Interpretar los resultados (clusters) obtenidos, 
 ¿tienen sentido con lo que sabemos de la realidad o lo que nos dice la intuición al revisar los datos?
 + Probar el modelo para distintos valores de: 
    - la variable (*casos_total*, *casos_nuevos*, *muertes_total* y *muertes_nuevos*) 
    - la distancia (*DTW*, *soft-DTW*, ...)
 Tener en cuenta en cada caso cuál sería el k óptimo.
 Quizás sea conveniente tener las variables por cada millón de habitantes en cada provincia (quizás el modelo mejora, prueben!!).
 La idea es encontrar el modelo que produzca la mejor agrupación posible de provincias. 
 + ¿Qué otros modelos de aprendizaje no supervisado se podrían utilizar con este tipo de datos? 
 Si se animan propongan otro y si se animan aún más lo prueban 
 (si llegan, sino todo bien, la idea es aunque sea pensarlo y debatirlo).
 
### Entregables:
 
 Breve informe y/o Notebook (lo que les resulte más cómodo) con lo que hicieron/ propusieron/ encontraron/ les pareció interesante.
 Hasta donde lleguen!