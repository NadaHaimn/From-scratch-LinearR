# Linear Regression from Scratch in Python

A lightweight implementation of a linear regression model using Python and gradient descent, built entirely from scratch. This project demonstrates the core concepts of linear regression, such as model formulation, gradient-based optimization, and performance evaluation, without using high-level machine learning libraries.

## Overview

Linear regression is one of the simplest yet powerful machine learning algorithms. This project implements a linear regression model from scratch to learn how it works under the hood, with a focus on:
- **Manual gradient descent optimization**: Iteratively updating weights and bias using computed gradients.
- **Loss function**: Minimizing the Mean Squared Error (MSE) to improve model accuracy.
- **Visualization**: Graphical representation of the fitted regression line and convergence of the loss function over time.

## Features

- **Custom Linear Regression Model**: Implements a basic linear regression model without using `scikit-learn` or other pre-built libraries.
- **Gradient Descent Optimizer**: A manual implementation of gradient descent for optimizing the model parameters.
- **Loss Function**: Mean Squared Error (MSE) is used as the objective function.
- **Visualization**: Generates plots to visualize the model fit and the reduction in loss over epochs.
- **Efficient Numpy Operations**: Leveraging vectorized operations for faster execution.
