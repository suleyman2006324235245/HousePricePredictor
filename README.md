# House Prices Prediction

## Project Overview

This project is my solution to Kaggle's **House Prices: Advanced Regression Techniques** competition. The goal is to predict house sale prices based on different features such as house quality, size, location, and condition.

## Kaggle Result

- **Kaggle Score:** 0.12022
- **Competition:** [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

## Approach

I followed several steps to prepare the data and build the prediction models:

- **Data Cleaning:** Handled missing values in numerical and categorical features.
- **Outlier Detection:** Identified and removed an unusual observation that could negatively affect model performance.
- **Feature Engineering:** Created new features such as total square footage, house age, and years since remodeling.
- **Target Transformation:** Applied a logarithmic transformation to the target variable to improve model performance.
- **Feature Scaling:** Used RobustScaler for the linear model.
- **Cross-Validation:** Used 5-fold cross-validation to evaluate model performance.

## Models

I trained several machine learning models:

- **XGBoost**
- **LightGBM**
- **CatBoost**
- **Lasso Regression**

To improve the final predictions, I combined these models using **Stacking**, with Ridge Regression as the meta-model.

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- SciPy
- Matplotlib
- Seaborn

## What I Learned

Through this project, I improved my understanding of:

- Data preprocessing and feature engineering.
- Handling missing values and outliers.
- Training and evaluating machine learning models.
- Cross-validation techniques.
- Ensemble learning and model stacking.
- Combining different models to improve prediction performance.
