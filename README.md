# QuantFinance-Trading
This project deals with  __Quantative Trading, building a trading strategy by generating alpha, optimizing a portfolio__ . 

This project is divided into four sections :
1. __Trading with Momentum Strategy :__
   - Generated a trading signal based on Momentum Indicator.
   - Tested the strategy to see if it has potential to be profitable.
2. __Break-Out Strategy :__
    - Implemented Break-Out Strategy i.e when stocks break out of range, due to, e.g., a significant news release or from market pressure from a large investor.
3. __Smart-Beta Portfolio Optimization:__
    - Built a portfolio using Quadratic programming to optimize the weights.
    - The portfolio formed was compared to a benchmark index by calculatiing a tracking error against the index.
4. __Multi-Factor Model using PCA:__
    - Created a statistical risk model using Principal Component Analysis.
    - Created factors, then evaluated them using factor-weighted returns, quantile analysis, sharpe ratio, and turnover analysis. 
    - Optimized the portfolio using the risk model and factors using multiple optimization formulations.
5. __Backtesting:__
    - Built a fairly realistic backtester that uses the Barra data. The backtester will perform portfolio optimization that includes transaction costs.
    - Implemented it with computational efficiency in mind, to allow for a reasonably fast backtest. 
    - Performanced attribution to identify the major drivers of your portfolio's profit-and-loss (PnL).

Dataset
-
Since the project was under Udacity's AI for Trading Nanodegree the dataset was provided by thier partners Quotemedia, Barra and Sharadar.

## Installation

```bash
pip install -r requirements.txt
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)