## The problem statement is to design a Python-based mini algo-trading prototype that incorporates machine learning and automation.

###Here's a breakdown of what needs to be done and how:

### 1. Problem Statement:
- Design a Python-based mini algo-trading prototype  that:

- Connects to a stock data API.

- Implements a sample trading strategy (RSI + Moving Average crossover).

- Stores and analyzes trades automatically in Google Sheets.

- Generates portfolio analytics and buy/sell signals using ML or rule-based logic.

### 2. How to Do It (Deliverables & Instructions):

#### Data Ingestion:

- Fetch intraday or daily stock data for at least 3 NIFTY 50 stocks using any free API (e.g., Alpha Vantage, Yahoo Finance, or dummy JSON).

#### Trading Strategy Logic:

- Implement a buy signal when RSI is less than 30.

- Confirm this buy signal with the 20-DMA (Daily Moving Average) crossing above the 50-DMA.

- Backtest the strategy for 6 months.

#### ML Automation (Bonus):

- Develop a basic machine learning model (Decision Tree or Logistic Regression) to predict next-day stock movement.

- Use indicators like RSI, MACD, and Volume as features for the model.

- Output the prediction accuracy of the model.

#### Google Sheets Automation:

- Log trade signals and Profit & Loss (P&L) to Google Sheets.

- Include a trade log, a summary of P&L, and the win ratio in separate tabs within the Google Sheet.

#### Algo Component:

- Create an auto-triggered function that scans data, runs the trading strategy, and logs the output.

#### Code Quality:

- Ensure the code is modular, well-documented, and includes logging.

### 3. Submission and Presentation:

- Submit the complete code in a GitHub repository or as a ZIP file with a README.

- Record and share 1-2 short videos explaining:

- The strategy logic and code flow.

- The output on the console and Google Sheets.

- Share the video links via Google Drive or YouTube (Unlisted).

### 4. Time Limit:

- 3-5 days from the receipt of the assignment.

### 5. Bonus Task:

- Integrate Telegram alerts for signal alerts or error notifications.