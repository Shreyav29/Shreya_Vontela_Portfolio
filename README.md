# [Project 1: Asset Allocation using Convex Portfolio Optimization](https://github.com/Shreyav29/Portfolio_Optimization)
## Objective: 
- In this project we study and compare the asset allocation methodology followed through mean variance portfolio optimization (MVO) and Sharpe Ratio optimization by using the PyPortfolioOpt library in python 

## Methodology: 
- Performed stock selection by choosing eight stocks which span across five industries and have a dispersed range of correlations. Downloaded the stock prices from yfinance library in python. 
- Analysed the stock prices, returns and correlations. 
- Formulated the objective and constraints for mean variance optimisation and solved it using PyPortfolioOpt. Analysed the bias in the results towards high return stocks. 
- Performed sharpe ratio optimization by finding the optimal risk aversion factor in order to get the maximum sharpe portfolio weights. 
- Then validated the same results as above by using PyPortfolioOpt's max_sharpe function 
- Changed the constrains of the portfolio, to allow short selling. Optimized it to realise better sharpe ratio portfolio. 
- Changed the sector constraints of the portfolio, by restricting the weights on tech stocks. This provided better diversification but resulted in a reduction in sharpe ratio. 

## Conclusion: 

![](/Image/port_stats.png)

- We compared the performance of various optimization methods like the traditional mean variance optimization, sharpe ratio optimization and also explored different ways to further enhance the model performance.
- Based on the current analysis, we conclude that the sharpe ratio maximization portfolio with short selling allowed is the most optimal portfolio with sharpe ~2.0 and returns ~87%.

#    
# 


# [Project 2: Web Scraping Bitcoin.com using Selenium and Python](https://github.com/Shreyav29/WebScrapingBitcoin.com)

## Objective:
- In this project I am trying to scrape the Bitcoin.com website and downlaod various paramters belonging to the Bitcoin cryptocurrency. I am going to use this data in a bitcoin price prediction project later. 

## Scraped Features: 
Bitcoin Core (BTC) Price, Market Capitalization, Price Volatility, Daily Transactions,Transaction Value,Total Transactions,Fee Percentage ,Transaction Amount,Hash Rate,Transaction Fees,Miner Revenue,Inflation Rate,Transaction Size,Output Volume,Velocity of Money
