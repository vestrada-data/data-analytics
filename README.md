# data-analytics-portfolio
# Análisis de Movilidad vs. Desarrollo Económico (PIB)

Este proyecto analiza la relación entre el Producto Interno Bruto (PIB) y los indicadores de movilidad, específicamente el retraso en minutos, para identificar cómo el desarrollo económico impacta (o se ve impactado por) la eficiencia en el transporte.

📊 Descripción del Proyecto

El objetivo principal es realizar un Análisis Exploratorio de Datos (EDA) para visualizar la distribución del PIB frente a las métricas de retraso, buscando patrones o correlaciones significativas que ayuden a la toma de decisiones estratégicas.

🛠️ Herramientas Utilizadas

Lenguaje: Python 3.x
Librerías de Datos: Pandas, NumPy

Visualización: Matplotlib, Seaborn

Base de Datos: Python (Extracción y limpieza inicial)

Documentación: Markdown

📁 Estructura del Repositorio
data/: Contiene los datasets originales (o enlaces a las fuentes).

notebooks/: Jupyter Notebooks con el proceso de limpieza y análisis.

visuals/: Gráficos de barras, histogramas y diagramas de caja generados.

📈 Hallazgos Principales 
No se encontró una relación directa entre el PIB per cápita y la congestión vehicular. 

Existen ciudades con alto PIB y alta congestión vehicular, así como ciudades con menor PIB pero distintos niveles de tráfico. 

Destacan ciudades como Lima y Ciudad de México, donde hay altos niveles de congestión vehicular pero un PIB per cápita que no es de los más altos, lo que sugiere que la congestión no depende únicamente del nivel económico, sino de factores como infraestructura, planeación urbana y transporte público.

Por otro lado, ciudades como Santiago muestran baja congestión vehicular y alto PIB, funcionando como un caso más eficiente.

![Comportamiento de los minutos de congestion](//content/sample_data/grafico_boxplot.png)


🚀 Cómo Ejecutar el Proyecto

Abre el archivo notebooks/analisis_principal.ipynb para ver el paso a paso.
