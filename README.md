# Food Delivery Time Prediction 🚴‍♂️🍴

## 📌 Project Overview

This mini project focuses on predicting **food delivery times** using regression techniques. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/denkuznetz/food-delivery-time-prediction) and contains various factors such as distance, traffic, weather, preparation time, and courier experience that influence delivery duration.

## 📊 Dataset Description

The dataset includes the following key features:

* **Delivery\_person\_ID**: Unique identifier for each delivery person
* **Order\_ID**: Unique identifier for each order
* **Distance\_km**: Delivery distance in kilometers
* **Weather**: Weather conditions (Clear, Rainy, Snowy, Foggy, Windy)
* **Traffic\_Level**: Low / Medium / High
* **Time\_of\_Day**: Morning / Afternoon / Evening / Night
* **Vehicle\_Type**: Bike / Scooter / Car
* **Preparation\_Time\_min**: Time required to prepare the order
* **Courier\_Experience\_yrs**: Courier’s delivery experience in years
* **Delivery\_Time\_min**: Target variable (Total delivery time in minutes)

## 🛠️ Project Workflow

1. **Data Preprocessing** – handled missing values, outliers, and categorical encoding
2. **Exploratory Data Analysis (EDA)** – analyzed feature distributions, correlations, and visual trends
3. **Model Development** – applied **Multiple Linear Regression** while validating **5 Multiple Linear Assumptions (MLA):**

   * Linearity
   * Independence
   * Homoscedasticity
   * Normality of residuals
   * No multicollinearity
4. **Model Evaluation** – used scatter plots, residual plots, and R² score to assess performance

## ✅ Conclusion

* Predictions showed a strong **upward trend** between actual and predicted values
* Scatter plots aligned closely with the **ideal fit line (red dashed line)**
* Achieved an **R² score of 0.807**, proving the model’s effectiveness in capturing delivery time patterns

## 📂 Project Type

🔹 **Mini Project** – built as part of machine learning practice to understand regression modeling and dataset handling

---
