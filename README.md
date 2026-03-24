# MNIST Neural Network from Scratch

A 2-layer neural network built entirely from scratch using Python and NumPy to recognize handwritten digits from the MNIST dataset. This project implements the core math behind neural networks without relying on high-level machine learning libraries like TensorFlow or PyTorch.

## Motivation
As a Computer Science student, I built this to gain a deeper, hands-on understanding of the linear algebra and calculus (specifically Backpropagation) that power modern AI models. 

## Implementation Details
* **Forward & Backward Propagation:** Custom implementations using matrix multiplication.
* **Activation Functions:** ReLU for the hidden layer and a numerically stable Softmax for the output layer.
* **Optimization:** Standard Gradient Descent.

## Architecture & Performance
After tuning the hyperparameters to balance between underfitting and overfitting, the current model achieves the following:
* **Architecture:** 784 Input nodes -> 50 Hidden nodes -> 10 Output nodes.
* **Accuracy:** ~86%-90% on the validation set after 500 iterations (Learning rate: 0.1).

## Dependencies
To run the notebook, you only need the following libraries (also listed in `requirements.txt`):
* Python 3
* NumPy 
* Matplotlib (for prediction visualization)

## Future Work
This repository currently contains the V1 baseline (procedural programming). The next planned step is an Object-Oriented Programming (OOP) refactor to encapsulate the logic into a `NeuralNetwork` class, which will support saving/loading weights and adding dynamic hidden layers.
