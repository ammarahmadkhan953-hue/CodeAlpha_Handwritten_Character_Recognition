# CodeAlpha_Handwritten_Character_Recognition
# Handwritten Character Recognition using CNN

## Overview
This repository contains my solution for the Handwritten Character Recognition task as part of the CodeAlpha Machine Learning Internship. The project focuses on identifying and classifying handwritten digits using image processing and deep learning.

## Dataset
The model is trained and evaluated on the **MNIST** dataset, which consists of 70,000 grayscale images of handwritten digits (0-9) normalized for optimal neural network performance.

## Model Architecture
The core of this project is a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The architecture is designed for efficient feature extraction and classification, utilizing:
* **Conv2D Layers:** For extracting visual patterns and features from the images.
* **MaxPooling2D Layers:** For dimensionality reduction and retaining important features.
* **Dense Layers:** A fully connected layer leading into a 10-node softmax output for classifying the digits 0 through 9.

## Technologies Used
* Python
* TensorFlow / Keras
* Matplotlib
* NumPy

## Author
**Muhammad Shahzaib**
Machine Learning Intern at CodeAlpha
