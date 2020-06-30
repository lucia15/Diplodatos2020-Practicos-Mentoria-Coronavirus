
# Práctico 2: Análisis y Curación

### Objetivos: 

Curar el conjunto de datos para poder utilizarlos en próximos análisis. Tener en cuenta:

+ Datos faltantes, datos nulos, ¿los eliminamos? ¿nos dicen algo? ¿podemos completarlos?
+ Consistencia de los datos, ¿existe información contradictoria? ¿Qué hacemos si la hay?
+ Outliers, ¿tenemos?, ¿cómo los tratamos? 
+ Indagar en la forma en que está presentada la información, ¿podríamos re organizarla de otra manera?
+ Considerar la posibilidad de crear nuevas variables (columnas) en base a las ya disponibles 
(o quizás incorporando otra información). 
Esto puede ser útil para algún análisis que nos propongamos hacer a futuro.


Puesto que este dataset fue creado y es mantenido por una sola persona, 
algunos de los incisos anteriores están orientados a mejorar la consistencia y calidad del mismo. 
Una buena idea puede ser compararlo con otros dataset similares, 
por ejemplo: https://github.com/SistemasMapache/Covid19arData


### Tareas a realizar:

* Detectar al menos **tres** variables con valores faltantes no triviales. Decidir si eliminarlos o computarlos,
investigar los métodos disponibles en pandas para dichos fines.

* Detectar al menos **cinco** inconsistencias en los datos, discutir a qué se deben y si podemos solucionarlas.
 
* Elegir al menos **una** variable que tenga outliers, debatir y decidir qué hacer con los mismos.

* Bonus (solo si tienen ganas y tiempo): Debatir: 
¿Hay variables que son redundantes o solo agregan ruido? ¿Las eliminarían? 
¿Agregarían otras variables que puedan ser de utilidad? ¿Pueden generar nuevas variables a partir de las existentes? 
Por ejemplo, transformando, escalando o combinando variables existentes. 
Contrastar con otras fuentes (otros datasets, reportes provinciales, prensa) si la información es correcta.
Comparar el dataset con otros similares, ¿cuáles son las semejanzas y diferencias? ¿consideran las mismas variables o equivalentes? 
¿hay información contradictoria?... O cualquier otro interrogante que les surja en torno a estos datos.

### Entregas:

+ Un **brevísimo informe** (entre una y dos páginas) en el cual expliquen con sus palabras qué encontraron, 
cómo interpretaron y qué soluciones proponen y/o aplicaron. 
Pueden agregar con total sinceridad las observaciones que tengan sobre la consistencia y calidad de los datos, 
comparación con otros datasets, etc. (me sería de gran ayuda!)

+ El o los **data sets modificados** con los cambios propuestos (limpios y curados).

+ Una **notebook** (o **script**) que refleje el trabajo realizado. 
No les voy a corregir el código en detalle, es para tener una idea de cómo fue el proceso.