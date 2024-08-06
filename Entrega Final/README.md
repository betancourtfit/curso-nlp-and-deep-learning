
Proyecto 1: Análisis de Sentimiento para Comentarios de Clientes
1. Adquisición y Exploración de Datos
   * Descargar el conjunto de datos de Reseñas de Yelp
   * Cargar los datos utilizando pandas
   * Realizar un análisis exploratorio de datos inicial (EDA)
   * Identificar al menos tres hallazgos sobre los datos
2. Preprocesamiento de Datos
   * Limpiar los datos de texto (eliminar caracteres especiales, convertir a minúsculas, etc.)
   * Tokenizar las reseñas
   * Eliminar las palabras vacías
   * Realizar stemming o lematización
3. Ingeniería de Características
   * Convertir el texto a formato numérico utilizando técnicas como:
      * Bolsa de Palabras
      * TF-IDF
   * Dividir los datos en conjuntos de entrenamiento y prueba
4. Desarrollo del Modelo
   * Diseñar una red neuronal simple con al menos dos capas
   * Experimentar con diferentes arquitecturas (por ejemplo, capas Densas, LSTM)
   * Entrenar el modelo con los datos de entrenamiento
   * Evaluar el rendimiento del modelo en el conjunto de prueba
5. Mejora del Modelo
   * Agregar al menos dos capas más a la red
   * Implementar técnicas como dropout o normalización por lotes
   * Reentrenar el modelo mejorado
   * Comparar los resultados con el modelo simple
6. Evaluación y Análisis del Modelo
   * Evaluar el rendimiento del modelo utilizando métricas como precisión, recall y puntuación F1
   * Analizar las clasificaciones erróneas para entender las limitaciones del modelo
   * Visualizar los resultados utilizando matrices de confusión y curvas ROC
7. Conclusiones y Trabajo Futuro
   * Resumir los hallazgos y conocimientos obtenidos del proyecto
   * Discutir las fortalezas y debilidades del modelo
   * Proponer posibles mejoras y próximos pasos

Proyecto 3: Pronóstico de Series Temporales para Consumo de Energía
1. Adquisición y Exploración de Datos
   * Descargar el conjunto de datos de Consumo de Energía Eléctrica de Hogares
   * Cargar los datos utilizando pandas
   * Realizar un análisis exploratorio de datos inicial (EDA)
   * Identificar al menos tres hallazgos sobre los datos
2. Preprocesamiento de Datos
   * Manejar valores faltantes
   * Convertir las marcas de tiempo a formato datetime
   * Remuestrear los datos a intervalos horarios
   * Normalizar o estandarizar las características
3. Ingeniería de Características
   * Crear características basadas en el tiempo (hora del día, día de la semana, mes, etc.)
   * Generar características de retraso
   * Dividir los datos en conjuntos de entrenamiento y prueba
4. Desarrollo del Modelo
   * Diseñar una red RNN o LSTM simple con al menos dos capas
   * Preparar los datos en el formato correcto para la predicción de series temporales
   * Entrenar el modelo con los datos de entrenamiento
   * Evaluar el rendimiento del modelo en el conjunto de prueba
5. Mejora del Modelo
   * Agregar al menos dos capas más a la red
   * Experimentar con diferentes tipos de células RNN (GRU, LSTM bidireccional)
   * Implementar técnicas como dropout o normalización por lotes
   * Reentrenar el modelo mejorado
   * Comparar los resultados con el modelo simple
6. Evaluación y Análisis del Modelo
   * Evaluar el rendimiento del modelo utilizando métricas como MAE, MSE y RMSE
   * Visualizar las predicciones vs. valores reales
   * Analizar el rendimiento del modelo en diferentes períodos de tiempo
7. Conclusiones y Trabajo Futuro
   * Resumir los hallazgos y conocimientos obtenidos del proyecto
   * Discutir las fortalezas y debilidades del modelo
   * Proponer posibles mejoras y próximos pasos