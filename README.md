# Bitcoin Price Forecasting

This project focuses on **time series forecasting** for **Bitcoin (BTC)** prices. By leveraging advanced statistical and machine learning models, we analyze historical price data to predict future price trends. The project covers **data visualization**, **price action analysis**, and **forecasting** using techniques such as ARIMA, SARIMA, and LSTM.

## Project Objectives
- Explore Bitcoin price action through interactive visualizations.
- Forecast Bitcoin prices using:
  - ARIMA (AutoRegressive Integrated Moving Average)
  - SARIMA (Seasonal AutoRegressive Integrated Moving-Average)
  - LSTM (Long Short-Term Memory Neural Networks)
- Compare the performance of the models and discuss their suitability for time series forecasting.

---

## Table of Contents
1. [Dataset](#dataset)
2. [Installation](#installation)
3. [Methodology](#methodology)
4. [Conclusion](#conclusion)

---

## Dataset
The dataset contains historical Bitcoin price data, including:
- Open, High, Low, Close prices
- Trading volume
- Timestamps for each observation

### Data Source:
- Public APIs (e.g., Binance, CoinGecko) or CSV files with historical data.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/btc-price-forecasting.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

### Required Libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `tensorflow` (for LSTM)
- `scikit-learn`

---

## Methodology

### 1. Data Exploration and Preprocessing
- Analyze historical BTC prices and trends.
- Handle missing values and normalize data for model training.
- Visualize price action using Line charts

### 2. ARIMA Model
- Apply the Box-Jenkins methodology:
  - Identify AR, MA, and differencing orders using ACF and PACF plots.
  - Fit the ARIMA model to the data.
  - Evaluate using metrics like RMSE and MAPE.

### 3. SARIMA Model
- Extend ARIMA to account for seasonality:
  - Identify seasonal patterns and set SARIMA hyperparameters.
  - Forecast BTC prices and validate results.

### 4. LSTM Model
- Utilize deep learning for sequence prediction:
  - Prepare data using sliding windows.
  - Build and train an LSTM model with TensorFlow.

---



### Key Findings:
- SARIMA perform well for short-term forecasts.
- LSTM captures complex patterns but requires more data and computational power.

---

## Conclusion
This project demonstrates the potential of time series models to forecast Bitcoin prices. While ARIMA and SARIMA are effective for traditional forecasting, LSTM provides a modern approach to capturing intricate patterns. Future work could involve:
- Incorporating external factors (e.g., trading volume, sentiment analysis).
- Using hybrid models to improve accuracy.


---

## How to Contribute
Feel free to open issues or submit pull requests for improvements and additional features.

---

## Acknowledgments
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Statsmodels Documentation](https://www.statsmodels.org/)
- [Kaggle Datasets](https://www.kaggle.com/)
