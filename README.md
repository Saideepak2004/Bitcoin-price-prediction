# Bitcoin-price-prediction
## Overview

This project focuses on predicting Bitcoin prices using a Long Short-Term Memory (LSTM) deep learning model. The model is trained on historical cryptocurrency market data to learn price trends and forecast future Bitcoin prices.

The project demonstrates the application of Time Series Forecasting, Deep Learning, and Financial Data Analysis using Python and TensorFlow/Keras.

## Features

* Historical Bitcoin price analysis
* Data preprocessing and normalization
* Time-series sequence generation
* LSTM-based deep learning model
* Model loss graph
* Prediction of future Bitcoin prices
## Technologies Used


Python
TensorFlow / Keras
NumPy
Pandas
Matplotlib
Scikit-learn
Dataset

The dataset contains historical Bitcoin market data including:

Opening Price
Closing Price
High Price
Low Price
Trading Volume
Date/Time Information

### Dataset Source:

Kaggle Bitcoin Historical Data
#### [Dataset link](/kaggle/input/datasets/mczielinski/bitcoin-historical-data)

## Project Workflow
### 1. Data Collection

* Collected historical Bitcoin price data from online financial datasets.

### 2. Data Preprocessing
* Removed null values
* Selected relevant features
* Normalized data using MinMaxScaler
* Converted data into sequential time-series windows
### 3. Model Building

Built an LSTM neural network using TensorFlow/Keras:

* Input Layer
* Multiple LSTM Layers
* Dense Output Layer
* Dropout layers for regularization

### 4. Prediction & Visualization

* Predicted future Bitcoin prices 


## Results
* Successfully predicted Bitcoin price trends using LSTM networks
* Achieved effective forecasting performance on time-series financial data
