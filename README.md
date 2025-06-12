# Retail-Sales-Forcasting-and-Promotional-Impact-Analysis

## Objective

🌟 Our aim is to forecast weekly sales from a particular department.

🌟 The objective of this case study is to forecast weekly retail store sales based on historical data.


## Datasets

- This dataset contains weekly sales from 99 departments belonging to 45 different stores.
  
- The data contains holidays and promotional markdowns offered by various stores and several departments throughout the year.

- The data consists of three sheets: 
    - Stores `stores_data_set.csv`
    - Features `Features_data_set.csv`
    - Sales `sales_data_set.csv`

Data Source : https://www.kaggle.com/manjeetsingh/retaildataset


## Exploratory Data Analysis 

Departments with lower weekly sales tend to receive a higher number of markdowns. For example, this pattern is evident in stores 77 and 99. 


## Build XGBoost Models

> ### TRAIN XGBOOST REGRESSOR IN LOCAL MODE

- RMSE = 14331.41 
- MSE = 205389360.0 
- MAE = 9281.67 
- $R^2$ = 0.6088
- $Adjusted R^2$ = 0.6070

> ### TRAIN XGBOOST USING SAGEMAKER

- RMSE = 7872.68
- MSE = 61979064.0 
- MAE = 4380.04
- $R^2$ = 0.8819
- $Adjusted R^2$ = 0.8814

> ### PERFORM HYPERPARAMETERS OPTIMIZATION

- RMSE = 4266.01 
- MSE = 18198860.0 
- MAE = 1811.64 
- $R^2$ = 0.9638 
- $Adjusted R^2$ = 0.9637
