# 5002project

## Code instructions

5002_ARIMA.ipynb is the ARIMA model builded in this project.

5002_LSTM.ipynb and 5002_LSTM2.ipynb are both the LSTM model builded in this project.

5002_CNN.ipynb is the CNN model builded in this project.

All of the code files can be run directly in Google Colab.

Changes in LSTM2：
1. CuDNNLSTM instead of LSTM.
2. Add the advanced activation layer LeakyReLU.
3. Modified some coefficients, such as epochs.
4. Set EarlyStopping as the callbacks is used to stop training early.


## reference:
1. https://www.kaggle.com/muonneutrino/wikipedia-traffic-data-exploration
2. https://www.kaggle.com/zoupet/predictive-analysis-with-different-approaches
3. https://www.kaggle.com/ashutosh619sudo/wikipedia-web-page-traffic-forecasting
4. www.kaggle.com/ymlai87416/web-traffic-time-series-forecast-with-4-model#2.-Data-transformation-and-helper-functions
