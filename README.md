# Feature Engineering: Employee Attrition Analysis

## Overview

This project analyzes employee attrition data to predict which employees are most at risk of leaving the company. Several machine learning models are trained and evaluated, including Random Forest, Logistic Regression, and Support Vector Machine classifiers. The goals are to identify key drivers of attrition, test predictive capabilities on unseen data, and evaluate model performance.

## Data

The dataset contains employee information from a fictional company, including demographics, job role, metrics of satisfaction in various areas, travel requirements, compensation, tenure and history of promotions, etc.

The target variable is a binary indicator of whether the employee left the company voluntarily (Attrition_Yes) or not.

## Methodology

The general methodology followed:
1. Exploratory data analysis and visualizations
2. Feature engineering - encoding categoricals, scaling numerics, etc.
3. Train-test split
4. Building classification models with hyperparameter tuning 
5. Model evaluation on test set using AUC-ROC, accuracy, etc.

## Models

* Random Forest Classifier
* Logistic Regression
* Support Vector Classifier  

Preprocessing consisted of:
* One hot encoding categorical variables
* Creating new features like tenure ratios
* Scaling numerical features  

Models were optimized for AUC-ROC using hyperparameters like n_estimators and C values.
