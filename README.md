# CIFAR-10 Image Classification with CNN

This project demonstrates how to build and train a **Convolutional Neural Network (CNN)** using TensorFlow and Keras to classify images from the **CIFAR-10** dataset.

## Project Overview

- **Objective**: Classify 32x32 color images into one of 10 mutually exclusive classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).
- **Dataset**: CIFAR-10, consisting of 60,000 images (50,000 training, 10,000 testing).
- **Framework**: TensorFlow 2.x and Keras Sequential API.

## Model Architecture

The model follows a standard CNN pattern:
1. **Convolutional Base**: A stack of `Conv2D` and `MaxPooling2D` layers to extract features from the images.
2. **Classifier**: A `Flatten` layer followed by `Dense` (fully connected) layers to perform the final classification.

## Key Features

- Data normalization (scaling pixel values to the range 0-1).
- Exploratory Data Analysis (EDA) by visualizing the first 25 images of the dataset.
- Performance evaluation using accuracy and loss metrics across 10 training epochs.

## Results

The simple CNN architecture achieves over **70% accuracy** on the test dataset.
