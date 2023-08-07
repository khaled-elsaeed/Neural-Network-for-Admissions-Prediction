# Neural Network for Admissions Prediction

This repository contains code for a simple neural network that predicts admission outcomes based on student data.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project demonstrates the implementation of a neural network to predict student admission outcomes based on GRE scores, GPAs, and school rankings. The network is trained on a dataset containing student information and their admission outcomes.

## Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies mentioned in the [Dependencies](#dependencies) section.
3. Run the provided Python script to train and test the neural network on the dataset.

## Usage

1. Prepare your dataset:
   - Ensure your dataset is in CSV format.
   - Update the `data` variable in the script with the appropriate dataset file path.

2. Preprocessing:
   - The script preprocesses the data by converting categorical features into one-hot encoding and scaling numeric features.

3. Training the Neural Network:
   - The script trains the neural network using the provided hyperparameters (epochs, learning rate).
   - During training, the loss is displayed for each epoch, and any increase in loss is highlighted as a warning.

4. Testing and Predictions:
   - After training, the script evaluates the trained model on a separate test dataset.
   - The accuracy of the predictions is calculated and displayed.

## Results

The neural network achieves a prediction accuracy of approximately 77.5% on the test dataset. The training process and accuracy evaluation are outlined in the code.

## Dependencies

- Python 3.x
- numpy
- pandas
- matplotlib

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or a pull request in this repository.
