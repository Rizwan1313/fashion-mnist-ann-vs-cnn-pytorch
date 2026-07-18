# Fashion-MNIST Classification using ANN and CNN with Swish & Mish Activations

## Overview

This project compares the performance of a Multi-Layer Perceptron (ANN) and a Deep Convolutional Neural Network (CNN) for Fashion-MNIST image classification using PyTorch.

The models incorporate modern activation functions (Swish and Mish), dropout regularization, batch normalization, and data augmentation to improve classification performance.

---

## Features

- PyTorch implementation
- Fashion-MNIST dataset
- ANN vs CNN comparison
- Swish & Mish activation functions
- Data augmentation
- Batch Normalization
- Dropout Regularization
- Adam Optimizer
- Accuracy & Loss Curves
- Confusion Matrix
- Softmax Confidence Visualization

---

## Dataset

Fashion-MNIST contains:

- 70,000 grayscale images
- 10 clothing categories
- Image size: 28×28 pixels

Dataset Source:

https://github.com/zalandoresearch/fashion-mnist

---

## Model Architectures

### ANN

- Input: 784 neurons
- Hidden Layer 1: 512 (Swish)
- Hidden Layer 2: 256 (Mish)
- Dropout
- Output: 10 Classes

### CNN

- 3 Convolution Blocks
- Batch Normalization
- Swish Activation
- Max Pooling
- Dropout
- Fully Connected Layer
- Mish Activation

---

## Results

| Model | Test Accuracy |
|--------|--------------|
| ANN | 81.37% |
| CNN | 91.22% |

The CNN significantly outperformed the ANN by effectively capturing spatial image features.

---

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn

---

## Installation

```bash
git clone https://github.com/yourusername/fashion-mnist-ann-vs-cnn-pytorch.git

cd fashion-mnist-ann-vs-cnn-pytorch

pip install -r requirements.txt
