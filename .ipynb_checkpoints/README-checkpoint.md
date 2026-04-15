# 📊 CreditWise – Loan Approval Prediction System

## 🚀 Overview
**CreditWise** is a machine learning project that predicts whether a loan application will be approved or not based on applicant details.  
The project focuses on data preprocessing, exploratory data analysis (EDA), and building a predictive model using real-world financial data.

---

## 🎯 Objective
The main goal of this project is to:
- Analyze loan applicant data  
- Handle missing values effectively  
- Perform data visualization and extract insights  
- Build a classification model to predict loan approval status  

---

## 🧠 Tech Stack
- **Programming Language:** Python  
- **Libraries Used:**
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

## 📂 Dataset
- Dataset: `loan_approval_data.csv`  
- Key features include:
  - Applicant Income  
  - Credit Score  
  - Loan Amount  
  - Employment Status  
  - Loan Approval Status (Target Variable)  

---

## ⚙️ Project Workflow

### 1. Data Loading
- Imported dataset using Pandas  
- Initial inspection using:
  - `head()`  
  - `info()`  
  - `describe()`  

---

### 2. Data Preprocessing
- Handling Missing Values:
  - Numerical columns → filled using **mean**
  - Categorical columns → filled using **most frequent value**

```python
from sklearn.impute import SimpleImputer

num_imp = SimpleImputer(strategy="mean")
cat_imp = SimpleImputer(strategy="most_frequent")