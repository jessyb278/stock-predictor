# Stock Predictor 

Machine learning–based stock analysis and prediction using historical Yahoo Finance data, Random Forest modeling, and backtesting.

---

## 📊 Overview
This project uses Python, scikit-learn, and yfinance to analyze stock market data and predict future price movements.  
It fetches long-term historical data from Yahoo Finance, engineers trend-based features, and evaluates a Random Forest Classifier through rolling backtests.

---

## Features
- Fetches full stock history automatically from Yahoo Finance (`yfinance`)
- Cleans and prepares price, volume, and date-indexed data
- Generates technical indicators over multiple time horizons
- Implements a Random Forest model for directional prediction
- Performs backtesting to simulate realistic rolling forecasts
- Calculates precision scores and visualizes performance

---

## Project Structure
```bash
StockPredictor/
├── .gitignore
├── Stock_analysis.ipynb     # Main notebook – full data analysis and modeling
├── venv/                    # (ignored) virtual environment
└── README.md
```

### Option 1 – Run in Jupyter / VS Code
1. Clone the repository  
   ```bash
   git clone https://github.com/jessyb278/stock-predictor.git
   cd stock-predictor
   ```
2. Install dependencies
```bash
pip install yfinance scikit-learn pandas matplotlib
```

---

### Option 2 – Import into IntelliJ or PyCharm

- Open the project directory  
- Ensure your virtual environment (`venv/`) is selected  
- Run each cell or script directly in the IDE  
