MetroBus Analytics — TFM Máster en Data & Analytics

Proyecto de Trabajo de Fin de Máster (thePower Business School) centrado en el análisis de datos operativos de MetroBus, una operadora urbana de transporte público (dataset ficticio construido para el proyecto).

Objetivo del proyecto

Aplicar un flujo completo de analítica de datos —desde la exploración inicial hasta la visualización final— sobre un conjunto de datos operativos de transporte público, con el fin de aportar información útil para la toma de decisiones (rendimiento de líneas, incidencias, mantenimiento de flota, etc.).

Dataset

El proyecto parte de 9 archivos CSV organizados en un modelo dimensional (esquema en estrella):

Tablas de hechos

fact_viajes — expediciones realizadas
fact_incidencias — eventos de incidencias en el servicio
fact_mantenimiento — eventos de mantenimiento de vehículos

Tablas de dimensiones

dim_linea, dim_vehiculo, dim_conductor, dim_parada, dim_tarifa, dim_depot
Fases del proyecto
Fase	Descripción	Estado
1. EDA	Exploración inicial, estructura y calidad de los datos	✅
2. Limpieza y transformación	Tratamiento de nulos, duplicados y outliers	🔄
3. ETL	Pipeline de carga y transformación	⏳
4. Dashboard	Visualización en Power BI	⏳
Estructura del repositorio
metrobus-analytics-tfm/
├── 01_eda.ipynb        # Fase 1: Exploración y Análisis de Datos
├── data/                # (opcional) CSVs del dataset
└── README.md
Herramientas utilizadas

Python (pandas, numpy, matplotlib, seaborn) · SQL · Power BI

Autor

Manuel Barrachina — LinkedIn
