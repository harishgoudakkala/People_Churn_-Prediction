# Customer Churn Prediction & Analysis

A machine learning project that analyzes telecom customer data and predicts customer churn using Python and Scikit-learn.

## Overview

The project follows an end-to-end machine learning workflow:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding and scaling
- Model training
- Model evaluation and comparison

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The project uses the **Telco Customer Churn** dataset, containing customer demographics, services, contract details, billing information, and churn status.

**Target Variable:** `Churn` (`Yes` / `No`)

## Workflow

1. **Data Cleaning**  
   Convert data types, handle missing values, remove zero-tenure records, and drop `customerID`.

2. **Exploratory Data Analysis**  
   Analyze churn patterns across demographics, services, contracts, payment methods, and billing information.

3. **Preprocessing**  
   Encode categorical features and standardize numerical features.

4. **Model Training**  
   Train and compare:
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
   - AdaBoost
   - Gradient Boosting

5. **Model Evaluation**  
   Evaluate models using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix
   - ROC-AUC

## Project Structure

```text
customer-churn-prediction-ml/
├── Churn_EDA_&_ML.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```

## How to Run

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd customer-churn-prediction-ml
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the Project

Open `Churn_EDA_&_ML.ipynb` and run the cells sequentially from top to bottom.

## Key Learning

- Python for data analysis
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature scaling
- Classification algorithms
- Ensemble learning
- Model evaluation and comparison

## Author

**Akkala Harish Goud**

[GitHub](https://github.com/harishgoudakkala) • [LinkedIn](https://www.linkedin.com/in/akkala-harish-goud-916bb1242/)
