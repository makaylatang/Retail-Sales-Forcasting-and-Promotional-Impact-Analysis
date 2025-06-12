# Retail-Sales-Forcasting-and-Promotional-Impact-Analysis

### Objective

🌟 Our aim is to forecast weekly sales from a particular department.

🌟 The objective of this case study is to forecast weekly retail store sales based on historical data.


### Datasets

- This dataset contains weekly sales from 99 departments belonging to 45 different stores.
  
- The data contains holidays and promotional markdowns offered by various stores and several departments throughout the year.

- The data consists of three sheets: 
    - Stores `stores_data_set.csv`
    - Features `Features_data_set.csv`
    - Sales `sales_data_set.csv`

Data Source : https://www.kaggle.com/manjeetsingh/retaildataset


### Exploratory Data Analysis 

Departments with lower weekly sales tend to receive a higher number of markdowns. For example, this pattern is evident in stores 77 and 99. 


### Build the Models

TRAIN XGBOOST REGRESSOR IN LOCAL MODE

TRAIN XGBOOST USING SAGEMAKER

PERFORM HYPERPARAMETERS OPTIMIZATION

RMSE = 4266.012 
MSE = 18198860.0 
MAE = 1811.6404 
R2 = 0.9638345632190437 
Adjusted R2 = 0.9636760184661681
