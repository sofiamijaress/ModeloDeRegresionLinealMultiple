# ModeloDeRegresionLinealMultiple
Este proyecto corresponde al propósito de aplicar la regresión lineal múltiple en un caso real de ingeniería, se utilizaron los datos de 1503 observaciones, cada una con 6 mediciones respectivamente, obtenidas de [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/291/airfoil+self+noise); originalmente publicados por [NASA Reference Publication 1218](https://ntrs.nasa.gov/api/citations/19890016302/downloads/19890016302.pdf).


El archivo a analizar posee seis variables: frecuencia, ángulo, longitud de cuerda geométrica, velocidad de flujo libre, espesor y nivel de presión sonora.
La variable dependiente que se busca predecir es la presión sonora, mientras que las demás actúan como predictores.

La metodología del proyecto se desarrolló en seis etapas principales.

Primero se importaron y exploraron los datos para verificar su integridad. Después, el conjunto se dividió aleatoriamente en 70% entrenamiento y 30% prueba, garantizando una evaluación sin sesgos. En la tercera etapa se entrenó un modelo de regresión lineal múltiple, obteniendo coeficientes, errores estándar, p-values y R².

Posteriormente se analizaron los resultados para identificar las variables significativas (p-value < 0.05) y señalar la más importante según su estadístico t. En la quinta etapa se calcularon métricas de desempeño, RSE y R², tanto en entrenamiento como en prueba. Finalmente, se elaboró una gráfica de dispersión de valores reales contra predichos, junto con la línea y = x, lo que permitió valorar visualmente la calidad del modelo.

Este proyecto incluye los siguientes documentos:
* [Reporte en formato ipynb](645700(3).ipynb)
* [Reporte en formato html](645700(3).html)
* [Base de datos](NASA.csv)
