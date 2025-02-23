# MNIST Handwritten Digit Recognition using ANN

## Overview
This project demonstrates the use of an Artificial Neural Network (ANN) for handwritten digit recognition using the MNIST dataset. The model is trained to classify digits (0-9) based on pixel intensity values from grayscale images.

## Features
- **Data Preprocessing:**  
  - Loading the MNIST dataset.  
  - Normalizing pixel values to improve model performance.  
  - Reshaping images for input compatibility with the neural network.  

- **ANN Model Architecture:**  
  - Input layer: Flattened 28x28 images into a 1D vector.  
  - Hidden layers: Fully connected layers with ReLU activation.  
  - Output layer: 10 neurons with Softmax activation for digit classification.  

- **Training & Evaluation:**  
  - Model trained using categorical cross-entropy loss and Adam optimizer.  
  - Evaluated using accuracy metrics on test data.  

## Dataset
The **MNIST dataset** consists of 60,000 training images and 10,000 test images of handwritten digits (0-9). Each image is 28x28 pixels in grayscale.  

## Dependencies
Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib tensorflow keras
