# Boston Housing Price Prediction Project
## Overview
This project aims to predict house prices in Boston using regression algorithms. It utilizes the Boston house prices dataset and various regression techniques to analyze and predict house prices based on several attributes.

## Setup and Installation
### Requirements
Python 3.9
Libraries: numpy, pandas, scikit-learn, xgboost, seaborn, matplotlib, statsmodels

## Project Structure
boston_housing_2022/ - Contains the main project directory.
data/ - Data directory where the dataset is stored.
plots/ - Directory to save visualizations.
README.md - Project documentation.

## Dataset
The dataset used in this project is the Boston housing prices dataset. It includes information on various features related to housing prices such as crime rate, land zoning, nitric oxides concentration, average number of rooms, etc. The target variable is the median value of owner-occupied homes in $1000's.

## Usage
boston_housing_regression.ipynb: Jupyter Notebook containing the main code for data loading, preprocessing, model training, and evaluation.

## Methodology
Data Exploration: Analysing features, checking correlations, visualizing distributions, and exploring relationships between variables.
Model Building: Utilizing regression algorithms such as Linear Regression, Decision Trees, Random Forest, and XGBoost for prediction.
Model Evaluation: Evaluating model performance using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared.

## Results
The project achieved the following results:

### Linear Regression:

R-Squared: 0.818
MAE: 1.089
MSE: 1.015
RMSE: 1.129

### Decision Tree:

R-Squared: 0.710
MAE: 1.112
MSE: 1.018
RMSE: 1.145

### Random Forest:

R-Squared: 0.784
MAE: 1.088
MSE: 1.014
RMSE: 1.124

### XGBoost:

R-Squared: 0.836
MAE: 1.081
MSE: 1.011
RMSE: 1.110

# Conclusion
This project successfully explored various regression algorithms for predicting Boston housing prices. The best-performing model was XGBoost, achieving an R-Squared value of 0.836 for validation dataset. Further improvements can be made by optimizing hyperparameters and feature engineering.