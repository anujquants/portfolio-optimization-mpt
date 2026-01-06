# portfolio-optimization-mpt
Mean-Variance portfolio optimization on Indian equities using Modern Portfolio Theory with live Yahoo Finance data in Python.
# Portfolio Optimization using Modern Portfolio Theory (MPT)

## Objective
To construct an optimal equity portfolio using Modern Portfolio Theory by dynamically fetching market data and maximizing risk-adjusted returns.

## Data Source
- Daily adjusted closing prices fetched directly from Yahoo Finance using `yfinance`
- Eliminates manual datasets and ensures real-time reproducibility

## Assets Considered
A diversified basket of Indian equities including:
Infosys, Reliance, HDFC Bank, ICICI Bank, SBI, Bajaj Finance, TCS, ITC, and others (20 stocks)

## Methodology
- Retrieved historical price data using Yahoo Finance API
- Computed log returns
- Estimated expected returns and covariance matrix
- Simulated multiple portfolios
- Constructed Efficient Frontier
- Identified Maximum Sharpe Ratio portfolio

## Key Financial Concepts
- Risk vs Return Tradeoff
- Diversification
- Covariance & Correlation
- Efficient Frontier
- Sharpe Ratio

## Tools & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- yfinance

## Results & Insights
- Optimized asset weights favor low-correlation stocks
- Diversification reduces portfolio volatility without sacrificing returns
- Efficient frontier illustrates risk-return optimization

## Limitations
- Assumes normal return distribution
- Ignores transaction costs and liquidity constraints
- Static covariance estimation

## Possible Enhancements
- CAPM-based expected returns
- Black-Litterman framework
- Monte Carlo simulations
- Constraint-based optimization

## Author
Anuj Patel  
Finance | Investment Banking | Quantitative Analysis
