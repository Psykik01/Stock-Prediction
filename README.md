# 🧠 Stock Price Prediction Using Machine Learning & Deep Learning

This project explores stock price prediction using three models:

- ✅ Random Forest Regressor (ML)
- ✅ Recurrent Neural Network (RNN)
- ✅ Long Short-Term Memory (LSTM)

The goal is to compare traditional machine learning and deep learning techniques on historical stock data using metrics like MAE, MSE, RMSE, and R².
Always show details

Copy

---

## 📌 Technologies Used

- Python
- NumPy, pandas, matplotlib, seaborn
- TensorFlow/Keras
- Scikit-learn
- Google Colab

---

## 📥 Dataset

- Historical stock price data (e.g., from Yahoo Finance)
- Features used: `Open`, `High`, `Low`, `Close`, `Volume`

---

## 🧪 Model Evaluation Metrics

| Model                  | MAE    | MSE     | RMSE   | R² Score |
|------------------------|--------|---------|--------|----------|
| **RNN**                | 7.66   | 83.05   | 9.11   | 0.6175   |
| **LSTM**               | 5.24   | 46.25   | 6.80   | 0.7869   |
| **Random Forest**      | 28.28  | 1011.10 | 31.80  | -3.1701  |

> ✅ **LSTM outperformed both RNN and Random Forest** with the lowest error and highest R².

---

## 📈 Visual Results

Add these if you have plots:

- 📉 Predicted vs Actual Closing Price
- 🧪 Loss Curve over Epochs
- 📊 Feature Importance (for Random Forest)
