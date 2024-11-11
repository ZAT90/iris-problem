# Iris Flower Classification Problem

This project uses a Jupyter Notebook to classify iris flowers (Setosa, Versicolor, Virginica) based on sepal and petal dimensions using logistic regression.

## Contents

[Overview](#overview)

[Features](#features)

[Usage](#usage)

[Dependencies](#dependencies)

[Results](#results)


## OverView
The goal of this project is to build a classification model for predicting the species of iris flowers. Using logistic regression, the model classifies flowers based on four physical measurements. The notebook includes data loading, model training, and evaluation with accuracy, a confusion matrix, and a classification report.

## Features
- Logistic Regression: Simple, interpretable model for multiclass classification.
- Metrics: Includes accuracy, confusion matrix, and classification report for a thorough evaluation.
- Data Visualization: Confusion matrix visualized with Seaborn heatmap.

## Usage
- Load and preprocess the Iris dataset.
- Split the data into training and testing sets.
- Train a logistic regression model.
- Evaluate the model and view results.

## Dependencies
```
pandas
seaborn
matplotlib
scikit-learn
```
## Results
- Accuracy: Overall performance of the model on test data.
- Confusion Matrix: Displays correct and incorrect predictions across classes.
- Classification Report: Provides precision, recall, and F1-score for each species.

### Sample Output
```
Accuracy: 100.00%

Confusion Matrix:
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]] 

Classification Report:
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30
```

