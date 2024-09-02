# Gold-price-prediction-model
## Overview
This project focuses on predicting the price of gold using a Long Short-Term Memory (LSTM) neural network, a specialized type of Recurrent Neural Network (RNN) that excels at learning from time-series data. The model is designed to predict future gold prices based on historical data, capturing the temporal dependencies inherent in financial time series.
## Dataset
The dataset consists of daily gold prices over a span of several years. For each day, the dataset includes the following features:

Date: The specific day of the price data.
Price: The closing price of gold for the day.
Open: The opening price of gold.
High: The highest price reached during the day.
Low: The lowest price reached during the day.
For this project, only the Price column is used to train the model, though future versions may incorporate additional features to improve accuracy.

## Methodology
This model will make use of a gold price dataset from the 1st of January 2015 to the 30th of August 2024 that was sourced from Kaggle.
