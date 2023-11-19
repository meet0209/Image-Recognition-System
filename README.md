# Convolutional Neural Network for Fashion MNIST

This repository contains a Python script that uses the Keras library to build, train, and evaluate a Convolutional Neural Network (CNN) for the Fashion MNIST dataset.

## Project Description

The script performs the following steps:

1. Imports necessary libraries and modules from Keras.
2. Loads and preprocesses the Fashion MNIST dataset.
3. Creates a Sequential model and configures it with one convolutional layer, a flattening layer, and a dense layer.
4. Compiles the model with the 'adam' optimizer, 'sparse_categorical_crossentropy' as the loss function, and 'accuracy' as the metric.
5. Trains the model on the training data for 10 epochs with a batch size of 64.
6. Evaluates the trained model on the test data and prints out the test accuracy.

## Installation

To run the script, you need to have Python installed on your machine. You can download Python [here](https://www.python.org/downloads/).

You also need to install the Keras library. You can do this by running the following command in your terminal:

## Usage

To run the script, navigate to the directory containing the script in your terminal and run the following command:

## Results

The model achieves a test accuracy of approximately 90.53%, indicating that it can correctly predict the class of the images in the test set about 90.53% of the time.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


