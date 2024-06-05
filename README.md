# Bone-Fracture-Classification-using-CNN
# Fracture Detection Model

This project involves training a Convolutional Neural Network (CNN) to detect fractures in images. The model is built using TensorFlow and Keras, and it is trained to classify images into two categories: "fractured" and "non-fractured".

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.6 or later
- TensorFlow 2.x
- Keras
- NumPy

## Training the Model

The model architecture consists of several convolutional and max-pooling layers, followed by dense layers. The training script includes the following steps:

1. Define the dimensions and color channels of your images.
2. Define the model architecture.
3. Compile the model.
4. Train the model.
5. Save the trained model.

## Making Predictions

To make predictions on new images, use the `predict.py` script. This script includes the following steps:

1. Load the trained model.
2. Load and preprocess the image.
3. Make predictions and convert predictions to labels (fractured or non-fractured).

## Dependencies

List your dependencies in `requirements.txt` for easy installation:
- TensorFlow
- NumPy

