# Iris Classification using Naive Bayes

A beginner machine learning project that uses Gaussian Naive Bayes to classify Iris flowers into three species based on their physical measurements.

## Objective

The objective of this project is to understand and practice the complete machine learning workflow for a multiclass classification problem using the Naive Bayes algorithm.

## Dataset

The project uses the **Iris dataset**, loaded directly from the UCI Machine Learning Repository.

### Dataset Details

- **Total samples:** 150
- **Features:** 4
- **Classes:** 3
- **Target:** `species`

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Classes

- Iris-setosa
- Iris-versicolor
- Iris-virginica

The dataset is loaded directly from an online CSV source and is not included in this repository.

## Machine Learning Workflow

```text
Online Dataset
      ↓
Data Exploration
      ↓
Missing Value Check
      ↓
Class Distribution
      ↓
Feature / Target Separation
      ↓
Train-Test Split
      ↓
Gaussian Naive Bayes
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Confusion Matrix
      ↓
Visualization
      ↓
Model Saving