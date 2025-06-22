# 📈 Cryptocurrency Forensics: Predictive Analysis of Bitcoin

A complete end-to-end data science and machine learning project focused on **Bitcoin price prediction** using **time series forecasting** and **social sentiment analysis**. This project covers data collection, EDA, feature engineering, model development (ARIMA, LSTM, Prophet), backtesting, and deployment using **Streamlit/Flask**.

---

## 🧠 Project Goal

To analyze historical and real-time Bitcoin price behavior by incorporating:
- Market data (CoinGecko, Yahoo Finance, CoinMarketCap)
- Social media sentiment (Twitter API)
- Technical indicators (RSI, Moving Averages)
- Macroeconomic influences (regulatory trends, global events)

---

## 🚦 Project Status

✅ **Completed**  
This project is complete and production-ready, with room for further enhancements such as real-time model integration and automated alerts.

---

## 🔁 Project Pipeline

### 🔍 1. Data Collection & Preprocessing
- 📊 APIs Used: CoinMarketCap, CoinGecko, Yahoo Finance
- 🔄 Cleaned missing values, standardized timestamps, normalized features
- 🧠 Collected and processed **Twitter sentiment** data using NLP

### 📊 2. Exploratory Data Analysis (EDA)
- Correlation between price and sentiment, volume, macro indicators
- Visualizations: candlestick charts, line graphs, seasonal decompositions
- Analyzed key historical Bitcoin events and their price impact

### 🛠️ 3. Feature Engineering
- Technical indicators: Moving Averages, RSI, EMA, MACD
- Seasonality, volatility, and trading volume signals

### 🤖 4. Model Development
- **Statistical models**: ARIMA, SARIMA, FB Prophet
- **Machine Learning models**: Random Forest, XGBoost
- **Deep Learning**: LSTM and GRU for sequential modeling

### 🔧 5. Model Optimization & Tuning
- Used Grid Search and Random Search for hyperparameter tuning
- Evaluated with RMSE, MAE, MAPE on validation and test sets
- Cross-validation applied for robustness

### 📈 6. Backtesting
- Simulated historical predictions and compared with actuals
- Improved performance by retraining on recent data windows

### 🚀 7. Deployment & Dashboard
- Built a clean, interactive dashboard using **Streamlit**
- Allows users to:
  - Upload data
  - Visualize trends
  - Generate forecasts
  - Analyze real-time social sentiment
- Optionally deployable via Flask for web APIs

---

## ⚙️ Technologies Used

| Category          | Tools / Libraries                             |
|-------------------|-----------------------------------------------|
| 📌 Programming     | Python                                        |
| 📚 Libraries       | Pandas, NumPy, Scikit-learn, TensorFlow, Keras, Statsmodels, Prophet |
| 📈 Time Series     | ARIMA, SARIMA, FB Prophet, LSTM, GRU          |
| 📉 Feature Tools   | TA-Lib, yfinance, Yahoo_fin, Tweepy           |
| 📊 Visualization   | Plotly, Seaborn, Matplotlib, Tableau (external) |
| 🌐 APIs            | CoinMarketCap, Yahoo Finance, Twitter API     |
| 🧠 Sentiment       | VaderSentiment, TextBlob, HuggingFace Transformers (optional) |
| 🚀 Deployment      | Streamlit / Flask                             |
| 🐳 Containerization| Docker (future enhancement)                   |

---

## 📂 Directory Structure

cryptocurrency-forensics/
├── notebooks/ # Jupyter notebooks for each stage
├── data/ # Raw and processed datasets
├── models/ # Saved models (ARIMA, LSTM, Prophet)
├── app/ # Streamlit or Flask app
│ └── dashboard.py
├── utils/ # Feature engineering and helpers
├── requirements.txt
├── Dockerfile # (optional)
└── README.md

---

## 📊 Results and Insights

- ✅ LSTM models captured volatility and outperformed ARIMA in short-term forecasting
- 📈 Prophet effectively handled trend + seasonality components
- 💬 Twitter sentiment showed correlation with price spikes/dips during major events
- 🧠 Combined multi-model ensemble improved prediction stability

---

## 🔧 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/cryptocurrency-forensics.git
cd cryptocurrency-forensics
pip install -r requirements.txt
streamlit run app/dashboard.py

---

### ✅ What’s Next?

Would you like me to generate:
- A **matching dashboard UI in Streamlit or Flask**?
- Sample notebooks for **LSTM**, **ARIMA**, and **Prophet**?
- A **live deployment guide** using Hugging Face Spaces, Render, or AWS?

Let me know, and I’ll generate the next steps for full production-readiness!


 
