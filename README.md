# P260_Trailblazers_Predicta1.0
Problem 2 -Trained Weather Condition Prediction Model

This repository contains a trained machine learning model for predicting weather conditions based on various meteorological features. The model is built using a Support Vector Machine (SVM) classifier and has been fine-tuned using GridSearchCV for optimal performance.

Model Description

Model Type: Support Vector Machine (SVM)
Training Data: Meteorological data including temperature, wind speed, pressure, humidity, and more.
Target Variable: Weather condition (condition_text)
Feature Selection: SelectKBest with ANOVA F-value
Data Preprocessing:
Encoding of categorical variables
Standard scaling of numerical features
Handling of class imbalance using SMOTE
Performance

Best Parameters:

C: 10
gamma: 0.1
kernel: 'rbf'
selector__k: 10
Test Accuracy: 0.878 
