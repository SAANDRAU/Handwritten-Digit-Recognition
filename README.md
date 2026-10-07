# Handwritten Digit Recognition using CNN

## Overview

This project implements a handwritten digit recognition system using a Convolutional Neural Network (CNN). The model is trained to recognize handwritten digits from 0 to 9 using the MNIST dataset.

The project demonstrates the use of deep learning and image classification techniques with TensorFlow and Keras.

## Dataset

The project uses the **MNIST handwritten digit dataset**, which contains grayscale images of handwritten digits from 0 to 9.

- Image size: 28 × 28 pixels
- Number of classes: 10
- Classes: Digits 0–9

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Convolutional Neural Networks (CNN)

## Project Workflow

1. Load the MNIST dataset
2. Preprocess the image data
3. Normalize the pixel values
4. Build a Convolutional Neural Network
5. Train the model
6. Evaluate the model on test data
7. Make predictions on handwritten digit images

## CNN Architecture

The neural network consists of:

- Convolutional layers (`Conv2D`)
- Max Pooling layers (`MaxPooling2D`)
- Flatten layer
- Dense (fully connected) layers
- Dropout layer
- Output layer with 10 classes using Softmax

The model predicts which digit (0–9) is represented in an input image.

## Model Performance

The trained CNN achieved approximately **97.74% accuracy** on the test dataset.

## Results

The model can classify handwritten digit images into one of the ten classes:

`0, 1, 2, 3, 4, 5, 6, 7, 8, 9`

## Project Structure

```text
Handwritten-Digit-Recognition/
│
├── Handwritten_Digit_Recognition.ipynb
└── README.md
