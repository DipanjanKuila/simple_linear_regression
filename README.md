# Simple Linear Regression

This repository contains a Jupyter Notebook implementing Simple Linear Regression to predict salaries based on years of experience. The notebook includes steps for data preprocessing, model training, and visualization of results.

## Dataset

The dataset used is `Salary_Data.csv`, which contains two columns:
- `YearsExperience`: The number of years of experience of the employee.
- `Salary`: The salary of the employee.

## Steps in the Notebook

1. **Importing Libraries**:
    - NumPy
    - Matplotlib
    - Pandas

2. **Loading the Dataset**:
    - The dataset is loaded using Pandas.
    - Features (`YearsExperience`) and target variable (`Salary`) are extracted.

3. **Splitting the Dataset**:
    - The dataset is split into training and test sets using `train_test_split` from scikit-learn.

4. **Training the Model**:
    - A Simple Linear Regression model is trained on the training set using `LinearRegression` from scikit-learn.

5. **Predicting Results**:
    - Predictions are made on both the test set and the training set.

6. **Visualization**:
    - Scatter plots are created to visualize the training and test set results.

7. **Single Prediction**:
    - An example prediction is made for the salary of an employee with 15 years of experience.

