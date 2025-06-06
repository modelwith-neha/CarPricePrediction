# 🚗 Car Price Prediction – Regression Project

**Author**: Neha Tiwari  
**Objective**: Predict the selling price of used cars based on various features such as age, mileage, fuel type, and transmission type.  
**Problem Type**: Supervised Regression  
**Tools**: Python (Pandas, Scikit-learn, Matplotlib, Seaborn)

---

## 📌 Overview

This project aims to develop a regression model that accurately predicts the resale value of cars based on structured vehicle data. The dataset includes various attributes that influence car prices, such as brand, model, fuel type, kilometers driven, and number of previous owners.

---

## 🧾 Dataset Summary

- **Source**: data.csv  
- **Observations**: ~3000 rows  
- **Features**:
  - Car Name / Company
  - Year of Manufacture
  - Present Price
  - Kms Driven
  - Fuel Type
  - Transmission
  - Owner History
  - Seller Type
  - Selling Price (target variable)

---

## ⚙️ Workflow

### 1. 🧹 Data Preprocessing
- Handled missing values
- Converted categorical variables using Label Encoding
- Removed outliers in "Kms Driven"
- Created derived features like car age
- Dropped irrelevant columns (e.g., car name where not useful)

### 2. 📊 Exploratory Data Analysis (EDA)
- Distribution plots for numerical features
- Boxplots to analyze the impact of categorical variables on price
- Correlation matrix heatmap

### 3. 🧠 Model Building & Evaluation
- Split data into training and test sets (80/20)
- Algorithms tried:
  - Linear Regression
  - Ridge & Lasso Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - XGBoost Regressor

### 4. ✅ Best Performing Model
- **Random Forest Regressor** showed the best performance with:
  - R² Score (Test Set): 0.89+
  - MAE and RMSE minimized

---

## 📈 Feature Importance (Random Forest)
- Car Age
- Present Price
- Fuel Type (Petrol vs Diesel)
- Transmission (Manual vs Automatic)
- Seller Type

---

## 🗂 Repository Contents

- `Neha_Tiwari_p2_final.ipynb` — Main notebook with code, visuals, and evaluation
- `data.csv` — Dataset used for training and testing
- `README.md` — Project overview and instructions

---

## 📬 Contact

Connect on [LinkedIn](https://www.linkedin.com/in/neha-tiwarii/) for feedback or collaboration.

---
