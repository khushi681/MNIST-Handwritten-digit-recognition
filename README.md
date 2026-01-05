# MNIST-Handwritten-digit-recognition
# Handwritten Digit Recognition using CNN (MNIST)

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits using the MNIST dataset.

The goal of this project was not just to achieve high accuracy, but to understand how CNNs learn patterns from image data and how training, validation, and loss behave during learning.

## 🔹 What this project covers
- Loading and preprocessing image data
- Building a CNN using TensorFlow/Keras
- Training and validating the model
- Visualizing accuracy and loss using Matplotlib
- Evaluating performance on unseen test data

## 🔹 Tech stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## 🔹 Results
- Training Accuracy: ~99%
- Validation Accuracy: ~98–99%
- Test Accuracy: ~98%

## 🔹 Key learnings
- How CNNs extract features step by step (edges → shapes → digits)
- Why validation accuracy is crucial for detecting overfitting
- How plotting loss and accuracy reveals model behavior
- Importance of training before evaluation

## 🔹 How to run
```bash
pip install -r requirements.txt
python mnist_cnn.py

