# Gradient Descent
## Introduction
Gradient descent is an optimization algorithm that is widely used in machine learning and deep learning. It is used to find the minimum of a differentiable function, often called the "cost" or "loss" function, which represents the error between the predictions of a model and the actual target values.
In the context of linear regression, the goal is to find the best-fitting line that minimizes the squared errors between the predicted values and the actual values. The cost function for linear regression is the residual sum of squares (RSS), which measures the squared difference between the predicted and actual values
## Optimization Algorithm for Linear Regression  

1. Define the loss function, which is the residual sum of squares (RSS) divided by 2:

   $$L(\boldsymbol{\beta}) = \frac{1}{2} \sum_{i=1}^n (y_i - \beta_0 - \sum_{j=1}^{p} {\beta_j x_{ij}})^2$$

2. Calculate the partial derivatives of the loss function with respect to the coefficients:

   $$\frac{\partial L}{\partial \beta_0} = \sum_{i=1}^{n}(\beta_0 + \sum_{j=1}^{p} {\beta_j x_{ij}} - y_{i})$$
   
   $$\frac{\partial L}{\partial \beta_j} = \sum_{i=1}^{n}(\beta_0 + \sum_{j=1}^{p} {\beta_j x_{ij}} - y_{i})x_{ij},  j=1 \dots p$$

3. Initialize the learning rate, model parameters, maximum number of training steps, and threshold. Then, iteratively update the coefficients using the following formula:

   $$\beta_j = \beta_j - \gamma \frac{\partial L}{\partial \beta_j}, j=0 \dots p$$

   The iteration continues until the maximum number of training steps is reached or the change in loss between two training steps is below the threshold.

4. Return the learned coefficients, which define the best-fitting line.

## Data
The house price data is used for predicting the price.
