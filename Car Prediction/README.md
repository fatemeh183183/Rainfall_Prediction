# 🚗 Car Price Prediction Project

This machine learning project predicts the **selling price** of used cars based on several features such as manufacturing year, fuel type, transmission, kilometers driven, and more.

The model helps estimate the fair market value of a car based on historical data, which is useful for both buyers and sellers.

---

## 📁 Dataset

The dataset contains the following columns:

- `Car_Name`
- `Year`
- `Selling_Price`
- `Present_Price`
- `Kms_Driven`
- `Fuel_Type`
- `Seller_Type`
- `Transmission`
- `Owner`

---

## 📌 Objective

To build and compare different regression models to predict the **Selling Price** of a car.  
Models used:

- Linear Regression
- Lasso Regression

---

## 🧪 ML Pipeline Steps

1. Data loading and exploration
2. Data preprocessing (handling categorical data, missing values, feature scaling)
3. Feature engineering
4. Model training and evaluation
5. Comparison of model performance

---

## 🛠️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
requirements.txt:


numpy
pandas
seaborn
matplotlib
scikit-learn
📊 Evaluation Metrics
R² Score
