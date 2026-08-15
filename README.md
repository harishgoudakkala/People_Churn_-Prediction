# Customer Churn Prediction & Analysis

Machine learning project for analyzing telecom customer data and predicting customer churn using Python and Scikit-learn.

## Overview

This project covers the complete ML workflow:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding and scaling
- Model training and evaluation
- Comparison of multiple classification algorithms

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The project uses the **Telco Customer Churn** dataset containing customer demographics, services, contract details, charges, and churn status.

**Target:** `Churn` — `Yes` / `No`

## Workflow

1. **Data Cleaning** – Handle missing values, convert data types, remove zero-tenure records and `customerID`.
2. **EDA** – Analyze churn patterns across customer demographics, services, contracts, and payment methods.
3. **Preprocessing** – Apply categorical encoding and standardize numerical features.
4. **Modeling** – Train and compare five classification models:
   - KNN
   - Decision Tree
   - Random Forest
   - AdaBoost
   - Gradient Boosting
5. **Evaluation** – Compare models using Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC.

## Project Structure

```text
customer-churn-prediction-ml/
├── Churn_EDA_&_ML.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md

How to Run
git clone <your-repository-url>
cd customer-churn-prediction-ml
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook

Open Churn_EDA_&_ML.ipynb and run the cells sequentially.

Key Learning
Python-based data analysis
EDA and data visualization
Feature preprocessing
Classification algorithms
Ensemble learning
Model evaluation and comparison
Author

Akkala Harish Goud

GitHub | LinkedIn
