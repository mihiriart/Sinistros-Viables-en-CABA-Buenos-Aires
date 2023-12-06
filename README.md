Análisis de Víctimas Mortales en Accidentes Viales en la Ciudad Autónoma de Buenos Aires (CABA)

Introducción

Este proyecto se enfocó en realizar un análisis exhaustivo de las víctimas mortales en accidentes viales en la Ciudad Autónoma de Buenos Aires (CABA) utilizando un dataset oficial del gobierno argentino. El conjunto de datos abarca información sobre siniestros viales ocurridos entre 2016 y 2021, resguardando la identidad de los involucrados.

Los siniestros viales, también conocidos como accidentes de tráfico o tránsito, involucran vehículos en las vías públicas, con consecuencias que van desde daños materiales hasta lesiones fatales. Nos enfocamos particularmente en este último aspecto.

En Argentina, alrededor de 4.000 personas mueren anualmente en siniestros viales, siendo esta la principal causa de muerte violenta en el país. Datos del Sistema Nacional de Información Criminal revelan que entre 2018 y 2022 se registraron 19.630 muertes en todo el país, equivalente a un promedio de 11 personas fallecidas diariamente debido a accidentes de tránsito.

Los siniestros viales son una preocupación significativa en una ciudad como Buenos Aires, debido al alto tráfico y la densidad poblacional, lo que resalta la importancia de su análisis.

El análisis se llevó a cabo utilizando Python, haciendo uso de librerías como Pandas, Matplotlib, Seaborn, entre otras.

Objetivos

Realizar un análisis detallado de los conjuntos de datos para comprender la problemática y obtener información valiosa.
Desarrollar un dashboard que presente de manera efectiva la información obtenida del análisis para facilitar su comprensión.
Conjunto de Tecnologías Utilizadas

Visual Studio Code, Jupyter Notebook, Python, NumPy, Pandas, Matplotlib, PowerBI, Git, GitHub, Markdown, Web scarping.

ETL (Extracción, Transformación y Carga de Datos)

El proceso de ETL reveló que el conjunto de datos estaba mayormente limpio y listo para su análisis, con pocos datos faltantes o nulos y sin registros duplicados. Se realizaron tablas para facilitar el análisis, como la segmentación por semestres, y se eliminó la columna "Altura" por su escaso aporte de información.

Análisis Exploratorio de Datos (EDA)

Tras el proceso de ETL, el EDA inició con un análisis temporal que reveló un total de 714 víctimas entre los años 2016 y 2021. Posteriormente, se realizó un análisis geográfico utilizando Geopandas para explorar los siniestros viales por las 15 comunas de CABA, identificando la calle más peligrosa y el impacto de los cruces en la cantidad de homicidios en siniestros viales. La comuna 1 se destacó como la más letal, a pesar de no ser la más grande ni poblada según datos oficiales.

Otros análisis incluyeron el tipo de víctimas, donde predominaron los hombres y las muertes relacionadas con motocicletas y peatones. Se analizó la edad de las víctimas, revelando que la mayoría eran adultos jóvenes de 20 a 39 años. Además, se identificó a los principales acusados, donde predominaron los automóviles, vehículos de pasajeros y vehículos de carga.

KPIs (Indicadores Clave de Proceso)

Se solicitaron 3 KPIs para este proyecto, dos de los cuales se entregaron, mientras que el tercero se planteó utilizando la información obtenida.

Reducción del 10% en la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con el semestre anterior.

Disminución del 7% en la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

Reducción del 15% en la cantidad de homicidios en siniestros viales en la Comuna 1, en CABA, respecto al año anterior.

Estos KPIs se basan en tasas de mortalidad relacionadas con siniestros viales, que son indicadores críticos para evaluar la seguridad vial en una región.

Dashboard

Se creó un dashboard en Power BI para resumir visualmente la información obtenida en el análisis, integrando elementos visuales interactivos para facilitar la comprensión de los hallazgos.

Conclusiones Principales

Las cinco conclusiones más significativas incluyen:

La mayoría de las víctimas son hombres.
La comuna más letal es la comuna 1, a pesar de no ser la más grande ni poblada según datos oficiales.
La mayoría de las muertes ocurren en accidentes relacionados con motocicletas, evidenciando ser el medio de transporte más inseguro.
La mayoría de las víctimas tienen entre 20 y 39 años, sugiriendo que la conducción imprudente puede ser una de las principales causas de muerte en siniestros viales.
Existe una influencia significativa en la cantidad de siniestros viales en los cruces, con un impacto del 75.4%.
Para detalles adicionales y visualizaciones específicas, se puede acceder al archivo del EDA.D:\Usuario\Desktop\Data Analyst\EDA.ipynb

AUTOR María Inés Hiriart 