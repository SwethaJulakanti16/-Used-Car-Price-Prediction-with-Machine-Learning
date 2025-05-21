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

![Image](https://github.com/user-attachments/assets/9512ce96-a9bc-4cde-af58-b8e951fedc60)

![Image](https://github.com/user-attachments/assets/a1fcd135-a6dc-4f40-b501-6c3c1638a344)
![Image](https://github.com/user-attachments/assets/7487a847-5321-415d-b313-5190b7417cd3)
![Image](https://github.com/user-attachments/assets/55af8fba-9d14-43c5-a5c9-32c8b3bebaf5)
![Image](https://github.com/user-attachments/assets/34d32a6b-8021-4ceb-aa6a-ce24a74b87ae)
![Image](https://github.com/user-attachments/assets/a8271026-7aca-4a06-8b92-9aa2344f2d35)
![Image](https://github.com/user-attachments/assets/64b064d8-0a09-4d94-b8ff-5b7ce049b723)
![Image](https://github.com/user-attachments/assets/0ad7141e-ee11-487a-ba11-0df19db2fa61)
![Image](https://github.com/user-attachments/assets/25383753-ba54-453e-808f-05f546c2ba68)
![Image](https://github.com/user-attachments/assets/d645dd71-8901-412d-961a-bf0eeb045313)
![Image](https://github.com/user-attachments/assets/512cc866-8193-4553-80bb-87fb1767bf6b)
![Image](https://github.com/user-attachments/assets/a50e7b78-5910-4c4f-bd03-809b187133b1)
![Image](https://github.com/user-attachments/assets/3e68c4ea-7f9d-4778-9702-60014e267f56)
![Image](https://github.com/user-attachments/assets/3a83cb41-b774-44e9-a94a-2a62ef40a099)
![Image](https://github.com/user-attachments/assets/8518daf4-6bbb-4773-a830-abf0a0fbb6cd)
![Image](https://github.com/user-attachments/assets/57d63405-8e08-46e8-8c81-597f024b2f34)
![Image](https://github.com/user-attachments/assets/b04876fe-3948-4f50-8b7b-c11c1d507a54)
![Image](https://github.com/user-attachments/assets/6073ae23-feb7-4097-843f-abb0154409b1)
![Image](https://github.com/user-attachments/assets/b4dfb66f-ae49-4daf-9a21-8022255ab801)
---

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---






