# Forex Price Prediction using LSTM



## Overview
This project focuses on predicting Forex prices (EUR/USD) using machine learning models, specifically Long Short-Term Memory (LSTM). The project includes steps such as data collection, preprocessing, feature engineering, model training, evaluation, and strategy backtesting to simulate a trading environment.

## Objectives
- Build a predictive model to forecast Forex prices.
- Enhance model accuracy using feature engineering.
- Simulate a trading strategy and evaluate its profitability.

## Features
1. **Data Collection**:
   - Historical Forex data fetched using the Alpha Vantage API.
2. **Feature Engineering**:
   - Added technical indicators such as SMA, EMA, RSI, MACD, and Bollinger Bands.
3. **Model Training**:
   - LSTM model trained to predict the next closing price.
4. **Strategy Backtesting**:
   - Trading strategy simulated with Stop-Loss and Take-Profit rules.
5. **Evaluation**:
   - Compared strategy returns with market returns.

## Results
- **LSTM Model Performance**:
  - Mean Squared Error: `0.00035`
- **Trading Strategy Performance**:
  - Initial Balance: `$10,000`
  - Final Balance: `$11,068.32`
  - Profit: `$1,068.32`

## Technology Stack
- **Programming Language**: Python
- **Libraries**: TensorFlow/Keras, Scikit-learn, Pandas, NumPy, Matplotlib
- **Data Source**: Alpha Vantage API

## Repository Structure
```
.
├── Stock Forex Price Prediction using ML & Deep Learning.ipynb
```

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yashkusumkar02/Forex-Price-Prediction-using-LSTM/
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the scripts in the following order:
   - `data_fetching.py`: Fetches Forex data.
   - `feature_engineering.py`: Adds technical indicators.
   - `lstm_model.py`: Trains the LSTM model.
   - `backtesting.py`: Simulates the trading strategy.

## Usage
1. Adjust parameters in the scripts, such as Stop-Loss and Take-Profit levels, to test different strategies.
2. Run the scripts to visualize predictions, evaluate strategy performance, and generate results.
3. Analyze outputs to assess model performance and trading profitability.

## Future Enhancements
- Automate trading using real-time data and APIs.
- Add support for other currency pairs and financial instruments.
- Improve strategy robustness with ensemble models (e.g., combining LSTM and XGBoost).

## Conclusion
This project demonstrates the application of machine learning in Forex price prediction and the importance of risk management in trading strategies. By incorporating Stop-Loss and Take-Profit mechanisms, the trading strategy achieved profitability, showcasing the practical utility of predictive models in financial markets.

---

### Author
Developed by Suyash Kusumkar.

