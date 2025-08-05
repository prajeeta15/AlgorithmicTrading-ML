# AlgorithmicTrading-ML
Machine Learning &amp; Quant Strategies 

# unsupervised learning: 
in trading involves using ML techniques to analyze financial data and discover patterns, relationships, and structures within the data without any labeled or predefined target variable. it focuses on extracting insights from data

# how is unsupervised learning applied in trading:
- clustering
- dimensionality reduction
- anomaly detection
- market regime detection
- portfolio optimization

# process:
download SP500 stocks price data
calc different technical indicators and features for each stock
aggregate on monthly level and filter for each month only top 150 most liquid stocks
calc monthly returns for different time horizons to add to features
download fama-french factors and calc rolling factor beats for each stock
for each month fit a k means clustering model to group simialr assets based on their features
for each month select assets based on their cluster and forma a portfolio based on efficient frontier max sharpe ratio portfolio optimization
visualize the portfolio returns and compare to SP500 returns
#limitation: using most recent SP500 stocks list might have survivorship bias in the list but in reality we have to use survivorship free data

# survivorship bias-
condition when a stock which have actually went out of SP500 list becuase it was failing and is currently not in the list

# later:

### - Twitter Sentiment Investing Strategy, ranking NASDAQ stocks based on engagement and evaluating performance against the QQQ return
### - Intraday Strategy with GARCH model combining with technical indicators to capture both daily and intraday signals for potential lucrative positions
