# Boston-House-prediction-Model
This project involves building a machine learning model to predict the median value of owner-occupied homes in Boston using the Boston Housing Dataset. The model is built using a Random Forest Regressor and aims to provide accurate predictions for potential home buyers or sellers.

# Project Overview
This project aims to create a predictive model that can estimate the median value of homes based on various features such as crime rates, number of rooms, property tax rates, etc. The model uses the Random Forest Regressor algorithm, which is a powerful ensemble method.

# Data
The Boston Housing Dataset consists of 506 samples of housing data in Boston. Each sample has 13 features (parameters) that are used to predict the median value of owner-occupied homes (MEDV). Here's a list of all the parameters (features) present in the dataset:

CRIM: Per capita crime rate by town.
ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
INDUS: Proportion of non-retail business acres per town.
CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
NOX: Nitric oxides concentration (parts per 10 million).
RM: Average number of rooms per dwelling.
AGE: Proportion of owner-occupied units built prior to 1940.
DIS: Weighted distances to five Boston employment centers.
RAD: Index of accessibility to radial highways.
TAX: Property tax rate (per $10,000).
PTRATIO: Pupil-teacher ratio by town.
B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town.
LSTAT: Percentage of the lower status of the population.

Each of these features provides information about different aspects of the housing market in various neighborhoods in Boston. The goal of using these features is to predict the MEDV (median value of owner-occupied homes) based on this information using machine learning models.

# Model Evaluation
The model's performance is evaluated using standard regression metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE). These metrics provide insights into how well the model predicts the target variable.
The most efficient model isRandomForestRegressor
Mean Squared Error (MSE) value 8.60853649999999
Root Mean Squared Error (RMSE) value 2.934030759893289
The mean Absolute Error (MAE) value is 2.063343137254902
r2 Score 0.8783103019622318





