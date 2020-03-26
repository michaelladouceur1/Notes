## Base Strategies
---

>### SMA Crossover
>- **Description**: A trigger for buying or selling is called when the faster SMA crosses over the slower SMA
>- **Reasoning**: A crossover indicates that a large movement trend is likely to occur due to market momentum
>- **Overview**: 
    - If the faster SMA crosses over the slower SMA into positive territory (SMAFast > SMASlow), the trigger should indicate a potential to buy in order to exploit the likelyhood of an upward trending security
    - If the faster SMA crosses over the slower SMA into negative territory (SMAFast < SMASlow), the trigger should indicate a potential to sell in order to protect the portfolio from the likelyhood of a downward trending security
    - 2 SMAs generally are used, but 3 could possibly make the strategy more robust for indicating strong movements
>- **Resources**:

>### SMA Derivative Threshold (Security/Market Momentum)
>- **Description**: A trigger for buying, selling, or alerts is called when an SMA's derivative reaches a specified threshold (either negative or positive)
>- **Reasoning**: An SMA derivative threshold could indicate the strength of a movement in a security. It could be used in tandem with other strategies in order to gauge whether a movement is likely to return to a previous position.
>- **Overview**:
    - If an SMA of a security has a large derivative (positive or negative), it could indicate that there is potential for large movement
    - If an SMA has a small derivative (positive or negative), it could indicate that the potential for large movement may not be likely 
    - Historical data could be analyzed to see what threshold would be the best choice. Periods of large movements could be found, and the predecessing derivatives, and their means, could be determined

>### Binomial Tree

>### Sharp Ratio
>- **Resources**: 
>    - [Binomial Tree - Investopedia](https://www.investopedia.com/terms/b/binomial_tree.asp)