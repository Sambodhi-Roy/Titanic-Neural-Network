# Titanic - Machine Learning from Disaster

This repository contains my solution for the Titanic Kaggle Competition, where I utilized a neural network with forward propagation to predict the survival of passengers on the Titanic.

## Overview

The Titanic competition challenges participants to predict the survival of passengers based on features like age, gender, and ticket class. I approached the problem by building a neural network model using the forward propagation algorithm.

## Approach

### Problem

Given a dataset with passenger details, the objective is to predict whether a passenger survived the disaster.

### Solution

I developed a neural network using the following steps:

1. **Data Preprocessing**:
   - Handled missing data (e.g., age, embarked).
   - Categorical features were encoded (e.g., gender and ticket class).
   - Numerical features were normalized to improve the model's performance.

2. **Neural Network**:
   - Implemented a multi-layer neural network from scratch using forward propagation.
   - The model was trained to minimize binary cross-entropy loss.
   - Parameters were optimized using gradient descent.

3. **Evaluation**:
   - The model was evaluated based on accuracy on the test set.
   - I fine-tuned hyperparameters like learning rate, network architecture, and more to improve performance.

### Why Neural Networks?

Neural networks can model complex, non-linear relationships between features, making them powerful tools for classification tasks. By implementing forward propagation, I was able to compute predictions efficiently and learn from the data.

## Learning Curves

Below are the learning curves showing the training and validation accuracy and loss over epochs:

![Training and Validation Accuracy](Model_Accuracy.png)  
![Training and Validation Loss](Model_Loss.png)

## Getting Started

To run the solution:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/titanic-neural-network.git
