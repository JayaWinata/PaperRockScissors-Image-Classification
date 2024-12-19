# Paper-Rock-Scissors Image Classification

## Overview
This project is a final project for the Dicoding course "Belajar Machine Learning untuk Pemula". It aims to classify images of rock, paper, and scissors gestures using machine learning techniques.

## Key Features
- Utilizes deep learning for image classification.
- Dataset includes images of rock, paper, and scissors.
- Implemented using TensorFlow and Keras.

## Key Steps
1. Dataset collection and preprocessing.
2. Model architecture design.
3. Model training and evaluation.
4. Validation of the model accuracy.

## Model Architecture
The model uses a **Convolutional Neural Network (CNN)** architecture, which is ideal for image classification:
1. **Input Layer**: Accepts images of rock, paper, or scissors.
2. **Convolutional Layers**: These layers apply various filters to detect important features like edges and shapes in the image.
3. **Pooling Layers**: Reduce the spatial dimensions of the image, improving efficiency and reducing computational load.
4. **Fully Connected Layers**: These layers perform the final classification based on the learned features.
5. **Output Layer**: Predicts one of the three classes: rock, paper, or scissors.

## Results
- The model achieved a validation accuracy of **95%**.

## Project Limitations
- The model is not capable of correctly predicting real-world data, as it was trained on a limited dataset of images. 
