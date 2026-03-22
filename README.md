# Data-Science-Analytics-Internship-tasks-1-5.
This repository contains all tasks completed as part of the Data Science & Analytics Internship at DevelopersHub Corporation. The tasks focus on data exploration, visualization, machine learning modeling, and performance evaluation using Python.

---

## Table of Contents

1. [Task 1: Exploring and Visualizing a Simple Dataset (Iris Dataset)](#task-1)
2. [Task 2: Credit Risk Prediction](#task-2)
3. [Task 3: Customer Churn Prediction (Bank Customers)](#task-3)
4. [Task 4: Predicting Insurance Claim Amounts](#task-4)
5. [Task 5: Personal Loan Acceptance Prediction](#task-5)

---

## Task 1: Exploring and Visualizing a Simple Dataset (Iris Dataset)

**Objective:**  
Understand how to read, summarize, and visualize a dataset (Iris Dataset).

**Approach:**  
- Loaded the dataset using pandas  
- Explored structure using `.shape`, `.columns`, `.head()`  
- Created scatter plots, histograms, and box plots using matplotlib and seaborn  

**Results & Insights:**  
- Observed relationships between petal and sepal features  
- Detected outliers and distribution patterns  
- Gained insights into feature variations across species

---

## Task 2: Credit Risk Prediction

**Objective:**  
Predict whether a loan applicant is likely to default on a loan (binary classification problem).

**Approach:**  
- Handled missing values using mode/median imputation  
- Explored features such as LoanAmount, ApplicantIncome, Education  
- Trained Logistic Regression and Decision Tree models  
- Evaluated using Accuracy, Confusion Matrix, ROC-AUC  

**Results & Insights:**  
- Class imbalance present (~82% good credit)  
- LoanAmount, ApplicantIncome, Education, PropertyArea influence credit risk  
- Models perform well on majority class; Decision Tree feature importance highlighted key factors

---

## Task 3: Customer Churn Prediction (Bank Customers)

**Objective:**  
Identify customers who are likely to leave the bank.

**Approach:**  
- Removed irrelevant columns (RowNumber, CustomerId, Surname)  
- Encoded categorical variables (Gender, Geography)  
- Conducted EDA: Age, Gender, Geography distributions vs Churn  
- Trained Logistic Regression and Decision Tree classifiers  
- Analyzed feature importance using Decision Tree  

**Results & Insights:**  
- Balance, Age, Geography, NumOfProducts are key factors affecting churn  
- Older customers or low balance customers more likely to leave  
- Banks can target retention strategies for at-risk customers

---

## Task 4: Predicting Insurance Claim Amounts

**Objective:**  
Estimate medical insurance claim amounts based on personal data (regression problem).

**Approach:**  
- Explored dataset (Age, BMI, Smoking status, Charges)  
- Visualized correlations between features and insurance charges  
- Trained Linear Regression model  
- Evaluated model performance using MAE and RMSE  

**Results & Insights:**  
- Age, BMI, and Smoking status strongly impact insurance charges  
- Regression model predicts charges with reasonable accuracy  
- Visualization revealed skewness and patterns in charges

---

## Task 5: Personal Loan Acceptance Prediction

**Objective:**  
Predict which customers are likely to accept a personal loan offer.

**Approach:**  
- Explored dataset (Age, Job, Marital Status, Education, Income)  
- Trained Logistic Regression and Decision Tree classifiers  
- Analyzed results to identify customer groups more likely to accept loans  

**Results & Insights:**  
- Higher income, certain job types, and married status increased loan acceptance likelihood  
- Models provide actionable insights for targeted marketing campaigns  
- Visualizations helped interpret demographic patterns

---

## Repository Structure
