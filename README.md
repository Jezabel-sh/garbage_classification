# ♻️ Garbage Classification using Deep Learning | Clasificación de Basura usando Deep Learning

[English](#english) | [Español](#español)

## English

**Deep learning-based garbage classification model using EfficientNet.**

### 🚀 Project Overview
This project focuses on classifying different types of garbage using a deep learning model trained on a dataset containing images of various waste materials.
- **Model:** EfficientNet-based CNN for garbage classification.
- **Dataset:** Includes images of plastic, paper, glass, metal, etc.
- **Implementation:** Built with TensorFlow and Keras, featuring transfer learning.
- **Notebook:** Provides an end-to-end workflow for training, evaluation, and testing.

### 📂 Files Included
- `garbage_classification.ipynb` - Jupyter Notebook with dataset processing, model training, and evaluation.
- `best_model.keras` - Trained deep learning model.
- Images folder - Contains dataset samples used for training.

### 💻 Installation & Usage
To run the notebook and train/test the model, follow these steps:
```bash
git clone https://github.com/Jezabel-sh/garbage_classification.git
cd garbage_classification
conda create --name garbage-classifier python=3.11 -y
conda activate garbage-classifier
pip install -r requirements.txt
jupyter notebook
```

---

## Español

**Modelo de clasificación de basura basado en deep learning utilizando EfficientNet.**

### 🚀 Descripción del Proyecto
Este proyecto se centra en la clasificación de diferentes tipos de basura utilizando un modelo de deep learning entrenado con un conjunto de datos que contiene imágenes de diversos materiales de desecho.
- **Modelo:** CNN basada en EfficientNet para la clasificación de basura.
- **Conjunto de datos:** Incluye imágenes de plástico, papel, vidrio, metal, etc.
- **Implementación:** Desarrollado con TensorFlow y Keras, utilizando transfer learning.
- **Notebook:** Proporciona un flujo de trabajo completo para entrenamiento, evaluación y pruebas.

### 📂 Archivos Incluidos
- `garbage_classification.ipynb` - Notebook de Jupyter con procesamiento del conjunto de datos, entrenamiento del modelo y evaluación.
- `best_model.keras` - Modelo de deep learning entrenado.
- Carpeta de imágenes - Contiene muestras del conjunto de datos utilizadas para el entrenamiento.

### 💻 Instalación y Uso
Para ejecutar el notebook y entrenar/probar el modelo, sigue estos pasos:
```bash
git clone https://github.com/Jezabel-sh/garbage_classification.git
cd garbage_classification
conda create --name garbage-classifier python=3.11 -y
conda activate garbage-classifier
pip install -r requirements.txt
jupyter notebook
```
