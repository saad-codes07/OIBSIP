# Level 2 Task 2: Wine Quality Prediction

## Overview
This project trains and benchmarks multiple classification models (**Random Forest**, **SGD Classifier**, and **Support Vector Classifier**) to predict wine quality based on physicochemical attributes.

## Checklist Deliverables
* **EDA & Class Imbalance Analysis:** Identified skewness in raw 3–8 quality ratings.
* **Feature Engineering:** Binary binning into Bad/Average ($\le 6$) vs. Good ($\ge 7$) categories.
* **Stratified Pipeline:** Standardized scaling with stratified train/test split.
* **Model Benchmarking:** Evaluated Random Forest, SGD, and SVC using accuracy, precision, recall, F1-score, and confusion matrices.
* **Feature Importance:** Plotted top chemical drivers (Alcohol, Volatile Acidity, Sulphates).
* **Deployment Insights:** Selected Random Forest as optimal production model for automated cellar quality sorting.
