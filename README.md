# **Proyecto: Análisis de Homicidios y Mortalidad en Siniestros Viales**

## **Descripción del Proyecto**
Este proyecto tiene como objetivo analizar los datos de homicidios y mortalidad en siniestros viales en la Ciudad de Buenos Aires (CABA) entre los años 2016 y 2021. El análisis se centra en identificar tendencias en los tipos de víctimas, los medios de transporte involucrados, y los cambios en las tasas de homicidios en distintos periodos de tiempo.

## **Estructura de los Datos**
**Dataset de Homicidios**

Nombre del archivo: homicidios.xlsx
Descripción: Este dataset contiene información sobre los homicidios en siniestros viales ocurridos en CABA. Cada fila representa un incidente con información sobre la fecha, tipo de víctima y número de víctimas, comunas de Buenos Aires. Es utilizado para calcular las tasas de mortalidad por semestre y año.
Columna	Descripción
Año/Comuna	Año y comuna de los datos de población
N_VICTIMAS	Número de víctimas en el incidente
VICTIMA	Tipo de víctima involucrada (auto, bicicleta, peatón, etc.)
Período cubierto: 2016 - 2021
Dataset de Mortalidad

Nombre del archivo: mortalidad.xlsx
Descripción: Este dataset contiene información demográfica y de mortalidad. Es utilizado para porcentajes de mortalidad por semestre y año.
Columna	Descripción
FECHA	Fecha del siniestro vial
EDAD   Edades de las víctimas
GENERO Masculino y femenino
FECHA DE FALLECIMIENTO
ROL  Desempeño de la vìctima en el siniestro

## **Metodología**
El análisis del proyecto incluye las siguientes etapas:

1. Análisis temporal por semestre
Objetivo: Analizar las tasas de homicidios en siniestros viales comparando el primer y segundo semestre del año 2019.
**KPI 1**
Cálculo de tasas: Se calcula la tasa de homicidios por cada 100,000 habitantes 
División temporal: Se dividieron los datos de homicidios en dos semestres:
Primer semestre: 1 de enero - 30 de junio de 2019
Segundo semestre: 1 de julio - 31 de diciembre de 2019

1. Comparación de la tasa de homicidios por semestre 
Tasa del primer semestre (2019): Se calculó la tasa de homicidios en el primer semestre y luego se comparó con la tasa del segundo semestre para evaluar si hubo una reducción del 10% o más.
Población semestral: Se utilizó la población de CABA en 2019 y se dividió en dos semestres para normalizar los datos.

**KPI 2**
Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año 2019, en CABA, respecto al año anterior 2018.

**KPI 3**
Reducir en un 15% la cantidad de accidentes mortales de peatones en el último año 2019, en CABA, respecto al año anterior 2018.

## **Resultados Clave**
Reducción de la Tasa de Homicidios (2019): El análisis reveló una reducción significativa de más del 10% en la tasa de homicidios en siniestros viales entre el primer y segundo semestre de 2019.
Distribución de víctimas por tipo de transporte: Los motociclistas y peatones representan la mayor proporción de víctimas en los siniestros viales.

**Recomendaciones al Gobierno de Buenos Aires**
A partir del análisis de los datos de homicidios y mortalidad, se recomiendan las siguientes medidas para reducir los siniestros viales en Buenos Aires:

**Educación y concientización vial:** Implementar campañas masivas de educación vial y concientización, dirigidas tanto a conductores como a peatones.
Mejora en la infraestructura vial: Identificar las zonas de alta siniestralidad y realizar mejoras en la señalización, iluminación y diseño de las vías.
Refuerzo en los controles de tránsito: Incrementar los controles de velocidad y pruebas de alcoholemia, sobre todo en áreas y horarios con alta incidencia de accidentes.
Protección de grupos vulnerables: Implementar medidas específicas para proteger a motociclistas y peatones, como carriles exclusivos y más infraestructura de seguridad.
Monitoreo de datos en tiempo real: Utilizar tecnología avanzada y análisis de datos en tiempo real para prevenir siniestros antes de que ocurran.

**Tecnologías Utilizadas**
Python: Para ETL, EDA, cálculo de tasas y porcentajes.
Pandas: Para la manipulación y filtrado de los datasets.
Power BI / DAX: Para la visualización de datos y cálculos adicionales (KPIs).

Visualización de datos: Se crearon gráficos de barras para visualizar las tendencias de las tasas de homicidios y la distribución de víctimas por tipo de transporte.
Cómo Usar los Archivos

**Clonar el repositorio:**

bash
Copiar código
git clone https://github.com/CaroVallejo/Proyecto2analisisdedatos.git
Instalar dependencias: Si utilizas Python, instala las dependencias necesarias:

bash
Copiar código
pip install pandas matplotlib
Cargar los archivos XLSX: Carga los archivos homicidios.csv y mortalidad.csv y asegúrate de que estén en el mismo directorio que el código Python o cargados en la plataforma de BI.

Ejecutar el análisis: Sigue los scripts proporcionados en el archivo análisis.py o el reporte en Power BI para obtener los resultados.

Licencia
Este proyecto está licenciado bajo la MIT License.

