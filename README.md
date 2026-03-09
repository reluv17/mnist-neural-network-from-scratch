# MNIST Neural Network From Scratch

A digit classifier built from scratch using PyTorch and fastai, trained on the MNIST dataset to classify handwritten digits (3s vs 7s).

## What This Project Covers

- Representing images as tensors and visualizing pixel values
- Computing ideal average images using the pixel similarity approach
- Building a linear model with sigmoid activation from scratch
- Implementing stochastic gradient descent manually including forward pass, loss calculation, backward pass, gradient zeroing, and weight updates
- Achieving 97.4% validation accuracy after 20 training epochs
- Identifying uncertain predictions where the model is less confident

## Key Concepts Explored

- Tensors, broadcasting, and vectorized operations
- Loss functions versus metrics and why accuracy cannot be used as a loss
- The role of gradients and backpropagation in training
- The sigmoid activation function
- Mini-batch gradient descent

## Tools and Libraries

Python, PyTorch, fastai, Google Colab

## Results

The model achieves **97.4% validation accuracy** after 20 epochs of training, starting from random weights.
A digit classifier built from scratch using PyTorch and fastai, achieving 97.4% validation accuracy on MNIST.
