### Note: Click [here](https://github.com/Shreyav29) to go to my Github Repository
### Note: Click [here](https://sites.google.com/berkeley.edu/shreya-vontela/home) to go to my Personal Website


## [Project 1: Asset Allocation using Convex Portfolio Optimization](https://github.com/Shreyav29/Portfolio_Optimization)
### Objective: 
- In this project we study and compare the asset allocation methodology followed through mean variance portfolio optimization (MVO) and Sharpe Ratio optimization by using the PyPortfolioOpt library in python 

### Methodology: 
- Performed stock selection by choosing eight stocks which span across five industries and have a dispersed range of correlations. Downloaded the stock prices from yfinance library in python. 
- Analysed the stock prices, returns and correlations. 
- Formulated the objective and constraints for mean variance optimisation and solved it using PyPortfolioOpt. Analysed the bias in the results towards high return stocks. 
- Performed sharpe ratio optimization by finding the optimal risk aversion factor in order to get the maximum sharpe portfolio weights. 
- Then validated the same results as above by using PyPortfolioOpt's max_sharpe function 
- Changed the constrains of the portfolio, to allow short selling. Optimized it to realise better sharpe ratio portfolio. 
- Changed the sector constraints of the portfolio, by restricting the weights on tech stocks. This provided better diversification but resulted in a reduction in sharpe ratio. 

### Conclusion: 

![](/Image/port_stats.png)

- We compared the performance of various optimization methods like the traditional mean variance optimization, sharpe ratio optimization and also explored different ways to further enhance the model performance.
- Based on the current analysis, we conclude that the sharpe ratio maximization portfolio with short selling allowed is the most optimal portfolio with sharpe ~2.0 and returns ~87%.

## [Project 2: Bitcoin Price Prediction Model](https://github.com/Shreyav29/Bitcoin_Price_Prediction)

### Objective 
- Objective of the project was to build a bitcoin price prediction model.

### Data Collection
#### [Sub Project 2.1: Web Scraping Bitcoin.com using Selenium and Python](https://github.com/Shreyav29/WebScrapingBitcoin.com)

#### Objective of sub project:
- In this project I am trying to scrape the Bitcoin.com website and downlaod various paramters belonging to the Bitcoin cryptocurrency. I am going to use this data in a bitcoin price prediction project later. 

#### Scraped Features: 
- Bitcoin Core (BTC) Price, Market Capitalization, Price Volatility, Daily Transactions,Transaction Value,Total Transactions,Fee Percentage ,Transaction Amount,Hash Rate,Transaction Fees,Miner Revenue,Inflation Rate,Transaction Size,Output Volume,Velocity of Money

### Model Development 
#### Model Setup
- As this is the sequence model. I assumed the past 28 days of data would be affecting next 7 days of data. So the input for the model will be 28 days data and the output would be the next 7 days.

#### Simple Neural Network 
- Even though this is a sequential model , just to test , I started off with a simple 2 dense later NN where I flattened the data to get the vectorised outputs.

#### RNN model with LSTM layer vs GRU Layer 
- Then I moved on to implement a simple RNN with a LSTM hidden layer and a GRU hidden layer. We found that GRU was giving a better

#### RNN model with GRU layer and recurrent dropout 
- Then we added a recurrent dropout which further improved the model . I also used a early stopping condition which stopped the model from overfitting to the data.

### Model Evaluation 
- I evaluated  the models based on the Mean absolute error and RMSE
- Finally to find the accuracy of our model, considering the fact that bitcoin is very volatile, I took a range of 1% around the bitcoin price and saw in how many days our prediction was inside that range. This turned out to be around 90% accurate 



## [Project 3: Designing SPX Futures Roll Strategy](https://github.com/Shreyav29/SPX_Futures_Roll_Strategy)
### Objective: 
- The Project aims to design the optimal monthly roll strategy for SPX futures such that we have minimum roll cost.

## Project 4: Implementing Machine Learning algorithms from scratch:: 
### [Sub Project 4.1: Linear_Regression_from_scratch](https://github.com/Shreyav29/Linear_Regression_from_scratch)
#### Objective: 
- The objective is to better understand the maths behind OLS and implement it in the Gradient Descent approach by using just numpy.
### [Sub Project 4.2: LogisticRegressionFromScratch](https://github.com/Shreyav29/LogisticRegressionFromScratch)
#### Objective: 
- The objective is to better understand the maths behind Logistic regression and implement it in the Gradient Descent approach by using just numpy.
### [Sub Project 4.3: KNN from scratch](https://github.com/Shreyav29/KNNRegression)
#### Objective: 
- In this project we will be solving KNN Regression problem from scratch. We will be implementing the KNN problem in the naive method using a for loop and also in a vectorised approach using numpy broadcasting. We will also plot the root mean squared error for various K values and chose the optimal number of nearest neighbours.

