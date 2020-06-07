# Diplomatura en Ciencia de Datos, Aprendizaje Automático y sus Aplicaciones 2020 

## Mentoría: Coronavirus en Argentina y el mundo

### A cargo de María Lucía Pappaterra

A través de este repositorio se publicarán los prácticos y se realizarán las entregas de los mismos.

------------------------------------------------------------------------------------------------------

Trabajaremos con la base de datos disponible en: 

https://github.com/lucia15/Datos-Covid19-Argentina

(y posiblemente con datos internacionales agregados de alguna otra),

nos proponemos trabajar las 5 tareas descriptas a continuación.

# Práctico 1: Análisis y Visualización

### Objetivos: 
Uso de estadísticas descriptivas para el análisis del set de datos. 
Responder a distintas preguntas generales respecto al dataset, por ejemplo:

+ Cantidad de infectados (nuevos y totales, recuperados, fallecidos) por región (país o provincia) por día
+ Proporción de casos importados, locales y comunitarios en Argentina
+ Cantidad de testeos cada 100 mil habitantes, proporción positivos/negativos, negativos acumulados
+ Diferencia entre las distintas provincias en el caso de Argentina

Determinar la tasa de ocurrencia de algún fenómeno, por ejemplo:

+ Tasas de contagio, testeo, mortalidad, hospitalización, recuperación
+ Tasa de mortalidad por país y por provincia (Argentina)

Señalar si existe correlación entre dos o más variables, por ejemplo:
+ Entre mortalidad y distintas comorbilidades

Estudiar la distribución de alguna variable de interés, por ejemplo:
+ Distribución etaria de los infectados y fallecidos
+ Clasificación por género y posibles diferencias del impacto del virus en cada uno

# Práctico 2: Análisis y Curación

### Objetivos: 

Procesar el conjunto de datos para poder utilizarlos en el análisis exploratorio de los mismos. Tener en cuenta:

+ Datos faltantes, datos nulos, ¿los eliminamos? ¿nos dicen algo? ¿podemos completarlos?
+ Consistencia de los datos, ¿existe información contradictoria? ¿Qué hacemos si la hay?
+ Outliers, ¿tenemos?, ¿cómo los tratamos? 
+ Indagar en la forma en que está presentada la información, ¿podríamos re organizarla de otra manera?
+ Considerar la posibilidad de crear nuevas variables (columnas) en base a las ya disponibles 
(o quizás incorporando otra información). 
Esto puede ser útil para algún análisis que nos propongamos hacer a futuro.


Puesto que este dataset fue creado y es mantenido por una sola persona, 
algunos de los incisos anteriores están orientados a mejorar la consistencia y calidad del mismo. 
Una buena idea puede ser compararlo con otros dataset similares.


# Práctico 3: Introducción al Machine Learning

### Objetivos:
Nos proponemos utilizar algunos algoritmos básicos de aprendizaje automático para intentar encontrar patrones en los datos, y evaluar los resultados usando métricas estándares para cada tipo de problema.

El objetivo es que pensemos en las distintas formas que puede tomar el modelado de un problema con datos, y en el trabajo de selección de features que debe realizarse para poder abordarlo.

Para ello intentaremos responder la siguiente pregunta:

¿Es posible predecir la cantidad de infectados que tendrá una región (país o provincia) en base a los datos que se 
encuentran presentes en este dataset?

Una forma de hacer esto puede ser estimar el R0 (número básico de reproducción de una epidemia) o el Rt (número de reproducción efectivo).

El número básico de reproducción de una epidemia R0 es la tasa de reproducción del virus. 
Se define como el número de infecciones secundarias producidas por una sola infección. 
Si R0 es mayor que 1, la epidemia se propaga rápidamente. Si R0 es menor que 1, 
la epidemia se propaga, pero lentamente y desaparece antes de que todos se infecten. 

Mientras que R0 es un valor estático, el número de reproducción efectivo Rt es 
el número promedio de personas que infectará una persona infectada en el momento t.


Al probar modelos de Machine Learning tener en cuenta los siguientes lineamientos: 

+ Deben decidir a partir de qué valor de una métrica determinada consideran aceptable el resultado. Esto lo tienen que hacer antes de empezar a entrenar un modelo.
+ Deberán trabajar con el problema de dos maneras diferentes: como un problema de regresión, y como un problema de clasificación.
+ A la hora de hacer selección de variables, tengan en cuenta que los modelos de Machine Learning solo reciben inputs numéricos.
+ Es importante que almacenen los resultados de alguna manera para poder comparar los distintos modelos. Recomendación: crear una función para almacenar resultados en un dataframe de pandas e imprimirlos en pantalla

# Práctico 4: Aprendizaje Supervisado

### Objetivos:

Profundizar el trabajo realizado en el práctico anterior. Intentaremos mejorar los resultados iterando sobre la ingeniería de atributos, el modelado, y el análisis de la salida de los modelos.

# Práctico 5: Aprendizaje No Supervisado

### Objetivos:
Realizar un k-means clustering para clasificar los países (o regiones) según alguna(s) variable(s) de interés.
