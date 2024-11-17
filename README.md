# Análisis de Tópicos con LDA sobre noticias de Chile

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

Script que utiliza el modelo de **Latent Dirichlet Allocation (LDA)** para analizar grandes volúmenes de noticias sobre Chile, con el fin de identificar los temas o tópicos más relevantes en distintos períodos. Las noticias son extraídas desde fuentes locales, procesadas mediante técnicas de procesamiento de lenguaje natural (NLP) y visualizadas a través de gráficos interactivos para su análisis.

## Funcionalidades

- **Extracción de noticias**: Obtención de noticias desde diversas fuentes en línea de Chile.
- **Análisis de tópicos**: Aplicación de LDA para identificar los temas recurrentes en las noticias.
- **Visualización interactiva**: Uso de **pyLDAvis** para representar gráficamente los tópicos y sus relaciones.
- **Análisis por localidades**: Estudio de las noticias segmentado por ciudades y comunas de Chile.
- **Optimización de tópicos**: Evaluación del número óptimo de tópicos mediante la coherencia de los modelos.

## Ejecución

El archivo `analisis-topicos-lda-noticias-chile` realiza las siguientes tareas:
- Conexión al motor de búsqueda para extraer noticias.
- Preprocesamiento de las noticias y extracción de tópicos utilizando el modelo LDA.
- Visualización de los tópicos utilizando **pyLDAvis**.