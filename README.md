# portfolio_forecasting_and_optimization
Created a web app in which the user can choose a list of stocks, a time range and frequency (days, months, years) and from these inputs calculate the optimal portfolio using the most well-known technique, the mean-variance optimization method. Displayed the efficient-frontier as well the historical return, volatility, Sharpe and Sortino ratios for the optimal portfolio.

We decided to go the extra mile and not only optimize historical portfolios at the end of the look back period but to also:

* forecast future prices over a new time range
* find the optimal portfolio over the overall (historical + forecasted) time range
* find the actual optimal portfolio using the actual prices on the overall time range
* compare the 3 portfolios (return, volatility etc.) over the new period

## Deployed our app using Gradio.
