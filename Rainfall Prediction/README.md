# Rainfall Prediction Using Machine Learning

This project predicts rainfall using weather-related features such as temperature, humidity, cloud cover, wind speed, and other meteorological variables. The model uses a Random Forest Classifier with hyperparameter tuning through GridSearchCV.

---

## 📁 Project Structure

Rainfall_Prediction/
│
├── Rainfall_Prediction.ipynb # Main Jupyter notebook
├── Rainfall 2.csv # Weather dataset
├── model.pkl # Saved trained model
├── requirements.txt # Python dependencies
└── README.md # Project documentation

markdown
Copy
Edit

---

## 🚀 Features

- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Machine learning pipeline using Random Forest
- Hyperparameter tuning with GridSearchCV
- Model evaluation with accuracy and confusion matrix
- Prediction on new/unknown data
- Saving and loading trained models

---

## 🗂 Dataset

- **File**: `Rainfall 2.csv`  
- **Features included**:  
  - `pressure`  
  - `dewpoint`  
  - `humidity`  
  - `cloud`  
  - `sunshine`  
  - `winddirection`  
  - `windspeed`  
  - `maxtemp`  
  - `mintemp`  
  - `rainfall` (target variable)

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
Move into the project folder:

bash
Copy
Edit
cd Rainfall_Prediction
Install the dependencies:

bash
Copy
Edit
pip install -r requirements.txt
🧪 Usage
Start Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Open Rainfall_Prediction.ipynb

Run the cells step by step to:

Load and explore data

Train the model

Tune hyperparameters

Evaluate performance

Save/load the trained model

Predict on new inputs

📊 Model Evaluation
Metrics reported include:

Accuracy

Precision

Recall

F1-score

Confusion matrix

📌 Future Improvements
Try additional classifiers (e.g., XGBoost, SVM)

Automate data updates with a weather API

Deploy as a web app using Streamlit or Flask

Improve feature selection methods




