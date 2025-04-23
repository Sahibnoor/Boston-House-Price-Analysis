# 🏠 Boston House Price Analysis

This project involves exploratory data analysis (EDA) and predictive modeling on the **Boston Housing Dataset**, a classic dataset in machine learning. The primary objective is to understand the key factors influencing housing prices and to build models that can accurately predict house prices based on these factors.

## 📌 Objective

To perform comprehensive EDA and build regression models to predict housing prices in Boston suburbs, using various socioeconomic and environmental features.

## 📊 Dataset Description

The Boston Housing dataset contains information on housing in Boston, including:
- **Target Variable:** `MEDV` – Median value of owner-occupied homes in $1000s
- **Features include:**
  - CRIM – Crime rate per capita
  - RM – Average number of rooms per dwelling
  - LSTAT – % lower status of the population
  - PTRATIO – Pupil-teacher ratio
  - DIS – Distance to employment centers
  - TAX – Property tax rate
  - Others...

## 🧹 Steps Performed

- **Data Cleaning:** Checked for missing values and inconsistencies  
- **Exploratory Data Analysis:**
  - Correlation heatmap and scatter plots
  - Distribution analysis of target and features
- **Feature Engineering:**
  - Identified significant predictors
  - Normalized and transformed skewed variables
- **Modeling:**
  - Linear Regression
  - Lasso & Ridge Regression
  - Random Forest (if included)

## 📈 Key Insights

- Strong positive correlation between `RM` (number of rooms) and housing prices.
- Strong negative correlation between `LSTAT` (poverty level) and `MEDV`.
- Crime rate (`CRIM`) and proximity to employment (`DIS`) also influence prices.
- Regularization techniques improve generalization and prevent overfitting.

## 🧠 Tools Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

## 📁 Files

- `Boston_House_Price_Analysis.ipynb` – Full EDA and modeling
- `README.md` – Project overview

## ✅ Outcome

A baseline predictive model with strong interpretability was created. The project lays the foundation for more complex regressors or ensemble models for even better price predictions.

---

