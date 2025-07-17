# 👕 Fashion MNIST Classification with Neural Networks

This project demonstrates a multi-class image classification model trained on the **Fashion MNIST** dataset using **TensorFlow** and **Keras**. The goal is to classify grayscale images of clothing items into 10 categories (e.g., T-shirt, trouser, sneaker, etc.).

## 🧠 Model Overview

- **Input**: 28x28 grayscale image
- **Model Type**: Multi-Layer Perceptron (MLP)
- **Architecture**:
  - Input Layer (Flatten)
  - Hidden Layer 1: Dense (128 units, ReLU)
  - Hidden Layer 2: Dense (128 units, ReLU)
  - Output Layer: Dense (10 units, Softmax)

## 🧪 Loss Function & Optimizer

- **Loss**: `CategoricalCrossentropy` (for one-hot encoded labels)
- **Optimizer**: `RMSprop`
- **Metrics**: Accuracy

## 📊 Training Results

- Training performed over 21 epochs
- Accuracy and loss are tracked for both training and validation sets
- Results are visualized using Matplotlib for performance monitoring

## 📈 Sample Output Plots

- Training vs. Validation Loss
- Training vs. Validation Accuracy

## 🗂 Dataset

- **Fashion MNIST** dataset (loaded via `tensorflow.keras.datasets`)
- Contains 70,000 images:
  - 60,000 training samples
  - 10,000 test samples
- Each image is 28x28 pixels, labeled with one of 10 fashion categories


