# mnist_neuralnet
Neural network for the MNIST dataset


- Roughly 85% accuracy as originally done with large data set in order to understand mathematics involed with NNs.

# Neural Network Architecture Description

## Overview
This document outlines the architecture of a neural network model designed for image classification tasks. The model follows a straightforward two-layer architecture, consisting of an input layer, a hidden layer, and an output layer.

## Architecture Details
### Input Layer (a[0])
- The input layer comprises 784 units, representing the 784 pixels in a 28x28 input image.

### Hidden Layer (a[1])
- This layer contains 10 units.
- Each unit is activated using the Rectified Linear Unit (ReLU) activation function.

### Output Layer (a[2])
- Consisting of 10 units, each corresponding to one of the ten digit classes (0 through 9).
- Softmax activation function is applied to produce probability distributions over the classes.

## Purpose
The purpose of this neural network architecture is to classify images into their respective digit classes with high accuracy.

## Usage
To utilize this neural network architecture, it can be implemented using various machine learning frameworks such as TensorFlow, PyTorch, or Keras.
