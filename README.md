# Reportes
Reportes con distintos indicadores y procesos. Construidos con fines recreativos y de aprendizaje

## Fondos de Pensiones
El objetivo es evaluar el desempeño de los distintos fondos de pensiones segun su nivel de riesgo, Administradora, valores cuotas y rentabilidades.\
El proceso comienza con un scraping a la [superintendencia de pensiones](https://www.spensiones.cl/apps/valoresCuotaFondo/vcfAFP.php), los datos son procesados y guardados en una base de datos, y finalmente son visualizados en el reprote. \
[Ver Reprote Aquí](https://app.powerbi.com/view?r=eyJrIjoiZTk5ZDIyZjQtYjYyZi00OWQyLTlhNWItNTFkNzExNTZkNWJjIiwidCI6IjM2YjZkNDEzLTNiNmYtNDgxYS1iYzlkLTY2ODliNTExY2FmYSIsImMiOjR9)\
\
Recursos Utilizados:
- Python (Anaconda)
- SQL Server Managment
- Power BI

## Palabras más Frecuentes en Medios Electrónicos
Reporte muestra las palabras mas publicadas en los medios electrónicos como el diario financiero, el mostrador, la nación y la tercera.
En él se ven palabras asociadas a tendencias políticas y económicas como el proceso constituyente y la crisis política en Taiwán.\
El proceso se ejecuta idealmente de forma diaria e incorpora un scraping a los cuatro medios digitales, donde se extraen las palabras, seguido de un proceso de depuración de datos y almacenamiento en una base de datos, terminando con la visualización de los datos en el siguiente link. \
[Ver Reprote Aquí](https://app.powerbi.com/view?r=eyJrIjoiYmE2ZjJhODEtMjkwOS00ZDExLTg4YmUtNmU5MzQwMDUwODA0IiwidCI6IjM2YjZkNDEzLTNiNmYtNDgxYS1iYzlkLTY2ODliNTExY2FmYSIsImMiOjR9)\
\
Recursos Utilizados:
- Python (Anaconda)
- SQL Server Managment
- Power BI


## Precio Dólar
Reporte muestra la evolución y distribución del tipo de cambio del dólar estadounidense.
En él es posible asociar el comportamiento del dólar en distintos contextos políticos y económicos de acuerdo con la fecha.
El proceso se puede ejecutar a disposición del usuario, y parte con el envío de un requerimiento a la API del Banco Central de Chile, la cual retorna datos que luego son procesados y almacenado en una base de datos, para posteriormente ser visaulizados en el reprote. \
Power BI [Ver Reporte Aquí](https://app.powerbi.com/view?r=eyJrIjoiZGNiYTkyYTItOWQ4Yy00ZWVkLWIyZDAtYjU4YjU5YTIxMjM2IiwidCI6IjM2YjZkNDEzLTNiNmYtNDgxYS1iYzlkLTY2ODliNTExY2FmYSIsImMiOjR9)
\
Tableau Public
[Ver Reporte Aquí](https://public.tableau.com/app/profile/sim.n3200/viz/TipodeCambioDolar/Dashboard1?publish=yes)
\
\
Recursos Utilizados:
- Python (Anaconda)
- API Banco Central
- SQL Server Managment
- Pentaho (Solo para Tableau)

