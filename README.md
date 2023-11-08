# Proyecto de Análisis de Datos sobre Servicios de Internet Fijo en Argentina

## Introducción
Este proyecto tiene como objetivo realizar un análisis exhaustivo de los datos relacionados con los servicios de Internet fijo en Argentina. Los datos se obtuvieron de diversas fuentes y se sometieron a un proceso de Extracción, Transformación y Carga (ETL) antes de llevar a cabo el Análisis Exploratorio de Datos (EDA).

## ETL - Extracción, Transformación y Carga
- Se extrajeron datos de múltiples archivos CSV que contenían información sobre ingresos, accesos, velocidad de bajada y penetración de Internet.
- Se realizaron operaciones de limpieza y transformación en los datos para eliminar caracteres no deseados, convertir tipos de datos y abordar valores nulos.
- Los datos resultantes se almacenaron en nuevos archivos CSV para su posterior análisis.

## Análisis Exploratorio de Datos (EDA)
El EDA incluyó las siguientes actividades:

1. **Exploración Básica de Datos:** Se realizó una exploración inicial de los datos, verificando la estructura y la presencia de valores faltantes.

2. **Análisis de Métricas Relevantes:** Se crearon visualizaciones y gráficos para analizar valores atípicos en los ingresos, la distribución de accesos por tecnología y la velocidad media de bajada por provincia.

3. **Cálculo de Key Performance Indicators (KPIs):** Se calcularon KPIs relacionados con el acceso, velocidad y penetración de Internet para evaluar el rendimiento y los cambios a lo largo del tiempo.

## Conclusiones y Recomendaciones
- Se observó un aumento en el acceso a Internet en la mayoría de las provincias, destacando Catamarca y Chubut.
- La velocidad media de bajada se mantuvo estable a lo largo de los años, con algunas fluctuaciones.
- Las 5 provincias con la mayor penetración de Internet mostraron un KPI de 85.03, lo que sugiere un alto nivel de acceso.

## Datos y Referencias
- Todos los datos utilizados en este análisis se almacenan en archivos CSV disponibles en la carpeta "data/output".
- Se utilizó la biblioteca `pandas` para la manipulación de datos y `seaborn` para la visualización.
- Las conclusiones se basan en el análisis de los datos disponibles y pueden requerir un análisis más profundo.

## Pasos Futuros
- Este análisis puede servir como punto de partida para evaluar tendencias a lo largo de los años y explorar relaciones más complejas entre variables.
- Se pueden realizar análisis adicionales para profundizar en aspectos específicos, como la correlación entre ingresos y velocidad de bajada.

**Luis Octavio Varas Jaime -**
**[Linkedin](#https://www.linkedin.com/in/luis-o-varas/)**