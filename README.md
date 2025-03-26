# Regression-and-return-based-on-PB-ratio

**Empirical Study on A-share Valuation Factors and Portfolio Construction**  
`Period: 2010-2023` | [📊 Dataset] | [📈 Methodology]

---

## 🎯 Research Objectives
This project investigates two critical aspects of China's A-share market:
1. **Valuation Drivers Analysis**  
   Identify how fundamental metrics (ROE-TTM, stock volatility) explain cross-sectional variations in P/B ratios through multivariate regression.

2. **Dynamic Portfolio Strategy**  
   Construct and backtest decile portfolios based on P/B ratios to examine the relationship between valuation levels and subsequent returns.

---

## 📂 Data Pipeline
### Data Sources (CSMAR Database)
- **Monthly Stock Data** (2009.12-2023.12)
  - Closing prices
  - Returns (without dividend reinvestment)
- **Quarterly Financials** (2009Q3-2023Q4)
  - ROE-TTM (Trailing Twelve Months)
  - Net assets per share
- **Daily Risk Metrics**  
  - 250-day log return volatility (as of 2010-12-31)

