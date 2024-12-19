# Factores demográficos en el síndrome metabólico


El síndrome metabólico (SM) hace referencia al conjunto de alteraciones metabólicas formado por la obesidad de distribución central, disminución de la concentración de colesterol unido a lipoproteínas de alta densidad (HDL), aumento de la concentración de triglicéridos, hiperglucemia y aumento de la presión arterial. 

------

En este repositorio, recogemos todo el proceso de análisis exploratorio de los datos pertenecientes a un dataset con 2401 entradas y 15 columnas, obtenido en Kaggle. Esta tabla recoge variables demográficas y valores de indicadores sanguíneos y de orina. 

Utilizando la librería Pandas de Python vamos a convertir el dataset en un DataFrame para trabajarlo:
- Reorganizando las columnas
- Limpiando valores nulos
- Eliminando outliers o columnas que no son de nuestro interés


Una vez terminado esta limpieza y transformación del dataset, pasamos a realizar un análisis estadístico de las variables:


#### Análisis univariante
Realizamos un estudio de las medidas de tendencia central en todas las variables:
-	Obtenemos la distribución de las variables categóricas como frecuencia relativa y su moda.
-	Observamos la distribución de las variables numéricas mediante histogramas y diagramas de cajas y bigotes. Además, obtenemos media, mediana, percentiles mínimos y máximos.


#### Análisis bivariante
Cruzamos las variables para ver si encontramos relaciones entre unas y otras, centrándonos principalmente en las variables demográficas. Profundizamos principalmente en los ingresos, el estado civil y la etnia de los diferentes sujetos, para ver cómo se relacionan entre sí y cómo se relacionan con el diagnóstico o no de síndrome metabólico.

------

Todo el proceso está desarrollado en el archivo EDA_main, que a su vez se encuentra dividido en partes en la ruta src/notebooks.
