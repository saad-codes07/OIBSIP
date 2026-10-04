# Level 2 Task 3: Credit Card Fraud Detection Pipeline

## Overview
This project builds a real-time machine learning pipeline to detect fraudulent financial transactions from an imbalanced dataset ($0.5\%$ positive fraud cases).

## Features Implemented
* **Class Imbalance Analysis:** Analyzed skewed transaction distribution and log-scaled transaction amounts.
* **Imbalance Handling:** Applied **SMOTE (Synthetic Minority Over-sampling Technique)** and balanced class weighting.
* **Stratified Pipeline:** Implemented stratified train-test splits preserving fraud ratios.
* **Model Training & Evaluation:** Benchmarked **Logistic Regression** and **Random Forest** using **Precision**, **Recall**, **F1-Score**, and **AUC-ROC**.
* **Feature Importance:** Extracted top signal features driving fraud predictions.
* **Scalability Architecture:** Documented streaming architecture requirements for serving 1 million transactions/hour.