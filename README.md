# neural-networks-unplugged
Introduction
Artificial Neural Networks (ANNs) are one of the most fundamental concepts in the field of machine learning and artificial intelligence. They are inspired by the structure and functionality of the human brain and are designed to recognize patterns, make predictions, and solve complex computational problems.

This project is aimed at learning the inner workings of an ANN by implementing it from scratch using Python. Unlike using pre-built libraries such as TensorFlow or PyTorch, building an ANN manually helps solidify understanding of key concepts like forward propagation, backward propagation, activation functions, and optimization algorithms. The project is solely for learning purposes, focusing on the foundational elements that make up a neural network.

Objectives:
To understand the mechanics of how neural networks work.

To implement key components such as layers, activation functions, loss functions, and optimizers.

To gain hands-on experience in building and training a model from scratch.

Steps to Build the ANN
Define the Problem and Dataset

Focus on a regression problem.

Prepare the dataset by normalizing features and splitting it into training and testing sets.

Design the Network Architecture

Choose the number of input features, hidden layers, and one output neuron for regression.

Use activation functions such as ReLU for hidden layers and a linear activation for the output layer.

Initialize Weights and Biases

Randomly initialize weights and biases for all layers.

Ensure appropriate initialization to avoid vanishing or exploding gradients.

Implement Forward Propagation

Compute the weighted sum of inputs and apply activation functions for each layer.

Produce a continuous output value suitable for regression tasks.

Define the Loss Function

Use Mean Squared Error (MSE) as the loss function.

Calculate the average squared difference between predicted and actual values.

Implement Backward Propagation

Derive gradients of the MSE loss function with respect to weights and biases.

Use the chain rule to propagate errors backward through the network.

Implement gradient descent to update weights and biases. Include detailed comments or explanations on how gradients are
computed for each layer.

Train the Network

Iterate through multiple epochs, performing forward and backward propagation for each batch of data.

Adjust weights using the gradients computed during backpropagation.

Monitor training loss to ensure the model is learning.
