## Stock Price Prediction using Deep Neural Networks

## Introduction:

This project focuses on the employment of LSTM-Long Short-Term Memory, a variant of RNN, which performs quite well in times series prediction, in predicting stock prices.
That's what it was trained for: training on historical stock prices to predict the prices which may later be used for some financial analysis and making decisions.

## Getting Started

## Pre-requisites:

Before you begin, make sure the following packages are installed:

Python 3.7+
pandas
NumPy
Matplotlib
TensorFlow
Keras
scikit-learn

## The Mechanism of Operation:

Data Preprocessing: Import the historical stock market data, then prepare it by handling missing values, scaling the data, and splitting into training and testing datasets.
Feature Engineering: Feature creation will help in learning as well as predicting the model.
Model Building: Implement the model using the LSTM network with TensorFlow and Keras based on preprocessed data. 
Evaluation: Use the test dataset to test the model, and make a number of visualizations for different metrics evaluation. 
Visualization: Plot the actual vs predicted stock prices to view the performance of the model.
