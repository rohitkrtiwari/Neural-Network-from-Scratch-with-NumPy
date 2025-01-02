# Neural Network from Scratch with NumPy


Implementation of a simple neural network for digit classification using NumPy, built entirely from scratch with detailed mathematical explanations

This repository contains a step-by-step implementation of a simple neural network built from scratch using only NumPy and mathematical principles. The concepts were inspired by the YouTube tutorial by <b> Samson Zhang </b>.

## Features

<ol>
  <li> <b> Minimal Dependency</b></li>
  <ul><li>Built entirely with NumPy, focusing on understanding the core principles of neural networks without relying on external frameworks like TensorFlow or PyTorch. </li></ul>

  <br>
  <li><b>Fully Customizable Neural Network:</b></li>
  <ul><li>A simple architecture with one hidden layer, using ReLU activation for non-linearity and softmax activation for multi-class classification.</li></ul>

  <br>
  <li><b>From Scratch Implementation:</b></li>
  <ul><li>Core functions such as forward propagation, backward propagation, and gradient descent are implemented step-by-step to deepen conceptual understanding.</li></ul>

  <br>
  <li><b>Efficient Data Preprocessing:</b></li>
  <ul><li>Reads data directly from CSV files, normalizes inputs to the range [0, 1], and splits the dataset into training and development sets.</li></ul>

  <br>
  <li><b>Modular Code:</b></li>
  <ul><li>Functions are modular, making it easy to modify the network architecture, activation functions, or optimization techniques.</li></ul>

  <br>
  <li><b>Metrics and Performance Evaluation:</b></li>
  <ul><li>Includes utility functions for calculating accuracy and predictions, along with regular performance updates during training.</li></ul>

  <br>
  <li><b>Beginner-Friendly Explanations:</b></li>
  <ul><li>The code is annotated with comments and supplemented by markdown cells in the notebook to explain each concept in detail.</li></ul>
</ol>



## Mathematical Concepts
This section provides detailed mathematical explanations for the neural network components and operations.

<ol>
  <li><b>Data Representation: </b></li>
  <ul><li>Input Data: The input is a flattened vector of 784 dimensions (28x28 pixel grayscale images). </li></ul>
  <ul><li>Labels: Labels are integers representing digit classes (0-9) and are converted to one-hot encoded vectors for training.</li></ul>

  <br>
  <li><b>Forward Propogation:</b></li>
  Forward propagation calculates the output of the network for a given input
  <ul><li><b>Hiddent Layers:</b> Z1 = W1.X + b1 </li>
      A1 = <a href="https://www.kaggle.com/code/dansbecker/rectified-linear-units-relu-in-deep-learning">ReLU(Z1)</a> <br>
      Here:
      <ul>
        <li>Z1: Weighted sum of inputs</li>
        <li>A1: Activation of hidden layer neurons using ReLU:</li>
        ReLU(z) = max(0, z)
      </ul>
      <li><b>Output Layer: </b>Z2 = W2.A1 + b2</li>
      A2 = <a href = "https://www.singlestore.com/blog/a-guide-to-softmax-activation-function/">softmax(z2)</a>  <br>
  </ul>
    
  <br>
  <li><b>Loss Function: </b></li>
  The corss-entropy loss is used to quantify the difference between predicted probabilities and true labels:
  
  <ul>
    
  </ul>
      
