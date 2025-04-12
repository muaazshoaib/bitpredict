# BitPredict: Time Series Forecasting with TensorFlow

This project demonstrates the development of **BitPredict**, a time series forecasting model built with TensorFlow and Keras. The goal of this project is to predict future values based on historical data using various deep learning models.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Models](#models)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
**BitPredict** applies deep learning techniques to time series data to forecast future values. This project involves preprocessing time series data (normalization and windowing) and evaluating model performance using MAE and MSE metrics.

The following models were implemented:
- **Naive Forecasting Model**: Simple baseline model.
- **Dense Neural Network (DNN)**: Fully connected network for forecasting.
- **LSTM Model**: Recurrent neural network for sequential data.
- **1D CNN Model**: Convolutional network for time series analysis.

## Technologies Used
- **TensorFlow** – for building and training deep learning models
- **Keras** – for model building and evaluation
- **Python** – for data processing and scripting
- **NumPy** – for numerical computations
- **Pandas** – for data manipulation

## Data
The data used for this project was sourced from [insert data source]. It contains time-dependent values, such as stock prices, temperature data, or sales data. The dataset was preprocessed to normalize and window the time series for training the models.

## Models
- **Naive Model**: A simple baseline model.
- **DNN Model**: A fully connected deep learning model.
- **LSTM Model**: A type of RNN for learning patterns from sequential data.
- **1D CNN Model**: A model using convolutions over time series data.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/muaazshoaib/bitpredict.git
    cd bitpredict
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare time series data and ensure it's in a CSV format.
2. Load the data and preprocess it in `data_preprocessing.py`.
3. Train the models by running their respective Python scripts (e.g., `train_lstm.py` for LSTM).
4. Evaluate model performance using MAE and MSE.

Example:
```bash
python train_lstm.py
