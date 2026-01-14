# NDX Cumulative Returns Dashboard (1990–Present)

## Overview
This project analyzes the historical performance of the Nasdaq-100 Index (NDX) from 1985 to the present using daily price data. I calculated key risk and return metrics, visualized long-term growth, and annotated major market events to highlight volatility and resilience.

The analysis demonstrates quantitative skills and domain knowledge relevant to financial data analysis, directly informed by my 3+ years of day trading experience (building systems, managing drawdowns, and identifying edges).

## Key Metrics
- **Daily Average Return**: 0.07%  
- **Annualized Average Return**: 16.86%  
- **Maximum Drawdown**: -82.90% (dot-com bust peak to trough)  
- **Annualized Volatility (Std Dev)**: 25.92%  
- **Excess Return** (above risk-free rate): 13.86%  
- **Sharpe Ratio**: 0.53  

## Visualizations
Interactive cumulative returns chart with annotations for major events:

- Dot-com Bubble Peak & Bust (2000–2002): -83% drawdown  
- 2008 Global Financial Crisis  
- 2020 COVID Crash + Quantitative Easing Recovery  
- 2022 Bear Market (rate hikes/tightening)  

[View Live Dashboard / Interactive Chart →](https://docs.google.com/spreadsheets/d/1GgfNm8PoIP3C531gaQac8P8ASiWRYYDBL1V1B_nkN4U/edit?usp=sharing)  

## Tools & Methodology
- **Data Source**: Historical daily OHLCV data (sourced from Alpha Vantage / Investing.com)  
- **Tools**: Google Sheets (data cleaning, formulas, conditional formatting, charting)  
- **Calculations**:
  - Daily Return = (Close_t / Close_{t-1}) - 1  
  - Cumulative Return = Previous × (1 + Daily Return)  
  - Annualized Return = Daily Avg × 252  
  - Annualized Std Dev = Daily Std Dev × √252  
  - Sharpe Ratio = (Annualized Return - Risk-Free Rate) / Annualized Std Dev (~3% risk-free proxy)

## Insights & Relevance
Despite extreme volatility (max drawdown -83%), the NDX delivered strong long-term compounded growth. This project reflects skills in data analysis, risk assessment, and storytelling — core competencies I developed through day trading, where managing drawdowns and quantifying edges were critical.

## How to Replicate
1. Download historical NDX data (CSV) from Alpha Vantage or Investing.com  
2. Import into Google Sheets  
3. Apply formulas for returns, cumulative, drawdown, volatility, and Sharpe  
4. Build line chart with conditional formatting and annotations  

## Next Steps / Improvements
- Add drawdown as a secondary line  
- Compare NDX vs. S&P 500  
- Implement basic momentum strategy backtest  

Feedback welcome!  
Last updated: January 13, 2026
