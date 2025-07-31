```
algo_trading_bot/
│
├── config/
│   └── settings.py                 # API keys, sheet config, stock list, thresholds
|
├── notebooks/                          # 🔍 Exploration & Visualization
│   ├── 01_EDA_Data_Exploration.ipynb
│   ├── 02_Backtesting_Strategy.ipynb
│   ├── 03_ML_Model_Training.ipynb
│   └── 04_Results_and_Visualization.ipynb              
│
├── data/
│   ├── data_fetcher.py            # Fetch stock data from API (Yahoo/Alpha Vantage)
│   ├── indicators.py              # Compute RSI, MACD, Moving Averages
│   └── backtester.py              # Backtest logic for past data
│
├── strategy/
│   └── rule_based.py              # RSI + Moving Average crossover logic
│
├── ml_model/
│   ├── features.py                # Feature engineering (RSI, MACD, volume)
│   ├── model.py                   # Train & evaluate Logistic Regression or Decision Tree
│   └── predict.py                 # Predict next-day movement
│
├── automation/
│   ├── google_sheets.py          # Google Sheets API logging (gspread, pygsheets)
│   ├── scheduler.py              # Time-based execution or cron trigger
│   └── telegram_alerts.py        # Telegram alert integration
│
├── utils/
│   └── helpers.py                # Date conversion, config loading, etc.
│
├── logs/
│   └── run.log                   # Stores logs for each run
│
├── main.py                       # Entry point: runs fetch, strategy, log, alert
├── requirements.txt              # All dependencies listed
├── README.md                     # Project documentation
└── .env                          # Environment variables (API keys, tokens)

```

