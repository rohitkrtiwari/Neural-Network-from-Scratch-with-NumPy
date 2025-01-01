# Neural Network from Scratch with NumPy


Implementation of a simple neural network for digit classification using NumPy, built entirely from scratch with detailed mathematical explanations

This repository contains a step-by-step implementation of a simple neural network built from scratch using only NumPy and mathematical principles. The concepts were inspired by the YouTube tutorial by <b> Samson Zhang </b>.

## Features

<ol>
  <li>Minimal Dependency</li>
  <ul><li>Built entirely with NumPy, focusing on understanding the core principles of neural networks without relying on external frameworks like TensorFlow or PyTorch. </li></ul>
  
  <li>Fully Customizable Neural Network:</li>
  <ul><li>A simple architecture with one hidden layer, using ReLU activation for non-linearity and softmax activation for multi-class classification.</li></ul>

  <li>From Scratch Implementation:</li>
  <ul><li>Core functions such as forward propagation, backward propagation, and gradient descent are implemented step-by-step to deepen conceptual understanding.</li></ul>

  <li>Efficient Data Preprocessing:</li>
  <ul><li>Reads data directly from CSV files, normalizes inputs to the range [0, 1], and splits the dataset into training and development sets.</li></ul>

  <li>Modular Code:</li>
  <ul><li>Functions are modular, making it easy to modify the network architecture, activation functions, or optimization techniques.</li></ul>

  <li>Metrics and Performance Evaluation:</li>
  <ul><li>Includes utility functions for calculating accuracy and predictions, along with regular performance updates during training.</li></ul>

  <li>Beginner-Friendly Explanations:</li>
  <ul><li>The code is annotated with comments and supplemented by markdown cells in the notebook to explain each concept in detail.</li></ul>
</ol>



## Mathematical Concepts
This section provides detailed mathematical explanations for the neural network components and operations.

<ol>
  <li>Data Representation</li>
  <ul><li>Input Data: The input is a flattened vector of 784 dimensions (28x28 pixel grayscale images). </li></ul>
  <ul><li>Labels: Labels are integers representing digit classes (0-9) and are converted to one-hot encoded vectors for training.</li></ul>
  
  <li>Forward Propogation:</li>
  Forward propagation calculates the output of the network for a given input
  <ul><li>A simple architecture with one hidden layer, using ReLU activation for non-linearity and softmax activation for multi-class classification.</li></ul>
