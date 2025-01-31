# Logistic Regression Model



# This repository contains a Jupyter Notebook implementing logistic regression using Python. The model is trained on a synthetic dataset generated using make_classification from sklearn.datasets.

## Dataset

The dataset consists of:

1000 samples

10 features

2 classes (binary classification)

Generated using make_classification with random_state=15

## Implementation Steps

Import necessary libraries: pandas, numpy, matplotlib, seaborn, and scikit-learn.

Generate dataset: Using make_classification with 1000 samples and 10 features.

Exploratory Data Analysis (EDA):

Visualize feature distributions

Analyze class balance

## Model Training:

Split dataset into training and testing sets

Train a logistic regression model using sklearn.linear_model.LogisticRegression

Hyperparameter Tuning & Cross-Validation:

Perform hyperparameter tuning using GridSearchCV and RandomizedSearchCV

Compare accuracy before and after tuning

Accuracy without hyperparameter tuning: 91%

Accuracy with GridSearchCV: 92%

Accuracy with RandomizedSearchCV: 92.6%

Model Evaluation:

Predict on test data

Calculate accuracy, confusion matrix, and classification report



# GridSearchCV vs. RandomizedSearchCV

GridSearchCV: Tries all possible hyperparameter combinations, leading to more precise tuning but higher computation time.

RandomizedSearchCV: Randomly selects a subset of hyperparameter combinations, making it faster and more efficient while still providing good results.

## Results

Model accuracy and performance metrics are displayed at the end of the notebook.

Graphs and heatmaps provide a clear understanding of model behavior.

Hyperparameter tuning improved model accuracy:

## GridSearchCV: 92%

## RandomizedSearchCV: 92.6%
