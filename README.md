# StatArbX ⭐
**AI-Powered Statistical Arbitrage Engine**

[![GitHub](https://img.shields.io/badge/GitHub-kantkrishan0206--crypto-blue?logo=github)](https://github.com/kantkrishan0206-crypto) 
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/) 
[![Email](https://img.shields.io/badge/Email-kantkrishan0206@gmail.com-red?logo=gmail)](mailto:kantkrishan0206@gmail.com)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🚀 About StatArbX
**StatArbX** is a cutting-edge **AI-Powered Statistical Arbitrage Engine** for intraday trading.  
It combines **classical statistical arbitrage methods** with **stochastic modeling and AI techniques**, enabling backtesting and simulation of complex trading strategies.

**Core Idea:**  
- Exploit temporary price divergences between **cointegrated assets**.  
- Use **traditional spread models** (pairs trading, cointegration, time series) and **continuous-time models** (Ornstein-Uhlenbeck, Brownian motion).  
- Calculate **option Greeks** with Black-Scholes for derivative strategies.

---

## 🗂 Project Structure

StatArbX/  
│  
├─ data/                     # Intraday datasets (stocks, options, dual listings)  
├─ utils/                    # Arbitrage helper functions (cointegration, regression)  
├─ models/                   # Simulations & parameter estimations  
│   ├─ BM.py                 # Brownian motion functions  
│   ├─ Vasicek.py            # OU-process functions  
│   └─ BS_model.py           # Black-Scholes & option Greeks  
├─ statistical_arbitrage/    # Jupyter notebooks for limit orderbook-based pair trading  
└─ res/                      # Backtesting results (positions, thresholds, PnLs)  

---

## ⚙️ Features

- **Pairs Trading**: Identify cointegrated pairs for spread trading  
- **Continuous-Time Modeling**: OU process & Brownian motion simulations  
- **Option Pricing & Greeks**: Black-Scholes computations for options strategies  
- **Backtesting Engine**: Evaluate strategy performance on intraday data  
- **Analytics & Visualization**: PnL, thresholds, positions with charts  

---

## 🖥 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white)  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)  

---

## 📈 Workflow Diagram

![Workflow Diagram](https://user-images.githubusercontent.com/yourusername/placeholder_workflow.png)  
*From Data → Modeling → Backtesting → Results & Visualization.*

---

## 🚀 Quick Start

**1. Clone the repo**  
git clone https://github.com/kantkrishan0206-crypto/StatArbX.git  
cd StatArbX  

**2. Install dependencies**  
pip install -r requirements.txt  

**3. Run the notebook**  
jupyter notebook statistical_arbitrage/StatArbX.ipynb  

---

## 📊 Example Output

*Spread Portfolios*  
![Spread Portfolios](https://github.com/user-attachments/assets/0f7aee04-6061-4b25-82db-e3e549aa6654)  

*Threshold Analysis*  
![Threshold Analysis](https://github.com/user-attachments/assets/8f2f5572-c4e6-43c0-9914-8838f2449ef0)  

*Position Analysis*  
![Position Analysis 1](https://github.com/user-attachments/assets/2a60cbeb-6da1-4f61-a13d-fab50c175886)  
![Position Analysis 2](https://github.com/user-attachments/assets/95817b6b-df2e-476b-96cd-5c583ef8b29d)  

*PnL Visualization*  
![PnL Visualization 1](https://github.com/user-attachments/assets/88161304-1f3a-4296-b7d7-6177ff5075d0)  
![PnL Visualization 2](https://github.com/user-attachments/assets/fca9baff-a0fa-4640-840d-212db072a0bd)  

---

## 📝 Scripts Overview

- **data/**: Intraday data files (stocks, options, dual-listed stocks)  
- **utils/**: Arbitrage tool functions including cointegration tests and regression analysis  
- **models/**: Simulations and parameter estimations for stochastic models and option Greeks  
- **BM.py**: Brownian motion related functions  
- **Vasicek.py**: OU-process related functions  
- **BS_model.py**: Black-Scholes model and option Greeks  
- **statistical_arbitrage/**: Notebook for realizing pair trading based on limit orderbook stock data  
- **res/**: Results for positions, thresholds, and PnLs  

---

## 👨‍💻 Author & Contact

**Krishan Kant**  

GitHub: [kantkrishan0206-crypto](https://github.com/kantkrishan0206-crypto)  
Email: [kantkrishan0206@gmail.com](mailto:kantkrishan0206@gmail.com)  

---

## 📜 License

MIT License © 2025 Krishan Kant
