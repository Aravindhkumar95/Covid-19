# Covid-19
In this project, I have build the time series model using XGBoost and LSTM to predict the Confirmed Cases and Fatalities.

# Dataset

Dataset provided by Kaggle for the competition on COVID-19 Global Forecasting(Week 4). The Dataset consist of Train and Test Datasets, we should build the model based on Training Dataset and predicting the number of confirmed cases as well as number of resulting Fatalities in various location across the world for the Future Dates.

# Visualization

![](Visualization_Images/Count_of_Cases_and_Deaths.png)
# Modelling

There are several machine learning models we can use for Time Series Forecasting Data such as Linear Regression,Naive, ARIMA, Tree Based models. But I have used XGBoost Regressor, it is a supervised algorithm and it has wide varity of tuning parameters.It outperforms in speed and gives better performance and also it minimize the loss when compare to other algorithms.I also would like to get some experience in Neural networks as well, since LSTM is used for sequence prediction problems I tried to employ the same for this Time Series Forecasting Dataset.
