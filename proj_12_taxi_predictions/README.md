# Prediction of Number of Taxi Rides Ordered in Following Hour

## Overview:

Tools: Python, Pandas, NumPy, Matplotlib, statsmodels, scikit-learn, LightGBM, XGBoost, CatBoost, Optuna

Goal: Use previous data about number of taxis ordered to predict the number of taxis to be ordered in the following hour

Data from taxi service was used to train model that would predict the number of taxis needed in the hour following the end of the data given to the model. Several approaches were used to achieve the given goal, including exponential smoothing, SARIMA, and regression models trained using time lag information.

Topics/Techniques: time series analysis, exponential smoothing, SARIMA, gradient boosting, regression

## Description:

The goal of this project was to use historical taxi orders to airports to train a model that predicts the number of taxis that will be ordered to airports in the following hour.

The dataset contains only the number of taxis ordered with datetime information as its index. The project was approached in a variety of ways: rolling averages, exponential smoothing, SARIMA analysis, and training machine learning models using 24-hour lag data. The final approach was the most successful, and in choosing and evaluating the specific model, RMSE was used as the metric.
