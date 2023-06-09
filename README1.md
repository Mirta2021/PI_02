

#                       PROYECTO INDIVIDUAL 
#                       ACCIDENTES AEREOS
# Introduccion y Objetivos:

Se nos encomendo el análisis de datos históricos de accidentes para mejorar la seguridad de la aviación: 
"La recopilación y el análisis sistemático de los datos de accidentes nos pueden ayudar a identificar patrones, tendencias y factores contribuyentes que podrían llevar a mejoras en la seguridad, desde ayudar a mejorar la capacitación de los pilotos y el personal de mantenimiento, así como a mejorar el diseño y la fabricación de aviones y equipos de aviación".

# Tareas desarrolladas:

- ETL : Extraccion y limpieza de la Base de Datos que se recibio
- Realizacion del EDA: Analisis Exploratorio de Datos
- Dashboard con Power BI

   
# ETL y Tareas realizadas:
En la Base de Datos entregada se realizaron las siguientes tareas:
-eliminacion de las columnas que no servian a nuestro proposito
-acomodamiento de la fecha 
-reemplazo de '?' por nulos 
-eliminacion de registros que tampoco sirven

# EDA

Del analisis de los diferentes graficos realizados con variedad de librerias y codigo python se pueden sacar algunas conclusiones:
-la columna summary no nos aporta informacion de importancia aun asi dado que estan las causas de los accidentes se opto por mantenerla.
-Hay claramente rutas que tienen mas accidentes que otras, (tambien se puede deber al transito aereo que circula a traves de ellas).
-El tipo de aparato tambien tuvo su influencia aunque esto fue en una epoca muy anterior a la actual.
- Se encontraron outliers muy definidos: 2da guerra mundial y el atentado a las torres gemelas
-Las victimas en tierra no fueron cuantitativamente importantes a la hora del analisis (salvo 2001).

# DASHBOARD

La realizacion del mismo ratifica plenamente lo dicho en el punto anterior por lo cual  se hicieron los graficos logicos para una segunda visualizacion, esta vez en forma interactiva y se incluyo un mapa con lugares donde hubo accidentes y la cantidad de victimas en ese lugar
KPI's:
KPI 1: Tasa de mortalidad: Número de muertes a bordo/Número total de personal a bordo
Tasa Objetivo: Reducción del 5% anualmente
KPI 2: Tasa de mortalidad en tierra (ground)/ año 
Tasa Objetivo: Reduccion de un 5% anual 
KPI 3: Tasa de accidentes fatales por ruta: Numero de accidentes en las rutas mas usadas/año
Tasa objetivo: Tasa de accidentes fatales por debajo del 5% anualmente en una determinada ruta
KPI 4: Tasa de siniestralidad:Accidentes anuales por millon de vuelos 
Tasa objetivo:fijada por la IATA , 2% anual

Los valores fijados de tasa objetivo fueron elegidos en base a estadisticas de las diferentes asociaciones de aviacion existentes, teniendo en cuenta las variables que intervienen en los mismos y el analisis de la historia ocurrida.

# RECOMENDACION:

La informacion que nos fue entregada claramente nos muestra que no alcanza para hacer un analisis mas exhaustivo, por ejemplo hubiera sido deseable contar con informacion climatica, super importante a la hora de analizar los accidentes aereos, y tambien evaluar datos de mantenimiento preventivo realizados en los aparatos, por ejemplo: perioricidad, infraestructura para hacer innovaciones mecanicas, etc , etc

# OBSERVACIONES: 

En el desarrollo del modelo se encontraron problemas de recursos que en su mayoria pudieron ser subsanados al utilizar el Power BI.

# Nota final:
Al realizar este proyecto conte aqui con la ayuda invalorable como siempre de mis queridos compañeros de curso, en especial : Ariel, Karla  y Angel. Es un placer trabajar con ellos como siempre

Se incluiran en la DEMO charts realizados en Power Point que me ayudaran a hacer el comienzo y el final de la presentacion

# Links
https://www.iata.org/contentassets/a9da312b27a446efa65a12ebccd48996/2023-03-07-01-sp.pdf



