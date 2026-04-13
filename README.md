# 🌾 Cotton Price Prediction Using Time Series Models

> Forecasting agricultural commodity prices using classical and deep learning approaches — ARIMA, VAR, and LSTM — to support data-driven decisions in the cotton industry.

---

## 📌 Project Overview

Cotton price volatility directly impacts farmers, traders, textile manufacturers, and policymakers. This project builds and compares multiple time series forecasting models to predict cotton prices across two market segments, providing actionable insights for stakeholders in the agricultural economy.

**Key Question:** Which forecasting model best balances accuracy, interpretability, and practical usability for cotton price prediction?

---

## 🚀 Tech Stack

| Category | Tools & Libraries |
|----------|------------------|
| Language | Python 3.x |
| Deep Learning | TensorFlow / Keras (LSTM) |
| Statistical Modeling | Statsmodels (ARIMA, VAR) |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Notebook | Jupyter Notebook |

---

## 🧠 Models Implemented

### 1. ARIMA (Autoregressive Integrated Moving Average)
- Classical statistical approach for univariate time series
- Optimized using AIC/BIC criteria to balance fit vs. complexity
- Best suited for stakeholders needing **interpretable, audit-friendly** predictions

### 2. VAR (Vector Autoregression)
- Multivariate model capturing **interdependencies** between cotton prices and related economic indicators
- Reveals how variables influence each other over time
- Useful for understanding **macro-level market dynamics**

### 3. LSTM (Long Short-Term Memory Neural Network)
- Deep learning model designed to capture **complex nonlinear patterns** in sequential data
- Achieved the **lowest RMSE** among all tested models
- Best suited for applications where **predictive accuracy is the top priority**

---

## 📊 Results Summary

| Model | Strength | RMSE | Best For |
|-------|----------|------|----------|
| ARIMA | Interpretability + AIC/BIC optimization | Moderate | Explainable forecasts |
| VAR | Multi-variable interdependency analysis | Higher | Market relationship insights |
| LSTM | Nonlinear pattern recognition | **Lowest** | High-accuracy forecasting |

> **LSTM outperformed classical models** in predictive accuracy, while ARIMA offered the best balance of simplicity and performance.

---

## 📂 Project Structure

```
cotton-price-prediction/
│
├── code.ipynb        # End-to-end pipeline: EDA, ARIMA & VAR training, evaluation
├── LSTM.py           # Standalone LSTM model training and prediction script
└── README.md         # Project documentation
```

---

## ⚙️ Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib statsmodels tensorflow
```

### Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/cotton-price-prediction.git
   cd cotton-price-prediction
   ```

2. **Prepare your data**
   - Add historical cotton price data (CSV format) to the project directory
   - Ensure date and price columns are correctly formatted

3. **Train & Evaluate Models**
   - Open `code.ipynb` in Jupyter Notebook for ARIMA and VAR models
   - Run `LSTM.py` for the deep learning model:
     ```bash
     python LSTM.py
     ```

4. **Evaluate Results**
   - Compare models using **RMSE** (lower = better accuracy)
   - Use **AIC/BIC** to assess ARIMA model fit

---

## 💡 Key Learnings & Takeaways

- Deep learning (LSTM) significantly outperforms classical models in **raw predictive accuracy** for commodity pricing
- Classical models (ARIMA) remain valuable where **explainability and regulatory compliance** matter
- Multivariate approaches (VAR) provide richer insights when **correlated economic factors** are available
- Hyperparameter tuning and data preprocessing are critical bottlenecks in time series forecasting pipelines

---

## 👥 Team

| Name |
|------|
| Nishtha Ahuja |
| Rachit Patel |
| Pradip Patelia |
| Dip Patel |
| Dhruvi Shah |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

*Built as part of an academic exploration into machine learning applications in agricultural economics.*
