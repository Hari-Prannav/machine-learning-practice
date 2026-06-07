# Store Sales Forecasting

## Overview

Forecasting retail sales using historical sales data from the Kaggle Store Sales competition.

## Techniques Used

- XGBoost Regressor
- Feature Engineering
- Lag Features
- Rolling Statistics
- Oil Price Features
- Holiday Features
- Recursive Forecasting
- Log Target Transformation

## Features

- lag_1
- lag_2
- lag_7
- lag_14
- lag_28
- rolling_mean_7
- rolling_mean_14
- rolling_mean_28
- rolling_std_7
- rolling_std_28
- onpromotion

## Results

| Version | Kaggle Score |
|----------|----------|
| Initial | 1.49 |
| Lag Features | 1.17 |
| Final Model | 0.477 |

## Key Learning

Applying a log transformation to the target variable produced the biggest improvement in forecasting accuracy.