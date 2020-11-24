# Covid 19 and Its Impact on Finance, Tech, Real Estate, and BioTech

## Summary
Our project is to help retail investors (i.e Robinhood, Qapital, Acorn) in guiding their investments during potential future pandemics. Based on stock data analysis we will recommend the rebalancing of a theoretical portfolio to outperform the market. We chose 4 of the top 10 most influential sectors and we created an equally weighted theoretical portfolio.

## Findings and Data Analysis
For simplicity used the following ETFs to track these market sectors, but the analysis can be easily expanded :
Finance (XLF)
Tech (XLK)
Vanguard Real Estate ETF (VNQ)
Biotech (IBB)
We used the SPY to represent the U.S. market.

### Statistical Techniques and Representations
Performed statistical analysis for before and during Covid periods:
Percentage Change
Standard Deviations
Variance and Covariance
Beta Values
Sharpe Ratios
Volatility
Correlations
ARIMA Model

### How a hypothetical stock portfolio should be rebalanced after a pandemic hits?
Based on our analysis we have recommended to rebalance the portfolio as follows. 
S&P 500:            0%       to       50%
Finance(XLF):       25%      to       0%
Real Estate(VNQ):   25%      to       0% 
Tech(XLK):          25%      to       25%
Biotech(IBB):       25%      to       25%
The total profit resulting from our analysis was $134,174

### Data Exploration and Cleanup
We gathered closing prices for all our ETF’s from Google Finance ranging from
January 2017- November 3rd 2020. We created precovid dataframes for each ETF in order to segment our historical data(January 1,  2017- January 22, 2020).  January, 22 2020 was the first documented Covid 19 case in the United States. The next step was to concatenate all data into a precovid dataframe with the date as our index.  We then created present covid 19 dataframes for each ETF ranging from January 22, 2020 - November 3, 2020 and merged them as well. Then we created and cleaned the Covid 19 Dataframe which included total cases and deaths nationwide. The final step was to concatenate the closing prices dataframe and the covid 19 dataframe.

## Future Explorations
#### What Could We Have Analyzed With More Time 
While the initial market impact of COVID has been clear we suspect that while some of the changes may be permanent (i.e. people will shop more online for example) others will not (i.e. people will go back to eat in restaurants).  Also, it’s clear that government intervention can soften the market impact as well. 
With more time we would’ve liked to try to estimate some of these and dynamically adjust the portfolios to improve potential returns.

