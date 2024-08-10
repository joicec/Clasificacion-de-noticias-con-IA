# Clasificador de Noticias con Inteligencia Artificial

Este proyecto tiene como objetivo desarrollar un modelo de inteligencia artificial que clasifique automáticamente noticias en tres categorías: **Política**, **Tecnología**, y **Ciencia**.

## Descripción del Proyecto

La clasificación de noticias es una tarea esencial en el periodismo digital moderno, donde la rapidez y precisión son cruciales debido a la sobrecarga de información y la competencia con las redes sociales. Este proyecto aborda este desafío desarrollando un modelo que ahorra tiempo, mejora la consistencia, y reduce errores en la clasificación de noticias.

## Funcionalidades Principales

- **Automatización de la clasificación**: El modelo utiliza técnicas de Machine Learning, específicamente TF-IDF (Term Frequency-Inverse Document Frequency), para clasificar noticias de manera automática.
- **Alta precisión**: El modelo ha sido entrenado y validado para ofrecer una precisión de clasificación del 86%, con un F1-Score promedio de 0.86.
- **API y Frontend**: Se ha desarrollado una API utilizando FastAPI, que permite a los usuarios acceder al modelo de clasificación como un servicio web. Además, un frontend implementado con Streamlit ofrece una interfaz intuitiva para la interacción con el sistema.

## Arquitectura del Proyecto

1. **Recolección y Preprocesamiento de Datos**: Los datos utilizados fueron obtenidos de Kaggle, consisten en un conjunto de noticias etiquetadas en las tres categorías mencionadas. Se realizó un proceso de limpieza y normalización de datos para mejorar la precisión del modelo.
   
2. **Modelo de IA**: El modelo se entrena utilizando un enfoque de vectorización de texto mediante TF-IDF, seguido de un clasificador que predice la categoría de la noticia.
   
3. **API y Frontend**: La API permite que el modelo sea accesible como un servicio web, mientras que el frontend facilita la interacción de los usuarios con el sistema.

## Resultados y Métricas

- **Precisión**: 86%
- **Recall**: 86%
- **F1-Score**: 0.86

Estos resultados demuestran que el modelo es capaz de clasificar noticias con un alto grado de precisión, ayudando a los medios de comunicación a mejorar su flujo de trabajo editorial.

## Próximos Pasos

- **Incorporar más categorías**: Expandir el modelo para clasificar noticias en más categorías.
- **Análisis en múltiples idiomas**: Implementar la capacidad de clasificar noticias en otros idiomas, como el español.
- **Automatización y seguridad**: Integrar funciones para la búsqueda y carga automática de noticias, y mejorar las medidas de seguridad.

