# Supervised Learning & Regression: Predicting US Median Price of Houses Sold

### Goal

The goal of this project is to predict median US house sale prices using the FRED (Federal Reserve Economic Data) timeseries API and Python implementations of machine learning models

### Summary

This README provides an overview of the process to fetch and explore data from the FRED timeseries API and use Python for predictive modeling. The outlined steps will guide you through the process of data retrieval, exploration, and implementation of machine learning models for predicting median US house sales prices.

#### Prediction Models
We employed Multiple Linear Regression, Decision Tree Regressor, and Neural Network models to forecast the MSPUS ('Median Sales Price of Houses Sold for the United States'). Among the five prediction models we applied to our dataset, the Multiple Linear Regression model demonstrated the most effective performance.

#### New Machine Learning Libraries 
In this project, we utilized two machine learning libraries that were not part of our class curriculum. Specifically, we employed CatBoost, an open-source library for gradient boosting on decision trees, and XGBoost, an optimized distributed gradient boosting library.


### Key Dependencies (pip or Conda install)

**Data Manipulation and Visualization:**
- pandas
- seaborn
- shap
- seaborn
- matplotlib.pyplot
- matplotlib.ticker
- matplotlib
- dotenv
- os
- fredapi
- matplotlib.pyplot
- numpy
- stats from scipy

**Machine Learning (SKLEARN):**
- StandardScaler
- LabelEncoder
- MinMaxScaler
- mean_squared_error
- r2_score
- DecisionTreeRegressor
- RandomForestRegressor
- KNeighborsRegressor
- LinearRegression
- permutation_importance
- train_test_split

**Advanced Models:**
- CatBoost
- xgboost

**Deep Learning (Tensorflow):**
- tensorflow
- Sequential
- Dense
- Activation


### Authors

- Joshua Lee
- Evan Grillo