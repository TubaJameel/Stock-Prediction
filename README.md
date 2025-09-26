This repository contains a Jupyter Notebook that demonstrates how to predict stock prices using machine learning models (LSTM, GRU, and baseline approaches). It walks step by step through data collection, preprocessing, model building, training, evaluation, and visualization.

**Project Overview**

The project is designed to help you:

Understand how to handle time-series stock data.

Apply data preprocessing and feature engineering.

Build and train deep learning models for stock prediction.

Evaluate performance with real metrics.

This is a learning-focused project and not financial advice.

**Requirements**

Python 3.8+

Jupyter Notebook

Main Libraries:

numpy, pandas

matplotlib, seaborn

scikit-learn

tensorflow / keras

**Step-by-Step Workflow**

Load Data

Data Exploration & Cleaning

Check for nulls, plot stock history, inspect trends.

Preprocessing

Scale features (e.g., MinMaxScaler).

Create time-series windows (sliding window technique).

Model Building
Example (LSTM)

Training

Train with early stopping and validation set.

Evaluation

Metrics: RMSE, MAE, MAPE.

**Troubleshooting**

ImportError: cannot import name 'Input' → Use from tensorflow.keras.layers import Input.

AttributeError: 'list' object has no attribute 'reshape' → Convert list to numpy array: np.array(my_list).reshape(-1,1).

Ensure scaler is fit on training data only to avoid data leakage.
