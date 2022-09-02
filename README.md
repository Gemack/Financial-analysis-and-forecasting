# Stock Price Time Series Financial Analysis and Forecasting using Google Tensorflow


[Check out my post on Neuron Network on Hashnode](https://emack.hashnode.dev/understanding-artificial-neuron-network)


This notebook performs basic financial analysis on stock data of 
 - (1) Master Card 
 - (2) PayPal 
 - (3) Visa. 
This notebook also attempts and uses deep learning by applying the LSTM (Long Short Term Memory)
to forecast future closing price of the stock data using **Google's TensorFlow**  

### Basic concept 

#### LSTM
Long Short Term Memory Network is part of the Recurrent Neuron Network used in deep learning, LSTM is very
good in learning from sequence of data because it has feedback connections, LSTM Can process an entire 
sequence of data ranging from speech to video.LSTM is used for many deep learning task such as 
- Language modelling 
- Time series forecasting
- Video to text conversion
- Handwriting recognition 

With the help of the tensorflow python library we will be using LSTM to predict future price of stock data.


#### OPENNING 
According to Investopedia a stock opening price is the price at which a security first trades upon the opening of an exchange on a trading day. The opening price is largely influenced by the closing price of the previous day and it is an important marker for trading for that day.

#### HIGH and LOW
The high price is the highest price a stock is traded for that day in a stock market while the low price is the lowest a stock market is traded for that day, both price gives traders ideas on what news is driving the price for that day for they are used to find signals and they can be used for calculating moving average
CLOSE
The close is the opposite of the opening stock it is simply the end of a trading session in the financial market.

#### ADJUSTED CLOSE AND VOLUME
The adjusted close and volume reflect details for past performances and are often used to examine historical returns 

#### TOTAL TRADE 
Opening trade for the day plus volume of that day

#### RETURNS
this gives information about percent gain (or loss) if stock is bought today and then sold the next day

### CUMULATIVE RETURNS
The Cumulative return gives investors insight on stock volatility 

