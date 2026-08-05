# 📈 Portfolio Optimization

> A professional end-to-end Quantitative Finance project implementing Modern Portfolio Theory, Portfolio Optimization, Risk Analytics, CAPM, Value at Risk using Python.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![NumPy](https://img.shields.io/badge/NumPy-2.x-orange)
![SciPy](https://img.shields.io/badge/SciPy-Optimization-red)
![Plotly](https://img.shields.io/badge/Plotly-Dashboard-blueviolet)
![License](https://img.shields.io/badge/License-MIT-success)

---

# 📌 Overview

This project demonstrates the complete workflow of professional portfolio management used in investment banks, hedge funds, quantitative research firms, and asset management companies.

Instead of analyzing only a few stocks, this project builds a diversified investment universe of **100 large-cap US equities** and performs advanced portfolio optimization using Modern Portfolio Theory (MPT).

The project also implements portfolio performance evaluation, advanced risk analytics, CAPM, Value-at-Risk models, Black-Litterman Optimization, GARCH volatility forecasting, stress testing, and portfolio backtesting.

---

# 🚀 Features

## Data Collection

- Download 100 US Stocks using Yahoo Finance
- Automatic Data Cleaning
- Missing Value Treatment
- Daily Returns
- Log Returns
- Annual Returns
- Covariance Matrix
- Correlation Matrix

---

## Portfolio Optimization

Implemented using **SciPy Optimization**

✔ Equal Weight Portfolio

✔ Monte Carlo Portfolio Simulation

✔ Efficient Frontier

✔ Maximum Sharpe Portfolio

✔ Minimum Variance Portfolio

✔ Risk Parity Portfolio

✔ Portfolio Allocation

---

## Portfolio Performance

- Annual Return
- Annual Volatility
- Sharpe Ratio
- Sortino Ratio
- Treynor Ratio
- Information Ratio
- Calmar Ratio
- Maximum Drawdown
- Drawdown Duration
- Rolling Sharpe Ratio
- Rolling Volatility
- Rolling Return

---

## CAPM

- CAPM Alpha
- CAPM Beta
- Expected Return
- Benchmark Comparison

---

## Risk Analytics

- Historical Value at Risk (VaR)
- Parametric VaR
- Student-t VaR
- Monte Carlo VaR
- Conditional Value at Risk (CVaR)

---

## Volatility Forecasting

- ARCH
- GARCH(1,1)
- Conditional Volatility
- Volatility Forecast

---

## Stress Testing

- COVID-19 Crash
- Financial Crisis (2008)
- Market Crash Simulation
- Interest Rate Shock
- Inflation Shock

---

## Portfolio Backtesting

- Monthly Rebalancing
- Quarterly Rebalancing
- Annual Rebalancing
- Portfolio Growth
- Benchmark Comparison

---

## Dashboard

Interactive dashboard built using

- Plotly
- Streamlit

Includes

- Portfolio Allocation
- Efficient Frontier
- Rolling Sharpe
- Rolling Volatility
- Rolling VaR
- Drawdown
- Sector Allocation
- Correlation Heatmap
- Performance Metrics

---

# 📂 Project Structure

```
Quantitative-Portfolio-Optimization/

│
├── notebooks/
│
│   ├── 01_Data_Preprocessing.ipynb
│   ├── 02_Portfolio_Optimization.ipynb
│   ├── 03_Performance_Analytics.ipynb
│   ├── 04_Risk_Management.ipynb
│   ├── 05_GARCH_Model.ipynb
│   ├── 06_Black_Litterman.ipynb
│   ├── 07_Backtesting.ipynb
│   ├── 08_Dashboard.ipynb
│
├── data/
│
│   ├── Prices.csv
│   ├── DailyReturns.csv
│   ├── CovarianceMatrix.csv
│   ├── CorrelationMatrix.csv
│   ├── StockSummary.csv
│
├── output/
│
│   ├── PortfolioComparison.csv
│   ├── MaximumSharpeAllocation.csv
│   ├── MinimumVarianceAllocation.csv
│   ├── RiskParityAllocation.csv
│   ├── PerformanceMetrics.csv
│
├── figures/
│
│   ├── EfficientFrontier.png
│   ├── CorrelationHeatmap.png
│   ├── Drawdown.png
│   ├── RollingSharpe.png
│   ├── PortfolioGrowth.png
│
├── app.py
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

# 📊 Mathematical Models Used

### Modern Portfolio Theory

- Portfolio Return
- Portfolio Risk
- Efficient Frontier

---

### Portfolio Optimization

- Maximum Sharpe Optimization
- Minimum Variance Optimization
- Risk Parity
- Equal Weight
- Monte Carlo Simulation

---

### Asset Pricing

- Capital Asset Pricing Model (CAPM)

---

### Performance Metrics

- Sharpe Ratio
- Sortino Ratio
- Treynor Ratio
- Information Ratio
- Calmar Ratio

---

### Risk Models

- Historical VaR
- Parametric VaR
- Monte Carlo VaR
- Conditional VaR

---

### Volatility Models

- ARCH
- GARCH(1,1)

---

### Portfolio Theory

- Black-Litterman Model

---

# 📚 Libraries Used

```python
numpy

pandas

matplotlib

seaborn

plotly

streamlit

scipy

yfinance

statsmodels

arch

scikit-learn
```

---

# 📈 Workflow

```
Download Data

↓

Clean Data

↓

Calculate Returns

↓

Covariance Matrix

↓

Portfolio Optimization

↓

Efficient Frontier

↓

Performance Evaluation

↓

Risk Analytics

↓

CAPM

↓

VaR Models

↓

GARCH

↓

Stress Testing

↓

Backtesting

↓

Dashboard
```

---

# 📷 Sample Outputs

- Efficient Frontier
- Correlation Heatmap
- Portfolio Allocation
- Rolling Sharpe Ratio
- Rolling Volatility
- Portfolio Growth
- Maximum Drawdown
- Risk Comparison
- VaR Distribution
- GARCH Forecast

---

# ⚙ Installation

Clone repository

```bash
git clone https://github.com/yourusername/Quantitative-Portfolio-Optimization.git
```

Move inside repository

```bash
cd Quantitative-Portfolio-Optimization
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter lab
```

or

```bash
jupyter notebook
```

---

# ▶ Running the Project

Run notebooks in order

```
01_Data_Preprocessing

↓

02_Portfolio_Optimization

↓

03_Performance_Analytics

↓

04_Risk_Management

↓

05_GARCH_Model

↓

06_Black_Litterman

↓

07_Backtesting

↓

08_Dashboard
```

---

# 📊 Skills Demonstrated

- Quantitative Finance
- Portfolio Optimization
- Financial Engineering
- Asset Pricing
- Risk Management
- Financial Modeling
- Python Programming
- Data Analysis
- Statistical Modeling
- Monte Carlo Simulation
- Time Series Analysis
- Machine Learning Basics
- Financial Visualization

---

# 🎯 Applications

This project demonstrates techniques used in

- Hedge Funds
- Investment Banks
- Quantitative Research
- Portfolio Management
- Asset Management
- FinTech Companies
- Robo Advisors
- Wealth Management

---

# 🔮 Future Improvements

- Multi-Factor Models
- Reinforcement Learning Portfolio
- Deep Learning Return Prediction
- LSTM Forecasting
- Option Pricing
- Cryptocurrency Portfolio Optimization
- ESG Portfolio Optimization
- Multi-Asset Portfolio
- Factor Investing
- Real-time Dashboard

---

# 👨‍💻 Author

**Ankit Singh Shekhawat**

B.Tech – Metallurgical & Materials Engineering

Maulana Azad National Institute of Technology (MANIT), Bhopal

Interested in

- Quantitative Finance
- Portfolio Management
- Financial Engineering
- Data Analytics
- Machine Learning
- Investment Research

---

# ⭐ If you found this project useful, consider giving it a Star!