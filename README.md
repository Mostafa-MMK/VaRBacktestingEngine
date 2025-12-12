# 📊 Value-at-Risk (VaR) Backtesting Engine

This project implements a full **VaR estimation and backtesting framework** commonly used in market risk management. It includes: 
- Multiple VaR models,
- Daily PnL-based backtesting, and
- Regulatory tests (Kupiec, Christoffersen).

---

## 🚀 Features

### ✔ VaR Models
- Historical Simulation VaR
- Filtered Simulation VaR  
- EWMA VaR (λ = 0.94 / configurable)  
- GARCH(1,1) Parametric VaR  
- Monte Carlo VaR (Gaussian & t-distribution)  

### ✔ Backtesting & Risk Validation
- **Unconditional Coverage Test (Kupiec)**
- **Independence Test (Christoffersen)**
- **Conditional Coverage Test**
- Exception counting & traffic-light classification (Basel)

### ✔ Additional Functionality
- Risk report generation (tables + plots)
