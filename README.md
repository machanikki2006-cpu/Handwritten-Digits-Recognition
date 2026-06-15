# Handwritten Digit Recognition using Deep Learning

## Overview
This project is a **Handwritten Digit Recognition System** built using **Deep Learning** and the **MNIST dataset**. The model is trained to recognize handwritten digits (0–9) using a **Convolutional Neural Network (CNN)** implemented with **TensorFlow/Keras**.

The objective of this project is to classify handwritten digits accurately by training a neural network on image data and evaluating its performance using classification metrics.

---

## Features
- Recognizes handwritten digits from **0 to 9**
- Uses the **MNIST dataset** for training and testing
- Image preprocessing and normalization
- Deep learning model built using **TensorFlow/Keras**
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

---

## Technologies Used
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Scikit-learn**
- **Jupyter Notebook**

---

## Dataset
The project uses the **MNIST (Modified National Institute of Standards and Technology)** dataset, which contains:

- **60,000 training images**
- **10,000 testing images**
- Grayscale images of handwritten digits
- Image size: **28 × 28 pixels**

Each image represents a handwritten digit between **0–9**.

---

## Project Workflow

### 1. Data Loading
The MNIST dataset is loaded using TensorFlow/Keras.

### 2. Data Preprocessing
- Reshaped images into **(28, 28, 1)** format for CNN input
- Normalized pixel values from **0–255 to 0–1**
- Converted data into NumPy arrays for efficient processing

### 3. Model Building
A **Convolutional Neural Network (CNN)** architecture is used for digit classification.

The model includes:
- Convolutional layers for feature extraction
- Pooling layers for dimensionality reduction
- Dense layers for classification
- Softmax activation for multi-class prediction

### 4. Model Training
The model is trained on the training dataset for multiple epochs using the **Adam optimizer** and **Sparse Categorical Crossentropy** loss function.

### 5. Model Evaluation
The trained model is evaluated using:
- Classification Report
- Confusion Matrix
- Prediction Accuracy

---

## Installation

Clone the repository:

```bash
git clone https://github.com/machanikki2006-cpu/Handwritten-Digits-Recognition.git
