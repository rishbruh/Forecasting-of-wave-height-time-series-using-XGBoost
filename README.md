# Forecasting-of-wave-height-time-series-using-XGBoost

We have data taken from a single scientific wave buoy that measures wave height, time between waves, wind direction and sea temperatures. The objective is to use historical data from the years (2017-2018) in order to predict wave heights for the year 2019, thus the wave height is our target.

We use XGBoost Regressor for forecasting the wave height for 2019. It is an ensemble learning method that will create a final model by combining several weak models. Further XGBoost is known to provide accurate and faster predictions than a few of the traditional forecasting models (eg - ARIMA).

The model gave us an accuracy of 94.9% on our training set and 94.2% on our test data set. The predcitions are further visualized as well, and the model yields pretty satisfactory results.

![image](https://user-images.githubusercontent.com/62597096/190705005-294d0b8f-80c7-40d6-b746-72c96194fae4.png)


Refer to the colab notebook in the repository for a detailed explanation.
