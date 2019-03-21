# Predicting stock prices with LSTM Networks
In this repo we explore a method of predicting stock price movements. We apply a long short term memory (LSTM) based recurrent neural network (RNN) to predict whether the S&P 500 will increase (up) or decrease (down) over the next trading month using the features volatility, return and trading volume as three sets of time sequence data. We use accuracy and the area under the (ROC) curve (AUC) as the metric to tune hyper-parameters and to measure the performance of our prediction. It turns out that the LSTM models perform much like the corresponding baseline linear classification models.
