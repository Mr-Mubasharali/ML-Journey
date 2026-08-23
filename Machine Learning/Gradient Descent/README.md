# Gradient Descent

This is my practice and learning work on **Gradient Descent** in Machine Learning.

I learned how Gradient Descent helps a machine learning model find better parameter values by reducing the loss step by step.

## What is Gradient Descent?

Gradient Descent is an optimization algorithm used to reduce the loss of a machine learning model.

It starts with some initial parameter values and updates them step by step in the direction that reduces the loss.

In simple words:

> Make a prediction → calculate the error → find the direction to reduce the error → update the parameters → repeat.

## Why is Gradient Descent Used?

A machine learning model needs to find the best parameter values so that its predictions are as close as possible to the actual values.

Gradient Descent helps the model find these values by minimizing the loss function.

## What is a Loss / Cost Function?

A loss function tells us **how wrong our model's predictions are**.

- Small loss → predictions are closer to actual values
- Large loss → predictions are farther from actual values

Gradient Descent tries to reduce this loss.

## What is a Derivative?

A derivative tells us how much the loss changes when a parameter changes.

It also helps us understand which direction we should move a parameter to reduce the loss.

## What is a Gradient?

A gradient is basically a collection of derivatives for the model's parameters.

It tells us the direction in which the loss increases.

Gradient Descent moves in the **opposite direction of the gradient** to reduce the loss.

## What is Learning Rate?

The learning rate controls **how big each parameter update should be**.

- Small learning rate → slower learning
- Large learning rate → faster updates, but it may overshoot the minimum
- Good learning rate → stable and efficient learning

## How Does Gradient Descent Work?

The basic process is:

1. Start with initial parameter values.
2. Make predictions.
3. Calculate the loss.
4. Calculate the gradients.
5. Update the parameters.
6. Repeat the process until the loss becomes small or the model reaches a suitable point.

## Gradient Descent in Linear Regression

In Linear Regression, Gradient Descent can be used to find better values for the **slope (m)** and **intercept (b)**.

The model first makes predictions using the current values of `m` and `b`.

Then Gradient Descent calculates how these values should be changed to reduce the loss.

This process continues for multiple iterations until the model reaches suitable parameter values.

## Types of Gradient Descent

### 1. Batch Gradient Descent

Batch Gradient Descent uses the **complete training dataset** to calculate the gradient before updating the parameters.

It can give stable updates but can be slower for large datasets.

### 2. Stochastic Gradient Descent (SGD)

Stochastic Gradient Descent uses **one training example at a time** to calculate the gradient and update the parameters.

It is usually faster for large datasets but the updates can be noisy.

### 3. Mini-Batch Gradient Descent

Mini-Batch Gradient Descent uses a **small group of training examples** to calculate the gradient and update the parameters.

It combines some advantages of Batch Gradient Descent and Stochastic Gradient Descent.

## What I Practiced

- Calculating predictions
- Calculating loss
- Calculating gradients
- Updating parameters
- Understanding derivatives
- Using a learning rate
- Running Gradient Descent for multiple iterations
- Applying Gradient Descent to Linear Regression
- Implementing Gradient Descent from scratch

## Implementation

I implemented Gradient Descent from scratch using **Python and NumPy** to understand how it works internally instead of only using a built-in Machine Learning library.

## Tools Used

- Python
- NumPy
- Jupyter Notebook

## Conclusion

This practice helped me understand how a machine learning model learns its parameters by reducing the loss step by step.

It also helped me understand the connection between **loss, derivatives, gradients, learning rate, and parameter updates**.

This is part of my **Machine Learning Journey**.