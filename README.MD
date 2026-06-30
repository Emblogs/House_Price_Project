# House Price Prediction

Predicting house sale prices using machine learning regression techniques.

## Tools Used
- Python, Pandas, NumPy, Scikit-learn, XGBoost

## Approach
- Exploratory Data Analysis with correlation heatmaps
- Feature engineering (created TotalSF from combined square footage features)
- Log transformation of target variable to handle skewness
- Missing value imputation using SimpleImputer
- Target encoding for Neighborhood using MEstimateEncoder
- One-hot encoding for categorical features
- Model: XGBoost Regressor with early stopping

## Features Used
OverallQual, GrLivArea, GarageArea, TotalBsmtSF, 1stFlrSF, YearBuilt, YearRemodAdd, GarageCars, FullBath, TotRmsAbvGrd, KitchenQual, Neighborhood

## Results
Validation MAE: $18,856.64

## Dataset
House Prices - Advanced Regression Techniques (Kaggle)
