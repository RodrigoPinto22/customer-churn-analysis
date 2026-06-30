# Telco Customer Churn Prediction

An end-to-end statistical analysis of customer churn using the IBM Telco Customer Churn dataset.

The primary objective of this project is to understand the factors associated with customer churn through Exploratory Data Analysis (EDA) and Logistic Regression while emphasizing statistical interpretation rather than maximizing predictive performance.

## Project Objectives

- Perform data cleaning and preprocessing
- Conduct Exploratory Data Analysis (EDA)
- Build and interpret a Logistic Regression model
- Explain coefficients and odds ratios
- Evaluate model performance using classification metrics
- Discuss model assumptions and limitations
- Translate statistical findings into business recommendations

## Dataset

- **Dataset:** IBM Telco Customer Churn
- **Target variable:** `Churn`

The dataset contains demographic information, customer account details, subscribed services, and billing information for a telecommunications company.

## Methods

- Data Cleaning
- Exploratory Data Analysis
- Feature Encoding
- Logistic Regression
- Odds Ratio Interpretation
- Confusion Matrix
- Accuracy, Precision, Recall, F1-score
- ROC Curve and ROC-AUC
- Threshold Selection
- Business Recommendations

## Key Findings

- Customers with month-to-month contracts exhibited substantially higher churn than customers with longer-term contracts.
- Fiber Optic internet service was strongly associated with customer churn, even after controlling for other predictors.
- Customer tenure was negatively associated with churn, indicating that longer-term customers were less likely to leave.
- The project illustrates how relationships observed during exploratory analysis may change after accounting for multiple variables in a Logistic Regression model.

## Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Repository Structure

```
├── customer_churn.ipynb
├── README.md
└── requirements.txt
```

## Learning Outcomes

This project focuses on understanding the statistical reasoning behind Logistic Regression rather than treating it as a black-box machine learning algorithm. It demonstrates how exploratory analysis, model interpretation, and performance evaluation can be combined to support data-driven decision making.
