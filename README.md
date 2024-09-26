# Neural Network from Scratch using NumPy

This repository contains implementations of a simple neural network from scratch using NumPy, designed to solve the XOR problem. The neural network includes two versions: one using the Sigmoid activation function and the other using the ReLU activation function for the hidden layer.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Training the Models](#training-the-models)
- [Results](#results)

## Introduction

The XOR problem is a classic example in machine learning where the output cannot be linearly separated. This neural network consists of one input layer, one hidden layer, and one output layer. The repository demonstrates fundamental concepts of neural networks, including forward propagation, backpropagation, and activation functions.

### Activation Functions
1. **Sigmoid Activation**: 
   - The first implementation uses the Sigmoid activation function for both the hidden layer and the output layer.
2. **ReLU Activation**: 
   - The second implementation uses the ReLU activation function for the hidden layer and the Sigmoid activation for the output layer.

## Technologies Used

- Python
- NumPy
- Jupyter Notebook

## Getting Started

### Prerequisites

To run the code, you need to have Python installed along with the NumPy library. You can install NumPy using pip:

```bash
pip install numpy
```

### Running the Jupyter Notebooks

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/ahmdmohamedd/numpy-neural-network.git
    ```
2. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3. Open the notebooks (`numpy_neural_network.ipynb`) to view and execute the code.

## Training the Models

Both models are trained on the XOR dataset, where the input and output are defined as follows:

- Input: `[[0, 0], [0, 1], [1, 0], [1, 1]]`
- Expected Output: `[[0], [1], [1], [0]]`

You can adjust the training iterations and learning rates in each notebook to observe different results.

## Results

After training, the predicted output of each neural network is displayed, along with the accuracy of each model on the XOR dataset.

Example of Predicted Output (ReLU):
```
[[0.05200231]
 [0.97116639]
 [0.9712641 ]
 [0.05200231]]
```
