# Stock Market Prediction using Numerical and Textual Analysis

## Objective
 
To create a hybrid model for stock price performance prediction using numerical analysis of historical stock prices, and
sentimental analysis of news headlines.


## Approach

* Extract Sentiment Scores from given news headlines dataset, with the help of nltk's SentimentIntensityAnalyzer.

* Use Multivariate Time Series Forecasting using the LSTM (Long Short-Term Memory) model in Keras and Tensorflow. LSTM analyses the features from both sentiment scores and numerical Historical stock data to predicit opening stock prices.

## Results

* Achieved Training loss: 0.05 and Validation loss: 0.02

* Achieved RMSE on test data : 511


## Data
 
* Historical stock prices(SENSEX (S&P BSE SENSEX)) from https://finance.yahoo.com/

* Textual (News) data from https://bit.ly/36fFPI6

## References:
[Deep learning for stock prediction using numerical and textual information](https://www.researchgate.net/publication/306925671_Deep_learning_for_stock_prediction_using_numerical_and_textual_information)- Ryo Akita, Akira Yoshihara, Takashi Matsubara, Kuniaki Uehara

