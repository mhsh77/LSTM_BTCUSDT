## 📈 LSTM-Based Bitcoin Price Prediction Using RSI & Close Price
This repository contains a deep learning model built with TensorFlow/Keras to forecast Bitcoin's closing price using historical RSI and Close price data. The model leverages a stacked Bidirectional LSTM architecture to capture temporal dependencies and volatility patterns in financial time series.
## 🔧 Features
- Multivariate time series input: RSI_14 and Close price
- Sliding window sequence generation for LSTM input
- Scaled and inverse-transformed predictions for real-world interpretability
- Performance metrics: RMSE and MAE
- Visualization of predicted vs actual Close prices
## 🧠 Model Architecture
- Bidirectional LSTM (128 units) with sequence output
- Stacked LSTM (64 units) for deeper temporal learning
- Dense layers with ReLU activation
- Dropout for regularization
- Output: next-day Close price prediction
## 📊 Results
The model demonstrates reasonable predictive capability, though further tuning (e.g., feature engineering, longer sequences, hybrid CNN-LSTM) may improve volatility tracking. See the included plots for visual comparison between actual and predicted prices.
<img width="1031" height="547" alt="image" src="https://github.com/user-attachments/assets/671f09f0-42d9-4424-bbb5-1e4e640490d0" />

