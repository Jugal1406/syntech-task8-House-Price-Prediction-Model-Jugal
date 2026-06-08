# 🏠 House Price Prediction Web App

## 🔹 Project Overview
This project is an end-to-end Machine Learning application that predicts house prices based on user input features. It covers the complete data science workflow including data preprocessing, model building, evaluation, and deployment using Streamlit.

---

## 🔹 Objective
To build a regression model that can accurately predict house prices using key features such as living area, number of rooms, and overall quality.

---

## 🔹 Dataset
- Source: Kaggle  
- Dataset: House Prices – Advanced Regression Techniques  
- File Used: `train.csv`

---

## 🔹 Features Used
- GrLivArea (Living Area in sq ft)  
- BedroomAbvGr (Number of Bedrooms)  
- FullBath (Number of Bathrooms)  
- GarageCars (Garage Capacity)  
- TotalBsmtSF (Basement Area)  
- OverallQual (Overall Quality Rating)  

---

## 🔹 Machine Learning Workflow

### 1. Data Preprocessing
- Selected relevant features  
- Handled missing values using median imputation  

### 2. Feature Selection
- Reduced dataset to important numerical features for simplicity and performance  

### 3. Model Training
- Linear Regression  
- Random Forest Regressor  

### 4. Model Evaluation
- Evaluation Metric: RMSE (Root Mean Squared Error)

| Model               | RMSE      |
|--------------------|----------|
| Linear Regression  | 39240.83 |
| Random Forest      | 28642.50 |

👉 Random Forest performed better and was selected as the final model.

---

## 🔹 Deployment
The model is deployed using **Streamlit** to create an interactive web application.

### 🔗 Live App
👉 https://house-price-prediction-basic-model.streamlit.app/
