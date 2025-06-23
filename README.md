# House Price Prediction

## Overview
This project aims to predict house prices based on various features like house type, garage presence, number of floors, etc. Using machine learning models, we analyze historical data to forecast prices, assisting potential buyers and sellers in making informed decisions.

## Dataset
- Data source : Kaggle
- Description of key features (House type, Garage, Garage Type, Basement, etc).

## Tools & Technologies Used
- Environment: Jupyter Notebook
- Modeling Tools: XGBoost, Random Forest Regressor, and Linear Regressor

## Data Preprocessing
- Fill Missing Value(If needed)
- Handle duplicate Data
- Handle Anomaly Data
- Convert Categorical Value into numerical value
- Feature engineering
- Feature Selection with correlation matrix and make ranking

## Model Development

### XGBoost
- **Hyperparameter Tuning**: Optimal parameters (max depth, learning rate, sub samble, etc) selected based on Baynessian Opt.

### Random Forest Regressor
- **Hyperparameter Tuning**: Employed Bayesian optimization to fine-tune parameters such as tree depth and number of estimators.

### Linear Regressor

## Model Evaluation & Comparison
- Evaluation metrics: MAPE, R2 Score, MAE
- Feature Importance : which feature that contribute most
