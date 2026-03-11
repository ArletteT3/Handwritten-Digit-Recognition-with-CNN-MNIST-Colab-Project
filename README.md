[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/ArletteT3/mnist-cnn-digit-recognition/blob/main/notebook/handwritten_digit_cnn_mnist.ipynb)

# Handwritten Digit Recognition with CNN (MNIST)

Author: Arlette Torres  
Course: CPSC 4330 Multimedia Processing  
Instructor: Prof. Jiangjiang (Jane) Liu  

## Project Overview
This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) using the MNIST dataset.

The model was developed in Google Colab using TensorFlow and Keras.

## Dataset
MNIST dataset  
70,000 grayscale images (28×28 pixels)

80% training set  
20% testing set

Source:
http://yann.lecun.com/exdb/mnist/

## Technologies Used
Python  
TensorFlow / Keras  
NumPy  
Matplotlib  
Scikit-learn  
Seaborn

## Model Architecture
Conv2D → Conv2D → MaxPooling → Dropout  
Conv2D → MaxPooling → Flatten  
Dense → Dropout → Softmax

## Results
Test Accuracy: ~99%

The model successfully classifies handwritten digits with high accuracy.

## Files Included
notebook/ – CNN training notebook  
data/ – MNIST dataset split  
results/ – screenshots and evaluation results

## How to Run
1. Open the notebook in Google Colab
2. Enable GPU runtime
3. Run all cells
