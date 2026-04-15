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

```python```
from sklearn.impute import SimpleImputer

num_imp = SimpleImputer(strategy="mean")
cat_imp = SimpleImputer(strategy="most_frequent")

### 3. Exploratory Data Analysis (EDA)
- Checked class distribution of loan approval  
- Visualized using pie charts and box plots  
- Identified:
  - Class imbalance  
  - Feature relationships  

---

### 4. Feature Engineering
- Separated:
  - Categorical features  
  - Numerical features  
- Prepared dataset for training  

---

### 5. Model Building
- Used Scikit-learn  
- Split data into training and testing sets  

```python
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)

### 6. Model Training & Evaluation
- Trained a classification model (e.g., Logistic Regression)  
- Evaluated using:
  - Accuracy  
  - Predictions comparison  

---

## 📈 Key Insights
- Credit score and income strongly influence loan approval  
- Data imbalance can affect model performance  
- Proper preprocessing improves prediction accuracy  

---

## 💡 Future Improvements
- Implement advanced models (Random Forest, XGBoost)  
- Handle class imbalance using SMOTE  
- Deploy as a web application (Flask / MERN)  
- Add real-time prediction interface  

---

## 🛠️ How to Run the Project

### Clone the repository:
```bash
git clone https://github.com/your-username/creditwise.git

### 6. Model Training & Evaluation
- Trained a classification model (e.g., Logistic Regression)  
- Evaluated using:
  - Accuracy  
  - Predictions comparison  

---

## 📈 Key Insights
- Credit score and income strongly influence loan approval  
- Data imbalance can affect model performance  
- Proper preprocessing improves prediction accuracy  

---

## 💡 Future Improvements
- Implement advanced models (Random Forest, XGBoost)  
- Handle class imbalance using SMOTE  
- Deploy as a web application (Flask / MERN)  
- Add real-time prediction interface  

---

## 🛠️ How to Run the Project

### Clone the repository:
```bash
git clone https://github.com/your-username/creditwise.git

### Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

### Run the notebook:
```bash
jupyter notebook credit_wise.ipynb

## 📌 Project Status
- ✅ Completed (Basic ML Pipeline)  
- 🚧 Scope for enhancements and deployment  

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📬 Contact
For any queries or suggestions, feel free to connect.
