<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Garbage Classification - Deep Learning</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }
        h1, h2 {
            color: #2c3e50;
        }
        code {
            background: #f4f4f4;
            padding: 4px;
            border-radius: 4px;
        }
        pre {
            background: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>
<body>

    <h1>♻️ Garbage Classification using Deep Learning</h1>
    <p><strong>Deep learning-based garbage classification model using EfficientNet.</strong></p>

    <h2>🚀 Project Overview</h2>
    <p>This project focuses on classifying different types of garbage using a deep learning model trained on a dataset containing images of various waste materials.</p>
    
    <ul>
        <li><strong>Model:</strong> EfficientNet-based CNN for garbage classification.</li>
        <li><strong>Dataset:</strong> Includes images of plastic, paper, glass, metal, etc.</li>
        <li><strong>Implementation:</strong> Built with TensorFlow and Keras, featuring transfer learning.</li>
        <li><strong>Notebook:</strong> Provides an end-to-end workflow for training, evaluation, and testing.</li>
    </ul>

    <h2>📂 Files Included</h2>
    <ul>
        <li><code>garbage_classification.ipynb</code> - Jupyter Notebook with dataset processing, model training, and evaluation.</li>
        <li><code>best_model.keras</code> - Trained deep learning model.</li>
        <li>Images folder - Contains dataset samples used for training.</li>
    </ul>

    <h2>💻 Installation & Usage</h2>
    <p>To run the notebook and train/test the model, follow these steps:</p>
    
    <pre>
    git clone https://github.com/Jezabel-sh/garbage_classification.git
    cd garbage_classification
    conda create --name garbage-classifier python=3.11 -y
    conda activate garbage-classifier
    pip install -r requirements.txt
    jupyter notebook
    </pre>

    <h2>🔍 Model Performance</h2>
    <p>The model achieves high accuracy in distinguishing different waste categories, making it a useful tool for automated waste management systems.</p>

    <h2>📬 Contact</h2>
    <p>For inquiries or collaborations, feel free to reach out via <a href="mailto:your-email@example.com">email</a> or visit my <a href="https://github.com/Jezabel-sh">GitHub</a>.</p>

</body>
</html>
