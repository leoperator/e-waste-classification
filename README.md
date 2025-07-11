# E-Waste Image Classification using CNN

This project classifies images of e-waste into 10 categories using a Convolutional Neural Network (CNN) built in TensorFlow.

Trained and tested on **Google Colab** with dataset downloaded via `gdown` from Google Drive.

---

## Project Overview

-  CNN-based image classification
-  Dataset structured into `train/`, `val/`, and `test/`
-  Measures training time with Python’s `time` module

---


## 📥 Dataset

The dataset is stored on Google Drive as a ZIP file.

- 🔗 [Download from Google Drive](https://drive.google.com/file/d/1BYLz8QCTjIvGTW3b-g0okooNZLJd4ykz/view?usp=sharing)
- Automatically downloaded and unzipped inside the notebook using `gdown`.

## 📌 Features
- Trained a CNN classifier from scratch using labeled e-waste images
- Achieved ~94% training and test accuracy
- Evaluated performance using confusion matrix and visualizations
- Deployed the trained model using [Gradio](https://gradio.app) for real-time image inference


## 🚀 Installation

```bash
git clone https://github.com/leoperator/e-waste-classification.git
cd e-waste-classification
pip install -r requirements.txt
```

## 🧠 Model Architecture

- Convolutional layers with ReLU activation and MaxPooling
- Dropout for regularization
- Fully connected output layer with softmax
- Loss Function: CrossEntropyLoss
- Optimizer: Adam

## 🛠️ Tech Stack
- Python, TensorFlow
- Matplotlib, NumPy, Scikit-learn
- Gradio (for deployment)
