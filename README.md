
# NYC Taxi Trip Duration Prediction

![NYC Taxi]([https://images.unsplash.com/photo-1496056987863-8a3ebd347f61](https://www.featuretools.com/wp-content/uploads/2018/12/taxi-min-1024x1024.jpg))

## Overview

Our task is to build a model that predicts the total ride duration of taxi trips in New York City. The dataset for this project is sourced from [NYC Taxi Trip Duration competition on Kaggle](https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data).

## Dataset

The dataset contains information about taxi trips in NYC, including pickup and dropoff timestamps, passenger count, and geographical coordinates. For detailed information about the dataset, please refer to the [Kaggle competition data page](https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data).

## Features

The features used for modeling include pickup and dropoff timestamps, passenger count, and geographical coordinates (pickup/dropoff longitude and latitude). Exploratory Data Analysis (EDA) was conducted to understand the distribution and relationships among the features.

## Modeling

The prediction model is built using the following regression algorithms:

- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**

The XGBoost Regressor was fine-tuned to optimize model performance. Hyperparameters were adjusted to achieve the best results. The primary metric used for evaluation is the Root Mean Squared Error (RMSE) on the logarithmic scale.

## Libraries Used

- [Scikit-Learn](https://scikit-learn.org/)
- [XGBoost](https://xgboost.readthedocs.io/)

## Files Included

- `NYC_Taxi_Duration_Prediction.ipynb`: Jupyter Notebook containing the entire project workflow, from data exploration to model evaluation.
- `taxi_duration_model.pkl`: Pickle file containing the trained XGBoost Regressor model.
