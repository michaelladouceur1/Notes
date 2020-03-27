## Base Strategies
---

>### SMA/EMA Crossover
>- **Description**: A trigger for buying or selling is called when the faster SMA crosses over the slower SMA
>- **Type**: Short-Medium term investments
>- **Reasoning**: A crossover indicates that a large movement trend is likely to occur due to market momentum
>- **Overview**: 
>    - If the faster SMA crosses over the slower SMA into positive territory (SMAFast > SMASlow), the trigger should indicate a potential to buy in order to exploit the likelyhood of an upward trending security
>    - If the faster SMA crosses over the slower SMA into negative territory (SMAFast < SMASlow), the trigger should indicate a potential to sell in order to protect the portfolio from the likelyhood of a downward trending security
>    - 2 SMAs generally are used, but 3 could possibly make the strategy more robust for indicating strong movements
>- **Resources**:
>   - [SMA - Investopedia](https://www.investopedia.com/terms/s/sma.asp)
>   - [EMA - Investopedia](https://www.investopedia.com/terms/e/ema.asp)


>### SMA/EMA Derivative Threshold (Security/Market Momentum)
>- **Description**: A trigger for buying, selling, or alerts is called when an SMA's derivative reaches a specified threshold (either negative or positive)
>- **Type**: Short-Medium term investments
>- **Reasoning**: An SMA derivative threshold could indicate the strength of a movement in a security. It could be used in tandem with other strategies in order to gauge whether a movement is likely to return to a previous position.
>- **Overview**:
>    - If an SMA of a security has a large derivative (positive or negative), it could indicate that there is potential for large movement
>    - If an SMA has a small derivative (positive or negative), it could indicate that the potential for large movement may not be likely 
>    - Historical data could be analyzed to see what threshold would be the best choice. Periods of large movements could be found, and the predecessing derivatives, and their means, could be determined


>### Binomial Tree
>- **Type**: Options; Short term investments
>- **Resources**: 
>   - [Binomial Tree - Investopedia](https://www.investopedia.com/terms/b/binomial_tree.asp)


>### Sharp Ratio
>- **Type**: Long term investments
>- **Overview**:
>    - SR = R<sub>p</sub> - R<sub>f</sub>/&sigma;<sub>p</sub>
>       - R<sub>p</sub> = Return of Portfolio
>       - R<sub>f</sub> = Risk-Free Rate
>       - &sigma;<sub>p</sub> = Standard Deviation of the Portfolio's Excess Return
>- **Resources**: 
>   - [Use Python to calculate the Sharpe Ratio](https://towardsdatascience.com/calculating-sharpe-ratio-with-python-755dcb346805)
>   - [Sharpe Ratio - Investopedia](https://www.investopedia.com/terms/s/sharperatio.asp)


>### Efficient Frontier
>- **Description**: The efficient frontier is the set of optimal portfolios that offer the highest expected return for a defined level of risk or the lowest risk for a given level of expected return
>- **Type**: Long term investments
>- **Reasoning**: While identifying a long-term portfolio, an investor may choose allocation weights that reduce return or expose the portfolio to sub-optimal risk. The efficient frontier can help choose the approximate optimal portfolio by looking at historical returns and volatility and finding the correct security allocations for a portfolio
>- **Overview**: 
>- **Resources**:
>   - [Plotting Markowitz Efficient Frontier with Python](https://towardsdatascience.com/python-markowitz-optimization-b5e1623060f5)
>   - [Efficient Frontier - Investopedia](https://www.investopedia.com/terms/e/efficientfrontier.asp)