# Car Price Prediction – Learning-Based Machine Learning Project 🚗💰

## Project Overview
This project is a **Car Price Prediction system** built from scratch using Python and scikit-learn.  
It is designed as a **learning exercise** to practice the full machine learning workflow: data exploration, feature engineering, preprocessing, modeling, hyperparameter tuning, and evaluation.

> ⚡ **Note:** This project is primarily for learning purposes. The dataset and models are used to demonstrate techniques, not to build a production-ready predictor.

---

## Features & Highlights

### 1. Exploratory Data Analysis (EDA)
- Histograms, boxplots, and heatmaps to understand the data distribution and correlations.
- Analysis of numeric and categorical features to identify trends and outliers.

### 2. Feature Engineering
- Added meaningful features such as:
  - `Car_Age` – calculated from the car’s year.
  - `Mileage_per_Year` – normalized mileage by age to remove bias.
  - `Is_Luxury` – indicates whether the car is a luxury brand.
- Purpose: enhance model learning and predictive performance.

### 3. Preprocessing Pipeline
- Numeric columns: StandardScaler (mean=0, std=1)
- Categorical columns: OneHotEncoder
- Fully integrated **pipeline ensures preprocessing is applied correctly during cross-validation and hyperparameter tuning**.

### 4. Models Used
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### 5. Hyperparameter Tuning
- `RandomizedSearchCV` applied to models with tunable hyperparameters.
- Cross-validation ensures robust evaluation and reduces overfitting risk.

### 6. Evaluation Metrics
- R² (Coefficient of Determination)
- Mean Absolute Error (MAE)
- Comparison of multiple models to select the best performing one.

---
