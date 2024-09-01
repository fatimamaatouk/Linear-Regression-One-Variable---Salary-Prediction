# Linear-Regression-One-Variable---Salary-Prediction
This repository contains a Python implementation of linear regression for predicting salaries based on years of experience. It demonstrates both gradient descent and the normal equation methods. The project is part of my journey to learn machine learning from scratch.

# Salary Prediction using Linear Regression

This notebook demonstrates how to implement linear regression in Python to predict salaries based on years of experience. It covers two approaches: Gradient Descent and Normal Equation.

## Dataset

The dataset used is `Experience-Salary.csv`, which contains two columns:

- `exp(in months)`: Years of experience
- `salary(in thousands)`: Corresponding salary

## Steps

1. **Data Loading and Preprocessing:**
   - Load the dataset using pandas.
   - Visualize the data using a scatter plot.
   - Scale the data (optional).
   - Add a column of ones for the intercept term.

2. **Gradient Descent:**
   - Implement the cost function to measure the error.
   - Implement the gradient descent algorithm to iteratively update the weights.
   - Train the model using the training data.
   - Plot the best fit line obtained using gradient descent.
   - Plot the error vs. training epoch graph.

3. **Normal Equation:**
   - Implement the normal equation to directly calculate the optimal weights.
   - Calculate the optimal weights.
   - Plot the best fit line obtained using the normal equation.

4. **Comparison:**
   - Compare the final weights and costs obtained using both methods.

## Requirements

- Python 3
- NumPy
- Pandas
- Matplotlib

## Usage

1. Upload the `Experience-Salary.csv` file to your Colab environment.
2. Run the notebook cells sequentially.
3. Observe the results and compare the performance of gradient descent and the normal equation.
