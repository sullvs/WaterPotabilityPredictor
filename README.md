# WaterPotabilityPredictor

A machine learning project focused on predicting water potability to ensure safe drinking water amidst rising pollution. By leveraging algorithms like Support Vector Machine, Decision Tree, and K-Nearest Neighbor, this project aims to classify water samples as potable or non-potable based on key water quality indicators.

## Introduction
Access to potable water is essential, yet pollution continues to threaten water quality globally. This project provides a machine learning-based solution to predict water potability, helping to ensure safer water for consumption.

## Dataset

The dataset includes various water quality metrics essential for determining potability, such as pH, hardness, solids, and more. An imbalanced dataset was addressed using SMOTE to improve model performance.

## Features

The following features are considered in predicting water potability:

pH
Hardness
Solids
Chloramines
Sulfate
Conductivity
Organic Carbon
Trihalomethanes
Turbidity


## Methodology

### Data Preprocessing:
Handled data imbalance using SMOTE (Synthetic Minority Oversampling Technique).
Split data into training (70%) and testing (30%) sets.

### Algorithms Used:
Support Vector Machine (SVM)
Decision Tree (DT)
K-Nearest Neighbor (KNN)

### Hyperparameter Tuning:
Used Stratified Cross-Validation (k=10) with GridSearch for optimal parameters.

### Feature Selection:
Applied Sequential Feature Selection for refining model input.

### Ensemble Learning:
Combined models for better generalization and accuracy.

### Results

The Decision Tree model achieved the highest accuracy at 73.75%, followed by SVM and KNN. This model is a promising tool for early potability assessment.

