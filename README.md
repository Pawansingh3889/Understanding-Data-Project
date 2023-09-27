# Project Title: Predicting Customer Churn for Lu's Communication

## Introduction

This project aims to predict customer churn for Lu's Communication, a telecommunications company. Utilizing data science techniques, we'll analyze various features like customer demographics, usage behavior, and service packages to predict which customers are most likely to churn.

---

## Data Preparation

### Data Collection

- The dataset, provided by Lu's Communication, is available in two formats: `Group1.csv` and `Group2.csv`.
- The dataset contains potential issues like outliers, missing values, and irrelevant information.

### Initial Review

- A peek into the structure of the dataset.
- Summary statistics to understand feature distributions.

### Data Transformation

- Reformat data for use in machine learning algorithms.

---

## Exploratory Data Analysis (EDA)

- Investigate the applicability of each feature to the problem of predicting churn.
- Explore how features are inter-related.
- Evaluate the presence and impact of outliers.

---

## Data Pre-Processing

- Deal with outliers through techniques like winsorizing or log transformation.
- Handle missing values through imputation.
- Normalize or standardize features with different scales.
- Feature selection based on importance.

---

## Developing and Testing Machine Learning Models

- Choose appropriate models to tackle the problem (e.g., logistic regression, decision trees, etc.).
- Test at least four different models to compare performance.
  
---

## Conclusion

- Summarize key findings.
- Identify the best machine learning model and its performance metrics.

---

### Dataset Features Overview

- **customer_id**: Unique ID for each customer.
- **gender**: Male or Female.
- **location**: Customer location.
- **partner**: Has partner (1=Yes, 0=No).
- **dependents**: Has dependents (1=Yes, 0=No).
- **senior**: Senior citizen (1=Yes, 0=No).
- **tenure**: Years with the company.
- **monthly_cost**: Monthly charge for the service.
- **package**: Various service packages (Package 1 to Package 4).
- **survey**: Customer service rating (0 to 10).
- **Class**: Churned (1) or not churned (0).
