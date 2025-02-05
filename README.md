#  CallMeMaybe-Operator-Analysis
Identificar operadores ineficaces en el servicio de telefonía virtual CallMeMaybe mediante el análisis de datos de llamadas.

Identifying inefficient operators in the CallMeMaybe virtual phone service through call data analysis.
 
## Contexto / Context
El servicio de telefonía virtual CallMeMaybe busca optimizar el rendimiento de sus operadores al identificar a aquellos que presentan ineficiencias. Se considera que un operador es ineficaz si:
- Tiene una gran cantidad de llamadas entrantes perdidas (internas y externas).
- Presenta un tiempo de espera prolongado para las llamadas entrantes.
- Realiza un número reducido de llamadas salientes, en caso de que su función lo requiera.

Este análisis es crucial para mejorar la experiencia del cliente y optimizar los recursos operativos, permitiendo que los supervisores tomen decisiones informadas sobre su equipo.

---

The CallMeMaybe virtual phone service aims to optimize operator performance by identifying those who exhibit inefficiencies. An operator is considered inefficient if:
- They have a high number of missed incoming calls (both internal and external).
- They have prolonged waiting times for incoming calls.
- They make a low number of outgoing calls, if their role requires it.

This analysis is crucial for improving customer experience and optimizing operational resources, allowing supervisors to make informed decisions about their team.

## Datos utilizados / Data Used
Los datasets empleados en este proyecto contienen información sobre el uso del servicio de telefonía virtual:
- telecom_dataset_us.csv: Contiene datos de llamadas realizadas, incluyendo
- telecom_clients_us.csv: Contiene información sobre los clientes

---

The datasets used in this project contain information about the virtual phone service usage:
- telecom_dataset_us.csv: Contains call data, including details of calls made.
- telecom_clients_us.csv: Contains client information.

## Herramientas utilizadas / Tools Used
- Python: Lenguaje principal para el análisis de datos.
- Pandas: Manipulación y análisis de datos.
- Matplotlib & Seaborn: Visualización de datos.
- Scipy: Pruebas estadísticas.

---

- Python: Main programming language for data analysis.
- Pandas: Data manipulation and analysis.
- Matplotlib & Seaborn: Data visualization.
- SciPy: Statistical testing.

## Análisis y Resultados / Analysis and Results
- Exploración de Datos: Se analizaron los datasets proporcionados para comprender la estructura y calidad de los datos.
- Identificación de Operadores Ineficaces: Se establecieron criterios para determinar qué operadores presentan un desempeño deficiente.
- Prueba de Hipótesis: Se llevaron a cabo pruebas estadísticas para validar los hallazgos y determinar la significancia de los resultados obtenidos.

---

- Data Exploration: The provided datasets were analyzed to understand their structure and quality.
- Identification of Inefficient Operators: Criteria were established to determine which operators exhibited poor performance.
- Hypothesis Testing: Statistical tests were conducted to validate findings and determine the significance of the results.


