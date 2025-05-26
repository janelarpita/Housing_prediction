# 🏡 Housing Price Prediction using Regression Models

This project aims to build and evaluate various regression models to predict housing prices based on a dataset containing multiple features like location, size, area, etc.

---

## 📌 Project Objectives

- Preprocess and clean the housing dataset
- Explore and visualize key patterns in the data
- Train and test multiple regression models:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Random Forest Regression
  - Gradient Boosting Regression
  - XGBoost Regression
- Evaluate models using multiple performance metrics
- Compare models to identify the best performer

---

## 🧾 Dataset

- File: `Housing - Housing.csv`
- The dataset includes various housing features such as:
  - Number of bedrooms, area, location, price, etc.
- Target variable: `price`

---

## 🧼 Preprocessing

- Handled missing values
- Converted categorical variables using one-hot encoding
- Split dataset into training and testing sets using `train_test_split`

---

## ⚙️ Models Used

| Model                 | Description                             |
|----------------------|-----------------------------------------|
| Linear Regression     | Basic regression technique              |
| Ridge Regression      | L2 regularization                       |
| Lasso Regression      | L1 regularization                       |
| Random Forest         | Ensemble of decision trees              |
| Gradient Boosting     | Boosted decision trees                  |
| XGBoost               | Optimized gradient boosting library     |

---

## 📊 Evaluation Metrics

Each model is evaluated using the following metrics:

- **R² Score** – Goodness of fit
- **RMSE** – Root Mean Squared Error
- **MAE** – Mean Absolute Error
- **MSE** – Mean Squared Error
- **SMAPE** – Symmetric Mean Absolute Percentage Error

---

## 📈 Results Visualization

Each model's performance is plotted using bar charts across the five metrics for visual comparison.

---

## 🧠 Libraries Used

```python
pandas, numpy, matplotlib, seaborn
scikit-learn
xgboost
