# MNIST Character Recognition with 4-Fold Cross Validation
MNIST Character Recognition with 4-Fold Cross Validation

This repository contains a deep learning project that performs character recognition on a subset of the MNIST dataset using a Convolutional Neural Network (CNN). 
The project includes a 4-fold cross-validation setup and visualizes accuracy and loss metrics across different folds.

Project Overview

Data Preparation: Randomly selects 500 samples from the MNIST training dataset (50 samples per class).
Model Definition: Constructs a CNN model for character recognition.
Cross-Validation: Implements 4-fold cross-validation to train and validate the model.
Visualization: Plots accuracy and loss graphs for each fold and their averages.

Requirements:
Python 3.x
TensorFlow/Keras
NumPy
Matplotlib

Dataset
The MNIST dataset consists of 70,000 28x28 grayscale images of handwritten digits. 
This project uses a subset of 500 samples from the training set.

Implementation Details
Model: The CNN includes three convolutional layers followed by max-pooling layers, a flatten layer, and dense layers.
Cross-Validation: The dataset is split into 4 folds. For each fold, the model is trained on 75% of the data and validated on the remaining 25%.
Metrics: Accuracy and loss are plotted for each fold and averaged across all folds.

Results
Accuracy and loss graphs will be generated and displayed for each fold, along with their averages.
