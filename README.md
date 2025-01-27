# Weather-forecasting using LSTM Model
This project demonstrates how to use Long Short-Term Memory (LSTM) models for predicting weather conditions, specifically temperature and pressure. The models include various architectures designed for univariate, multivariate, and multi-step forecasting.


## Introduction
This repository contains code for building and training LSTM models for weather forecasting. 
It includes:
- Univariate LSTM: Predicts temperature using past temperature data.
- Multivariate LSTM: Uses multiple weather features for forecasting.
- Multi-Step LSTM: Forecasts temperature and pressure for multiple future time steps.

## Features
- Forecasts temperature and pressure.
- Handles single-step and multi-step predictions.
- Supports both univariate and multivariate time series.
- Visualizes actual vs predicted values.

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Matplotlib
- Pandas

## Approach

## Univariate LSTM Models
- Predicts a single variable (e.g., temperature) using past data.
- Implements Vanilla, Stacked, Bidirectional, CNN-LSTM, and ConvLSTM architectures.

## Multivariate LSTM Model
- Uses multiple input features (e.g., temperature, humidity) for enhanced predictions.

## Multi-Step LSTM Model
- Forecasts multiple future time steps for temperature and pressure.
- Includes Vector Output and Encoder-Decoder architectures.

## Evaluation
- The performance of each model is evaluated using two key metrics:
  - **MSE (Mean Squared Error)**: Measures the average squared difference between the actual and predicted values, giving a sense of the model's overall prediction accuracy. A lower MSE indicates better performance.
  - **RMSE (Root Mean Squared Error)**: The square root of MSE, which provides an error metric in the same units as the predicted variable. It is more interpretable and helps in understanding the magnitude of error in predictions.

- Both MSE and RMSE are calculated for each model, and the model with the lowest values indicates the best performance in terms of prediction accuracy for temperature and pressure forecasting.







  



  




