# Sale Price Recommendation System for Autosales Platform

## Overview:

Tools: Python, Pandas, NumPy, scikit-learn, LightGBM, XGBoost, CatBoost, Optuna

Goal: Use description of cars to create list price recommendation system for used car site

Data from automobile sales site was used to train a model to predict listing price of vehicles to be implemented as suggestion system. Different models were compared using the following three criteria: quality of prediction (metric: RMSE), speed of prediction, training time.

Topics/Techniques: gradient boosting, regression

## Description:

The goal of this project was to train a model for a used car sales platform, which would be used both for recommending a sales price to new sellers as well as for flagging suspicious postings as potential fraud.

The dataset includes information about the cars (model, brand, number of kilometers on odometer, etc.) as well as about the postings (date posted, zip code, number of photos, etc.). The dataset contains several hundred thousand entries, so one of the criteria. As such, the criteria for evaluating model performance and choosing the final model were prediction accuracy (RMSE), training time, and prediction time.
