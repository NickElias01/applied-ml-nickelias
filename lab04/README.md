# Titanic Fare Prediction Analysis

## By Nick Elias

## Project Overview
This analysis utilizes the Titanic dataset to predict passenger fares using various regression models. The project explores machine learning techniques and feature engineering to enhance prediction accuracy.

## Key Features
- Implementation of multiple regression models:
  - **Linear Regression**
  - **Polynomial Regression**
  - **Ridge Regression**
  - **ElasticNet Regression**
- Feature importance analysis
- Model performance comparison
- Polynomial degree optimization
- Residual analysis for model evaluation

## Technical Details
- **Programming Language:** Python
- **Libraries Used:**
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`

## Results Summary
- **Best Performing Model:** Polynomial Regression (degree 3)
- **Best R² Score:** 0.402
- **Most Important Feature:** Passenger Class
- **Key Challenge:** Right-skewed fare distribution, requiring data transformation and careful model tuning.