# Simple-Linear-Regression-on-Housing-Prices-
# 🏠 House Price Prediction using Simple Linear Regression

## 📌 Project Overview

This project focuses on predicting house prices using a **Machine Learning Linear Regression model**.

The model is trained on a housing dataset and learns the relationship between different house features such as income, number of rooms, house age, location, etc., to predict the house price.

The project includes:
- Data loading
- Data preprocessing
- Feature selection
- Data normalization
- Model training
- House price prediction
- Model evaluation


---

## 🎯 Objective

Build a Linear Regression model that can predict housing prices based on different features.

---

## 📂 Dataset

Dataset used:

**California Housing Dataset** (from Scikit-learn)

Features:

| Feature | Description |
|---|---|
| MedInc | Median income of residents |
| HouseAge | Average age of houses |
| AveRooms | Average number of rooms |
| AveBedrms | Average bedrooms |
| Population | Area population |
| AveOccup | Average occupants per household |
| Latitude | Location latitude |
| Longitude | Location longitude |

Target:

**Price** → House price value

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


---

## ⚙️ Project Workflow
Dataset Loading
|
↓
Data Cleaning
|
↓
Exploratory Data Analysis
|
↓
Feature Selection
|
↓
Feature Scaling
|
↓
Train-Test Split
|
↓
Linear Regression Model
|
↓
Prediction
|
↓
Model Evaluation


---

## 📊 Data Preprocessing

Performed following preprocessing steps:

- Checked missing values
- Analysed feature correlation
- Selected important features
- Applied StandardScaler for normalization


---

## 🤖 Machine Learning Model

Algorithm Used:

**Simple Linear Regression**

Formula:
Price = b0 + b1X1 + b2X2 + ... + bnXn


Where:

- Price = Predicted house price
- X = Input features
- b = Model coefficients


---

## 📈 Model Evaluation

The model performance is evaluated using:

### Mean Absolute Error (MAE)

Measures average prediction error.

### Mean Squared Error (MSE)

Measures squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Shows model prediction accuracy.

### R² Score

Shows how well the model explains price variation.


---

## 🔮 House Price Prediction Example

Input:
MedInc = 8.5
HouseAge = 25
AveRooms = 7
AveBedrms = 1
Population = 300
AveOccup = 2
Latitude = 40
Longitude = -120

Output:
Predicted House Price: 3.45

---

## 📁 Project Structure
House-Price-Prediction/
│
├── Housing_Price_Prediction.ipynb
│
├── README.md
│
└── requirements.txt

---

## 🚀 How to Run Project

### 1. Clone Repository
git clone <your-github-repository-link>

### 2. Install Required Libraries
pip install -r requirements.txt

### 3. Open Jupyter Notebook
jupyter notebook

Run all cells in:
Housing_Price_Prediction.ipynb

---

## 📌 Requirements

Create `requirements.txt`
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter

---

## ✅ Conclusion

The Linear Regression model successfully predicts house prices using multiple housing features.

This project demonstrates a complete Machine Learning workflow including data preprocessing, model building, evaluation, and prediction.


---

