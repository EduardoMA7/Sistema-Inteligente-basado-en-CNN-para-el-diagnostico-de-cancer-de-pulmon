# Sistema Inteligente basado en CNN para el diagnostico de cancer de pulmon
Este repositorio contiene el código desarrollado en Python y ejecutado en Google Colab como parte de un artículo científico sobre la detección automática de cáncer pulmonar. Se emplearon técnicas de Deep Learning para el análisis de imágenes médicas (tomografías computarizadas en 2D), utilizando redes neuronales convolucionales (CNN) para la clasificación entre casos con y sin cáncer.

Dataset utilizado:

El conjunto de datos utilizado contiene miles de imágenes de resonancia magnética (MRI) de pulmones, cada una de las cuales ha sido anotada por cuatro radiólogos expertos para identificar y clasificar nódulos pulmonares como benignos o malignos.
- Enlace al dataset: https://www.kaggle.com/datasets/xiaopengzhang12/lung-cancer-mri-images

# Cómo ejecutar el notebook
**Subir el dataset a Google Drive**

1. Antes de ejecutar el notebook, asegúrate de haber subido el dataset a tu cuenta de Google Drive

**Coloca tu token de Ngrok**

2. En la sección "Requerimientos" en la tercera celda del notebook, coloca tu token.

**Selecciona el modelo objetivo**

3. En la sección de "Entrenamiento", especifica el modelo que deseas entrenar en "modelo_objetivo = ". El proceso de entrenamiento puede tomar aproximadamente 3 horas en CPU.
  - CNN 2D personalizada
  - DenseNet121
  - ResNet50

**Ejecuta la aplicación final**

4. Ejecuta la aplicación mediante Streamlit conectada por Ngrok. Se imprimirá una URL pública para acceder a la interfaz web del sistema de diagnóstico.
