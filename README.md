#  CallMeMaybe-Operator-Analysis
Identificar operadores ineficaces en el servicio de telefonía virtual CallMeMaybe mediante el análisis de datos de llamadas.

Identifying inefficient operators in the CallMeMaybe virtual phone service through call data analysis.

## Contexto del Proyecto / Project Context
El objetivo de este proyecto es identificar a los operadores ineficaces en el servicio de telefonía virtual CallMeMaybe, basado en varios indicadores de rendimiento. Se considera que un operador es ineficaz si tiene una gran cantidad de llamadas perdidas, tiempos de espera largos para las llamadas entrantes, y un bajo número de llamadas salientes realizadas. Este análisis permite a los supervisores del servicio tomar decisiones informadas para mejorar la eficiencia y la calidad del servicio al cliente.

El análisis abarca varias fases: un análisis exploratorio de datos (EDA) para comprender el comportamiento de las llamadas, seguido por la identificación de operadores ineficaces usando métricas clave, y la prueba de hipótesis estadísticas para validar los hallazgos. La información extraída de este análisis puede ser utilizada para optimizar el rendimiento de los operadores y mejorar la experiencia de los usuarios del servicio.

Los datos utilizados provienen de dos conjuntos de datos principales:
- telecom_dataset_us.csv: Contiene información sobre las llamadas realizadas por los operadores, incluyendo detalles como la dirección de la llamada (entrante o saliente), la duración, el número de llamadas perdidas, entre otros.
- telecom_clients_us.csv: Contiene información de los clientes del servicio, como su tarifa actual y la fecha de registro.
Herramientas Utilizadas

---

The goal of this project is to identify ineffective operators in the CallMeMaybe virtual telephony service, based on several performance indicators. An operator is considered ineffective if they have a high number of missed calls, long waiting times for incoming calls, and a low number of outgoing calls made. This analysis enables service supervisors to make informed decisions to improve efficiency and customer service quality.

The analysis consists of several phases: an exploratory data analysis (EDA) to understand the behavior of the calls, followed by identifying ineffective operators using key metrics, and conducting statistical hypothesis tests to validate the findings. The information extracted from this analysis can be used to optimize operator performance and enhance the user experience.

The data used comes from two main datasets:
- telecom_dataset_us.csv: Contains information about the calls made by operators, including details like the direction of the call (incoming or outgoing), duration, number of missed calls, among others.
- telecom_clients_us.csv: Contains information about the service's clients, such as their current plan and registration date.

## Herramientas utilizadas / Tools Used
Herramientas y tecnologías utilizadas para limpiar, analizar, visualizar y comunicar los resultados del análisis de datos
1. Python: Se utilizó Python para realizar la limpieza de los datos, el análisis exploratorio, y las pruebas estadísticas. Las librerías principales fueron:
 - Pandas: Para la manipulación y limpieza de los datos.
 - Matplotlib y Seaborn: Para crear visualizaciones de datos y analizar patrones.
 - SciPy: Para llevar a cabo las pruebas estadísticas y validar las hipótesis.
 - datetime: Se utilizó para manejar y transformar fechas, lo que permitió realizar análisis basados en periodos de tiempo y extraer información relevante como la frecuencia de las llamadas en ciertos intervalos.
2. Tableau: Tableau fue utilizado para crear un dashboard interactivo que visualiza los hallazgos del análisis. Este dashboard permite a los supervisores explorar los datos de manera intuitiva y acceder a insights clave sobre el rendimiento de los operadores.
- Jupyter Notebooks: Para documentar y ejecutar todo el flujo de trabajo del análisis, proporcionando un entorno interactivo y reproducible.

---

The following tools and technologies were used to clean, analyze, visualize, and communicate the results of the data analysis:
1. Python: Python was used for data cleaning, exploratory analysis, and statistical testing. The main libraries were:
 - Pandas: For data manipulation and cleaning.
 - Matplotlib and Seaborn: For data visualization and pattern analysis.
 - SciPy: For conducting statistical tests and validating hypotheses.
 - datetime: Used to handle and transform dates, allowing for time-based analysis and extracting relevant information such as call frequency in certain intervals.
 - Tableau: Tableau was used to create an interactive dashboard that visualizes the findings from the analysis. This dashboard allows supervisors to explore the data intuitively and access key insights about operator performance.
 - Jupyter Notebooks: Used to document and execute the entire analysis workflow, providing an interactive and reproducible environment.

## Enlace al Dashboard en Tableau / Link to Tableau Dashboard
https://public.tableau.com/views/CallAnalysisbyDurationTypeandDirection/Dashboard1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
