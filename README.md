# Rossmann Store Sales Forecasting

## Project Overview

This project focuses on forecasting retail sales for Rossmann stores using historical sales data and machine learning techniques.
The objective is to predict future sales and identify the factors that have the strongest impact on store performance.

## Business Problem

Accurate sales forecasting helps retailers:

- Optimize inventory management
- Improve staffing decisions
- Plan promotions more effectively
- Reduce operational costs
- Support strategic business planning

## Dataset

Dataset: Rossmann Store Sales (Kaggle)

The dataset contains information about:

- Daily sales
- Store characteristics
- Promotions
- School holidays
- Public holidays
- Customer counts
- Competition information

## Project Structure

```text
rossmann-store-sales/
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_modelling.ipynb
│   └── 04_forecasting_analysis.ipynb
├── data/
├── outputs/
├── src/
├── README.md
├── requirements.txt
└── .gitignore
```

## Exploratory Data Analysis

Key areas explored:

- Sales distribution
- Customer behavior
- Store performance
- Promotional impact
- Seasonal trends
- Holiday effects

## Feature Engineering

Features created and prepared include:

- Date-based features
- Month
- Week
- Day of week
- Promotional indicators
- Store-related variables
- Competition variables

## Model Development

The final forecasting model was built using:

- XGBoost Regressor

Model evaluation metrics:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

## Results

Final XGBoost model achieved:

- MAE ≈ 800
- RMSE ≈ 1120
- R² ≈ 0.87

The model explained approximately 87% of the variance in sales and produced strong forecasting performance on unseen future data.

## Feature Importance

The model identified the most influential variables contributing to sales predictions, helping provide business insight into the drivers of store performance.

## Forecasting Analysis

A dedicated forecasting notebook was used to:

- Generate future sales predictions
- Compare actual vs predicted sales
- Evaluate forecasting performance
- Visualize forecasting trends

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Jupyter Notebook

## Author

Mario Da Silva

Aspiring Data Scientist focused on machine learning, forecasting, and business analytics.
