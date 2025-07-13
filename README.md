# Sistema-Inteligente-basado-en-CNN-para-el-diagnostico-de-cancer-de-pulmon
Este repositorio contiene el código desarrollado en Python y ejecutado en Google Colab como parte de un artículo científico sobre la detección automática de cáncer pulmonar. Se emplearon técnicas de Deep Learning para el análisis de imágenes médicas (tomografías computarizadas en 2D), utilizando redes neuronales convolucionales (CNN) para la clasificación entre casos con y sin cáncer.

El sistema incluye:

- Entrenamiento de tres modelos: una CNN 2D personalizada, DenseNet121 y ResNet50.
- Evaluación del rendimiento con métricas clínicas relevantes (AUC-ROC, sensibilidad, precisión, F1, Dice, matriz de confusión).
- Visualización de mapas de saliencia (heatmaps) para interpretación médica.
- Comparación de desempeño entre modelos.

Dataset utilizado:

El conjunto de datos utilizado contiene miles de imágenes de resonancia magnética (MRI) de pulmones, cada una de las cuales ha sido anotada por cuatro radiólogos expertos para identificar y clasificar nódulos pulmonares como benignos o malignos.
- Enlace al dataset: https://www.kaggle.com/datasets/xiaopengzhang12/lung-cancer-mri-images
