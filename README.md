# **Stock-Price-Prediction-using-LSTM-and-Technical-Indicators**

In this project, I have created a model for the prediction of Stock Market prize of **BANK NIFTY**.

First, I have extracted data from **Yahoo Finance**.

Next, the data was processed by **scaling** it and **cleaning** it by removing the null values

The Technical Indicators incorporated here are:
* **Moving Average (MA)**
* **Exponential Moving Average (EMA)**
* **Moving Average Convergence Divergence (MACD)**
* **Bollinger Bands**

I have used **LSTM (Long Short Term Memory)** due to their efficient working with **Sequential** as well as **Time Series** Data. They are also beneficial in getting rid of the vanishing gradient problem and are capable of learning long-term dependencies.

The efficiency of the model can be improved by adding **more parameters** to it.

We can make this project better by adding sentiment analysis using NLP to process daily tweets, adding fundamental ratios, using NLP to analyze quarterly and annual income statements, etc.
