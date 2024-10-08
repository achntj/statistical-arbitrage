# Statistical Arbitrage Strategy

This project implements a multi-phase Statistical Arbitrage (StatArb) strategy using machine learning, econometrics, and quantitative finance techniques. The strategy identifies and trades pairs of cointegrated assets, leveraging mean-reversion principles and risk management techniques to optimize portfolio performance.

## Other Techniques / Tests

1. **Linked Asset Identification**  
   Utilized K-Means Clustering on key financial features such as returns, volatility, beta, and rolling correlations to identify linked asset pairs.

2. **Cointegration Testing**  
   Applied the Engle-Granger test to determine cointegration between asset pairs, ensuring long-term stability of their price relationships.

3. **Pair Trading Strategy**  
   Constructed a pair trading strategy based on price ratios. Positions (long/short) are opened when the ratio deviates from its historical mean, expecting it to revert over time.

4. **Risk Management**  
   Incorporated Value at Risk (VaR) and Conditional Value at Risk (CVaR) to dynamically manage risk and adjust position sizes based on volatility.

5. **Backtesting**  
   The strategy was backtested using historical data, with performance metrics such as Sharpe Ratio, Maximum Drawdown, and Annualized Returns calculated to evaluate success.
