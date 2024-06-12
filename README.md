# Image-Classification-Birds

Proyecto realizado para una de las asignaturas del Máster Universitario en Inteligencia Artificial de la Universidad Internacional de Valencia. 

Su objetivo principal es implementar y comparar varias arquitecturas de redes neuronales convolucionales (CNN) para determinar cuál ofrece el mejor rendimiento en la clasificación de especies de aves. Se evaluaron tres enfoques principales. Primero, se desarrollaron modelos "from scratch", diseñando y entrenando redes neuronales desde cero. Segundo, se aplicó Transfer Learning, utilizando modelos preentrenados en grandes conjuntos de datos y adaptándolos a nuestro conjunto específico de aves. Finalmente, se llevó a cabo el Fine Tuning, ajustando finamente los modelos preentrenados para mejorar su precisión en la clasificación de especies de aves.

Además, se implementaron diversas técnicas de preprocesamiento de imágenes para agilizar el entrenamiento y aumentar la diversidad de los datos de entrada mediante el uso de data augmentation, ayudando a mejorar la robustez y el rendimiento de los modelos.

Los resultados obtenidos de las diferentes arquitecturas se compararon utilizando múltiples métricas, como precisión, recall y F1-score, así como mediante la comparación de las gráficas de entrenamiento. Estas comparaciones proporcionaron una visión clara del rendimiento relativo de cada enfoque y ayudaron a identificar la mejor arquitectura para la tarea de clasificación de aves.

El conjunto de datos utilizado para este proyecto contiene imágenes de 525 especies de aves y está disponible en Kaggle (BIRDS 525 SPECIES- IMAGE CLASSIFICATION). Los datos están divididos en conjuntos de entrenamiento, validación y prueba, lo que permite evaluar de manera efectiva el rendimiento del modelo.
