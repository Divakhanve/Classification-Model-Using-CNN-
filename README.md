# CIFAR-10 Image Classification with TensorFlow

This repository contains a simple Convolutional Neural Network (CNN) model implemented in TensorFlow for image classification using the CIFAR-10 dataset.

## Overview

The code demonstrates the following steps:

1. **Dataset Loading and Preprocessing:**
   - The CIFAR-10 dataset is loaded using TensorFlow's dataset utility.
   - Images are normalized to the range [0, 1].

2. **Model Architecture:**
   - A simple CNN model is created using the Sequential API.
   - Convolutional layers with ReLU activation and max-pooling are used.
   - Fully connected layers with ReLU activation are included.
   - The model outputs probabilities using the softmax activation for 10 classes (CIFAR-10 categories).

3. **Model Compilation:**
   - The model is compiled using the Adam optimizer and sparse categorical cross-entropy loss.

4. **Model Training:**
   - The model is trained on the training set for a specified number of epochs.

5. **Model Saving:**
   - The trained model is saved in the HDF5 format.

6. **Model Evaluation:**
   - The model is evaluated on the test set, and accuracy and loss are reported.



