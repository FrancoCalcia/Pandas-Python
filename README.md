# Proyecto de Análisis de Datos Meteorológicos con Pandas y Matplotlib
Este proyecto de análisis de datos meteorológicos utiliza Python y se basa en las bibliotecas Pandas para el análisis de datos y Matplotlib para la visualización de gráficos. A continuación, se presenta una descripción general del proyecto

## Objetivo:
El objetivo principal de este proyecto es realizar un análisis exhaustivo de los datos meteorológicos proporcionados, centrándose en variables como la temperatura, humedad, velocidad del viento, entre otras, a lo largo de diferentes estaciones y meses.

## Contenido del Proyecto:
*Carga de Datos:*
- Descarga del archivo ServiciosMeteorologicos.CSV desde Google Drive utilizando la biblioteca gdown.
- Lectura del archivo CSV con Pandas.

*Limpieza de Datos:*
- Renombrado de columnas para mayor consistencia (Estaci—n a Estación).
- Limpieza de caracteres no legibles en las columnas relevantes.
- Conversión de las columnas de meses a formato numérico.

*Análisis Descriptivo:*
- Cálculo de estadísticas descriptivas para la temperatura promedio y la humedad relativa.

*Visualización con Boxplot:*
- Visualización de la distribución de temperaturas y humedad relativa en enero mediante boxplots.

*Top 10 de Temperaturas Mínimas y Máximas:*
- Identificación y visualización de las estaciones con las temperaturas más bajas y más altas en julio y enero, respectivamente.

*Top 10 de Estaciones con Mayores Vientos:*
- Identificación y visualización de las estaciones con mayores velocidades de viento para cada mes.

*Análisis Temporal con Gráfico de Líneas:*
- Representación gráfica de la variación de temperaturas máximas, promedio y mínimas a lo largo de todos los meses.

*Preguntas de Investigación:*
- Respuestas a preguntas específicas, como la estación con menor frecuencia de días con precipitación, el mes con mayor nubosidad total y el mes con menor velocidad del viento.

## Requisitos:
1. La biblioteca gdown para descargar el archivo CSV.
1. Las bibliotecas pandas y matplotlib para el análisis de datos y la visualización de gráficos, respectivamente.

## Uso:
El código proporcionado puede ejecutarse secuencialmente en un entorno de Python y se debe ajustar según las necesidades específicas del usuario. Además, se pueden agregar más preguntas de investigación o análisis en función de los datos disponibles.

Este proyecto proporciona una visión detallada del clima a lo largo del tiempo y puede servir como base para investigaciones más profundas o para la toma de decisiones informada, como por ejemplo, en campos relacionados con la meteorología.
