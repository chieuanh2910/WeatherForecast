# Weather Forecast
This analysis represents a multivariate time-series forecast of two-week mean temperature in the city of Delhi from 2013 to 2017. The objectives inlcude data exploration, visualization, and forcasting with the target being the daily mean temperature for 14 days ahead.

The structrure of the analysis includes Data Preprocessing, Prediticve Modeling, and Experiemnts Report

Data Preprocessing

This section involves data exploration to understand the characteristics of the provided dataset. This included visualizing time series patterns and normalizing data values to scale 0-1. The dataset is then divided into a training set, encompassing data from 2013 to 2016, and a testing set consisting of data from 2017.

Predictive Modelling

A Recurrent Neural Networks (RNN) is designed and implemented to conduct the time-series forecasting. The model leverages the temporal patterns present in the dataset to make predictions for the next two weeks.

Model Evaluation

To evaluate the forecasting model's performance, the testing dataset is data in 2017. Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE), were computed to assess the accuracy and reliability of the forecasts. The results provide insights on how reliable the model is able to capture temperature variations and make predictions for the specified horizon.

Experiments Report

While the initial model provides promising results, there is room for improvement in several areas:

Hyperparameter Tuning: Fine-tuning hyperparameters such as the model architecture, learning rate, and batch size may enhance forecasting accuracy. Feature Engineering: Further feature engineering, including the incorporation of external variables like humidity, wind speed, and precipitation, could improve the model's predictive power. Ensemble Techniques: Exploring ensemble methods or hybrid models that combine deep learning with traditional time series forecasting approaches may yield better results. Advanced Deep Learning Architectures: Experimenting with more complex deep learning architectures, such as Long Short-Term Memory (LSTM) networks or Gated Recurrent Units (GRUs), could capture long-term dependencies more effectively. Additional Data Sources: Incorporating data from other sources, such as satellite imagery or climate indices, may enhance the model's forecasting capabilities.

In summary, this analysis aims to develope and evaluate a deep learning model for forecasting the mean daily temperature in Delhi with a two-week horizon. The results could help business such as F&B industry to have better understanding of weather forecasting in Delhi and have good plannings to introduce new foods or beverages in time, or better inventory management to avoid high costs of ingredients during off seasons.
