This project combines our knowledge of mathematics, economics, and computer engineering to develop a comprehensive study exploring the predictive power of machine learning in the context of index rebalancing and its subsequent impact on stock prices. Drawing inspiration from our shared fascination with quantitative finance, we sought to construct a robust trading strategy and assess its profitability. Building upon existing research and literature, we embarked on collecting and preprocessing extensive datasets. Through the application of linear regression, we derived an equation that assigned weights to individual input variables based on their efficacy in forecasting price effects. Our findings shed light on the potential for machine learning techniques to enhance understanding and decision-making in the realm of financial markets, presenting a promising avenue for further exploration and refinement of predictive models.
In this study, we created a dataset by collecting publicly available information from YAHOO Finance. The dataset focused on stocks that were added to various indices of the S&P, including the S&P 500, S&P SmallCap 600, and S&P MidCap 400. The data covered the period from May 2021 to January 2023.

The dataset consisted of the following features:
- Stocks being added or removed from the index
- Performance variables, including company performance, sector performance, and index performance, during three distinct periods preceding the release of the rebalance list
- Total market capitalization of the index
- 2-week average volume traded for each stock
- Sum of dividends paid out by the stock over the previous 10 weeks
- Sector, index, and company performance over the previous 1 week, 5 weeks, and 20 weeks

The time-series data (sector, index, and company performance) in the dataset was discretized into three different periods: 1 week, 5 weeks, and 20 weeks. This discretization allowed us to capture different time horizons and analyze their impact on stock price changes.

You can view the results in the report.

