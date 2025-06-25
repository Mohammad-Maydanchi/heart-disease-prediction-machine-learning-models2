# Heart Disease Prediction Using Machine Learning Models 2
This repository contains the implementation and results of the published paper:

"A Comparison of Methods for Predicting Heart Disease: Neural Network, XGBoost, Gradient Boost, Logistic Regression, and SVM"
# Published in IEEE SoutheastCon 2025.

# Objective
To evaluate and compare the performance of various supervised learning models in predicting heart disease using health-related survey data from the CDC.
This paper presents the second group of machine learning models evaluated on this dataset. A comparison is provided at the end of the paper between the results of this study and a previous paper that examined other classifiers on the same dataset.
# Models Used
XGBoost

Gradient Boost

Logistic Regression

Neural Network

Support Vector Machine (SVM)

# Dataset
Source: Behavioral Risk Factor Surveillance System (BRFSS), CDC

Size: 320,000+ samples

Target Variable: HeartDisease (binary classification)

Handling Imbalance: SMOTE (Synthetic Minority Over-sampling Technique)

# Evaluation Metrics
F1-score

Area Under the ROC Curve (AUC)

Training Runtime

# Key Findings
XGBoost achieved the highest F1-score.

Logistic Regression had the best AUC and fastest runtime.

SVM showed the lowest performance across most metrics.

Models performed differently due to dataset imbalance and feature interactions.

# Tools & Libraries
Python

Scikit-learn

XGBoost

Keras (for Neural Network)

Pandas, NumPy, Seaborn, Matplotlib
