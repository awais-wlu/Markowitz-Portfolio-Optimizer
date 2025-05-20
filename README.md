# Markowitz Portfolio Optimizer

This project explores portfolio optimization using a combination of machine learning (K-Means clustering) and financial optimization techniques. The objective is to create optimized portfolios with higher risk-adjusted returns compared to an equal-weight benchmark.

## 📊 Overview

- **Dataset**: S&P 500 historical stock data from [Kaggle](https://www.kaggle.com/)
- **Goal**: Compare the performance of optimized portfolios (Minimum Variance and Maximum Sharpe Ratio) against a standard equal-weight portfolio.

## 🧠 Methodology

1. **Clustering with K-Means**:
   - Stocks were grouped using K-Means clustering to identify different behavior patterns.
   - 7 stocks were randomly selected from each cluster to ensure diversity.

2. **Portfolio Optimization**:
   - Constructed two optimized portfolios:
     - **Minimum Variance Portfolio**
     - **Maximum Sharpe Ratio Portfolio**
   - Used mean-variance optimization principles for portfolio construction.

3. **Benchmark Comparison**:
   - Built an **equal-weight portfolio** using all selected stocks.
   - Compared all portfolios’ performance over time.

## 📈 Visualizations

- **Efficient Frontier**: Plotted risk-return tradeoffs of the optimized portfolios.
- **Portfolio Comparison Graph**: Line chart showing cumulative returns of the optimized portfolios vs. the equal-weight portfolio.

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn (for K-Means)
- Matplotlib
- PyPortfolioOpt (if used)
- yfinance or other API/Kaggle source for data

## ✅ Results

- The **Maximum Sharpe Ratio portfolio** outperformed the equal-weight benchmark in terms of risk-adjusted return.
- The **Minimum Variance portfolio** achieved lower volatility but slightly lower returns.
- Clustering helped diversify the stock selection across sectors and behaviors.

## 📁 Files

- `portfolio_optimization.ipynb`: Full code, analysis, and visualizations
- Supporting plots embedded in notebook

---

**This project demonstrates how clustering techniques can enhance portfolio diversification and how optimization can improve investment strategies.**
