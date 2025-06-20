Stock Price Trend Prediction with LSTM

This project focuses on predicting stock closing prices using an LSTM (Long Short-Term Memory) neural network. We use the `all_stocks_5yr.csv` dataset, which contains 5 years of historical stock data for multiple companies.

Project Objective

The goal is to build a model that can learn patterns in historical stock prices (using Open, High, Low, Close, and Volume data) and predict future closing prices of a selected stock.

Dataset

- Source:Local file (`all_stocks_5yr.csv`)  
- Columns used:`open`, `high`, `low`, `close`, `volume`  
- Example stock symbol:`AAPL`

Tools & Technologies

- Python
- Pandas, NumPy, Matplotlib
- Scikit-Learn
- TensorFlow + Keras (LSTM)
- Jupyter Notebook

Steps to Run

1.Install the required libraries:
`bash
pip install pandas numpy matplotlib scikit-learn keras tensorflow

2️.Run the Jupyter notebook code:

Load the dataset from your local machine.
Preprocess the data (scaling, sequence creation).
Train the LSTM model.
Visualize training loss and predictions.
Save the trained model as aapl_lstm_model.keras.

Results:
The model successfully predicts the stock’s closing price trend.

A graph compares actual vs. predicted closing prices.

The model file is saved for future use.

