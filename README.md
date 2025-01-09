**AAPL Stock Closing Price Predictor**

This project uses a machine learning model trained to predict the daily closing price of AAPL (Apple Inc.) stock based on historical trading data. The model has been trained using features including the opening price, high price, low price, and trading volume. While predictions are not currently implemented, the project demonstrates the end-to-end process of preparing and training an ANN for stock price forecasting.

Features

Trains an ML model to predict AAPL's daily closing price.

Built using Python and TensorFlow/Keras.

Ready for deployment as a Flask API.

Dataset

The data for this project is fetched using the Alpha Vantage API, which provides daily stock market data for AAPL.

Features Used:

Open: Opening price of the stock.

High: Highest price during the trading day.

Low: Lowest price during the trading day.

Volume: Total number of shares traded during the day.

Model Architecture

The model is a simple Artificial Neural Network (ANN) with the following structure:

Input Layer: 4 neurons (one for each feature: open, high, low, volume).

Hidden Layers: Two hidden layers with ReLU activation.

Output Layer: A single neuron with a linear activation function to predict the closing price.

Training Details

Loss Function: Mean Squared Error (MSE)

Optimizer: Adam

Metrics: MSE

Epochs: 250

Batch Size: 10

Results

The model achieved the following performance metrics:
loss: 4.1507  

Mean Squared Error (MSE): 4.1507
