Attention-Based LSTM Time Series Forecasting
 Overview

This project builds a multivariate time series forecasting model using:

LSTM

Self-Attention

Optuna Hyperparameter Optimization

 Problem Statement

Predict future values from past 40 timesteps, and identify important time lags using an attention mechanism.

Workflow

Data preprocessing (scaling + windowing)

Custom Attention-LSTM model

Optuna hyperparameter tuning

Final training

Evaluation (RMSE, MASE)

Attention visualization

Results

Prediction vs Actual Plot

Mean Attention Plot

Attention Heatmap

(Metrics replace with your values)

RMSE (orig): XXX  
MASE (orig): XXX

Files
submission_artifacts/
│── attention_lstm_model.keras  
│── test_preds_orig.csv  
│── attention_weights_test.csv  


Notebook includes all code for:

Data generation

Preprocessing

Model

Tuning

Plots

Evaluation

Conclusion

This project shows how LSTM + Attention improves forecasting and provides interpretability.
