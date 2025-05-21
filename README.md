# 🚗 Used Car Price Prediction with Machine Learning

This project aims to predict the prices of used cars based on various vehicle attributes. The analysis involves data cleaning, feature engineering, exploratory data analysis, and applying regression models such as Linear Regression, Random Forest, and Gradient Boosting.

---

## 🎯 Project Objective

To build and evaluate predictive models that can estimate the selling price of a used car given features like year, present price, kilometers driven, fuel type, seller type, transmission, and ownership status.

---

## 📁 Dataset Overview

- **Source:** Kaggle – Used Car Dataset
- **Features:**
  - `Year` – Year of manufacturing
  - `Present_Price` – Current ex-showroom price of the car
  - `Kms_Driven` – Distance driven in kilometers
  - `Fuel_Type` – Petrol, Diesel, or CNG
  - `Seller_Type` – Individual or Dealer
  - `Transmission` – Manual or Automatic
  - `Owner` – Number of previous owners
  - `Selling_Price` – Target variable

---

## 🔍 Exploratory Data Analysis (EDA)

- Distribution plots for selling price and other continuous variables
- Count plots for categorical features
- Pair plots and correlation heatmaps to visualize relationships
- Skewness analysis and outlier detection

---

## ⚙️ Feature Engineering

- Conversion of `Year` to `Car_Age`
- One-hot encoding for categorical features like `Fuel_Type`, `Seller_Type`, and `Transmission`
- Removal of redundant or highly collinear features

---

## 🧠 Machine Learning Models Used

- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**

Models were trained and evaluated based on **R² Score**, **MAE**, and **RMSE**.

---

## 📊 Key Visualizations

- Feature importance from tree-based models
- Actual vs Predicted price scatter plot
- Residual error distribution plots
- Bar charts comparing model performances

---

## 🧪 Results Summary

| Model                  | R² Score | MAE     | RMSE    |
|------------------------|----------|---------|---------|
| Linear Regression      | 0.86     | ~1.25   | ~2.10   |
| Random Forest Regressor| 0.94     | ~0.50   | ~1.00   |
| Gradient Boosting      | 0.96     | ~0.40   | ~0.85   |

> Gradient Boosting Regressor performed best on validation data with the highest R² and lowest error metrics.

---

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---






