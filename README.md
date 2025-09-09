# Commonwealth Bank Stock Price Prediction Powered by AI

## Project Overview
This project applies **AI and statistical models** to predict the stock price of the Commonwealth Bank of Australia (CBA.AX).  
We aim to benchmark different forecasting methods (ARIMA, LSTM, Transformers, XGBoost) and apply **Explainable AI (XAI)** techniques like SHAP and LIME.  

## Roadmap Stages
Phase 1: Data collection, cleaning, feature engineering, ARIMA baseline  
Phase 2: Add ML/DL models (XGBoost, LSTM, Transformers)  
Phase 3: Explainable AI (LIME, SHAP)  
Phase 4: Azure SQL integration + Power BI dashboard  

## 📂 Project Structure

 Phase 1 (Local, Weeks 1-3)                 Phase 2 (Cloud, Weeks 4-10)
+---------------------------+              +------------------------------+
|  Python (VS Code/Jupyter) |              |   Python (VS Code/Jupyter)   |
| - EDA, Cleaning           |              | - Models (ARIMA, LSTM, etc.) |
| - Feature Engineering     |              | - XAI (LIME, SHAP)           |
| - ARIMA Baseline          |              |                              |
+-------------+-------------+              +-------------+----------------+
              |                                            |
              v                                            v
     +-------------------+                         +-------------------+
     | SQLite Database   |   === Migration ===>    | Azure SQL Database|
     | - stock_prices    |                         | - stock_prices    |
     | - features        |                         | - features        |
     | - predictions (*) |                         | - predictions     |
     +-------------------+                         +-------------------+
                                                            |
                                                            v
                                                +----------------------+
                                                | Power BI Dashboard   |
                                                | - Trends & Forecasts |
                                                | - Feature Importance |
                                                | - Risk Metrics       |
                                                +----------------------+

## ⚙️ How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/ErDipeshPaudel/commonwealth-bank-stock-price-prediction-powered-by-AI.git
   cd commonwealth-bank-stock-price-prediction-powered-by-AI

2. Create virtual environment:
python3 -m venv venv
source venv/bin/activate

3. Install dependencies:
pip install -r requirements.txt

4. Team Contribution

### 2. Commit It
```bash
git add README.md
git commit -m "Added professional README"
git push