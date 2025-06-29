# Stock-Price-Prediction
# Stock Price Prediction with LSTM

This project predicts stock prices using an LSTM neural network in Python (Jupyter Notebook).  
It fetches historical stock data (using yfinance), visualizes prices and moving averages, and trains an LSTM model for time-series prediction.

**Workflow:**
- Download historical stock data for a selected ticker.
- Visualize price and compute moving averages (100, 200 days).
- Split data into train/test sets.
- Prepare data for LSTM (normalization, reshaping).
- Build and train LSTM model with TensorFlow/Keras.
- Predict and visualize actual vs. predicted prices.

> All code and analysis are in the notebook:  
> `Stock Price Prediction LSTM.ipynb`

**Dependencies:**  
- pandas, numpy, matplotlib, yfinance, tensorflow

**How to use:**  
1. Open the notebook in Jupyter or Colab.
2. Run cells sequentially to fetch data, train the model, and view predictions.

---
