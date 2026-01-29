# Project Name

# Credit Card Fraud Detection Using Machine Learning

# Project Summary

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to build a reliable classification model that can accurately identify fraudulent transactions from a highly imbalanced dataset. The project involves data preprocessing, exploratory data analysis, feature engineering, model building, and performance evaluation.

# Problem Statement

Credit card fraud is a major issue in the financial sector, leading to significant monetary losses every year. The challenge is to:

Detect fraudulent transactions accurately

Handle highly imbalanced data (very few fraud cases compared to normal transactions)

Minimize false positives while maximizing fraud detection

The objective is to build a machine learning model that can classify transactions as Fraudulent or Legitimate.

# Dataset Description

The dataset contains credit card transaction records

Features are numerical and anonymized for security reasons

# Target variable:

0 → Legitimate Transaction

1 → Fraudulent Transaction

# Data Manipulation & Preprocessing

The following data manipulation steps were performed:

✔️ Checked dataset shape and structure

✔️ Identified and handled missing values

✔️ Verified class imbalance in the target column

✔️ Performed exploratory data analysis (EDA)

✔️ Separated features and target variable

✔️ Split data into training and testing sets

✔️ Standardized/normalized features (if required)

# Machine Learning Techniques Used

Algorithm: Logistic Regression

Reason:

Works well for binary classification

Efficient and interpretable

Suitable as a baseline model for fraud detection

# Model Evaluation

The model was evaluated using:

✔️ Accuracy Score

✔️ Comparison between predicted and actual values

The focus was not only on accuracy but also on understanding model behavior due to class imbalance.

# Key Insights

 The dataset is highly imbalanced, with very few fraud cases

 Logistic Regression can detect fraud patterns reasonably well

 Accuracy alone is not sufficient for fraud detection problems

 Even a simple model can provide valuable insights when data preprocessing is done correctly

# Future Improvements

Use advanced models like Random Forest, XGBoost, or Neural Networks

Apply techniques like SMOTE to handle class imbalance

Evaluate model using Precision, Recall, F1-score, and ROC-AUC

Deploy the model as a web application or API

# Tools & Technologies

Python

NumPy

Pandas

Scikit-learn

Jupyter Notebook
