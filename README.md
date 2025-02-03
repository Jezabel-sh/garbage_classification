# ♻️ Garbage Classification using Deep Learning

**Deep learning-based garbage classification model using EfficientNet.**

## 🚀 Project Overview
This project focuses on classifying different types of garbage using a deep learning model trained on a dataset containing images of various waste materials.

- **Model:** EfficientNet-based CNN for garbage classification.
- **Dataset:** Includes images of plastic, paper, glass, metal, etc.
- **Implementation:** Built with TensorFlow and Keras, featuring transfer learning.
- **Notebook:** Provides an end-to-end workflow for training, evaluation, and testing.

## 📂 Files Included
- `garbage_classification.ipynb` - Jupyter Notebook with dataset processing, model training, and evaluation.
- `best_model.keras` - Trained deep learning model.
- Images folder - Contains dataset samples used for training.

## 💻 Installation & Usage
To run the notebook and train/test the model, follow these steps:

```bash
git clone https://github.com/Jezabel-sh/garbage_classification.git
cd garbage_classification
conda create --name garbage-classifier python=3.11 -y
conda activate garbage-classifier
pip install -r requirements.txt
jupyter notebook
