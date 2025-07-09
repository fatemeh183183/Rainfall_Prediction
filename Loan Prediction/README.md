# 🏦 Loan Prediction ML Project

This project predicts whether a loan will be approved (`Loan_Status`) using customer data. It compares the performance of three machine learning models — **Random Forest**, **Logistic Regression**, and **Support Vector Machine (SVM)** — along with **hyperparameter tuning** using `GridSearchCV`.

---


## Dataset

The dataset contains anonymized information such as:

- Gender
- Marital Status
- Dependents
- Education
- Employment status
- Applicant & Coapplicant Income
- Loan Amount & Term
- Credit History
- Property Area
- **Target:** Loan_Status (Y/N)

---

## Features Implemented

### 🔍 Data Preprocessing
- Imputation:
  - Categorical: most frequent value
  - Numerical: median
- Encoding: One-hot encoding for categorical variables
- Scaling: StandardScaler for numerical values
- Train-Test split: 90/10 with stratification

### 📈 Models Used
- **Random Forest**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

###  Hyperparameter Tuning
Performed using `GridSearchCV` with 5-fold cross-validation.


## 📉 Evaluation Metrics
- **Accuracy**
- **Precision, Recall, F1-score**
- **Classification Report**
- **Confusion Matrix** *(optional)*
- **ROC-AUC** *(recommended as next step)*



