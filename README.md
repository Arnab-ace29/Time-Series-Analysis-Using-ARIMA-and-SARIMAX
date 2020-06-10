# Time-Series-Analysis-Using-ARIMA-and-SARIMAX
The baisc aim of this project is to understand working of ARIMA and SARIMAX models and how they can be used.  
Here, for prediction we will follow following pattern.  
Step 1. Check the data and try to find a proper pattern, check seasonility or trend present.
Step 2. Here we will try two methods to deal with the data, first we try to remove seasonility from the time-series and try to visually find (p,d,q) using Autocorrelation and Partial Autocorrelation plots and test how it performs on ARIMA.
Then using the same hyperparameters, we will check the performance on SARIMAX.  
Then we wil try to find the best hyperparameters by using grid search.  
Using grid search helps us to find the best solution but using Autocorrelation and Partial correlation plots helps us to understand the basics better. Hence,first we try using plots to get the idea of the series.
Dataset can be found here:-https://www.kaggle.com/c/competitive-data-science-predict-future-sales
