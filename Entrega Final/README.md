# Proyecto 1: Análisis de Sentimiento para Comentarios de Clientes

## Índice
1. [Adquisición y Exploración de Datos](#1-adquisición-y-exploración-de-datos)
2. [Preprocesamiento de Datos](#2-preprocesamiento-de-datos)
3. [Ingeniería de Características](#3-ingeniería-de-características)
4. [Desarrollo del Modelo](#4-desarrollo-del-modelo)
5. [Mejora del Modelo](#5-mejora-del-modelo)
6. [Evaluación y Análisis del Modelo](#6-evaluación-y-análisis-del-modelo)
7. [Conclusiones y Trabajo Futuro](#7-conclusiones-y-trabajo-futuro)

## 1. Adquisición y Exploración de Datos

- Descargar el conjunto de datos de Reseñas de Yelp
  - Dataset obtenido de Kaggle: [Yelp Review Polarity](https://www.kaggle.com/datasets/irustandi/yelp-review-polarity)
- Cargar los datos utilizando pandas
- Realizar un análisis exploratorio de datos inicial (EDA)
- Identificar al menos tres hallazgos sobre los datos

## 2. Preprocesamiento de Datos

- Limpiar los datos de texto:
  - Eliminar caracteres especiales
  - Convertir a minúsculas
- Tokenizar las reseñas
- Eliminar las palabras vacías (stop words)

## 3. Ingeniería de Características

- Convertir el texto a formato numérico utilizando Tokenizer de tensorflow
- Aplicar los mismos tratamientos a los conjuntos predividos de traing y tes

## 4. Desarrollo del Modelo

- Diseñar una red neuronal simple con 4 capas
- Experimentar con diferentes arquitecturas:
  - Capas Densas
  - LSTM (Long Short-Term Memory)
- Entrenar el modelo con los datos de entrenamiento
- Evaluar el rendimiento del modelo en el conjunto de prueba

## 5. Mejora del Modelo

- Agregar dos capas más a la red
- Implementar técnicas de regularización:
  - Dropout
  - Normalización por lotes (Batch Normalization)
- Reentrenar el modelo mejorado
- Comparar los resultados con el modelo simple

## 6. Evaluación y Análisis del Modelo

- Evaluar el rendimiento del modelo utilizando métricas:
  - Precisión (Precision)
  - Exhaustividad (Recall)
  - Puntuación F1 (F1-score)
- Analizar las clasificaciones erróneas para entender las limitaciones del modelo
- Visualizar los resultados:
  - Matrices de confusión
  - Curvas ROC (Receiver Operating Characteristic)

## 7. Conclusiones y Trabajo Futuro

- Resumir los hallazgos y conocimientos obtenidos del proyecto
- Discutir las fortalezas y debilidades del modelo
- Proponer posibles mejoras y próximos pasos
