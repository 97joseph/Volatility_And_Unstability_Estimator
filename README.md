# Volatility_And_Unstability_Estimator

A predictive model for financial markets that chooses to capture the volatility movements to aid in future predictive actions through insight generation and calculated projections.

## BACKGROUND

[Volatility](https://www.optiver.com/insights/guides/options-volatility/) is one of the most prominent terms you’ll hear on any trading floor – and for good reason. In financial markets, volatility captures the amount of fluctuation in prices. High volatility is associated to periods of market turbulence and to large price swings, while low volatility describes more calm and quiet markets. For trading firms like Optiver, accurately predicting volatility is essential for the trading of options, whose price is [directly related to the volatility](https://www.optiver.com/insights/guides/options-pricing/) of the underlying product.

As a leading global electronic market maker, Optiver is dedicated to continuously improving financial markets, creating better access and prices for options, ETFs, cash equities, bonds and foreign currencies on numerous exchanges around the world. Optiver’s teams have spent countless hours building sophisticated models that predict volatility and continuously generate fairer options prices for end investors. However, an industry-leading pricing algorithm can never stop evolving, and there is no better place than Kaggle to help Optiver take its model to the next level.

In the first three months of this competition, you’ll build models that predict short-term volatility for hundreds of stocks across different sectors. You will have hundreds of millions of rows of highly granular financial data at your fingertips, with which you'll design your model forecasting volatility over 10-minute periods. Your models will be evaluated against real market data collected in the three-month evaluation period after training.

Through this competition, you'll gain invaluable insight into volatility and financial market structure. You'll also get a better understanding of the sort of data science problems Optiver has faced for decades. We look forward to seeing the creative approaches the Kaggle community will apply to this ever complex but exciting trading challenge.

## Getting started

In order to make Kagglers better prepared for this competition, Optiver's data scientists have created a [**tutorial notebook**](https://www.kaggle.com/jiashenliu/introduction-to-financial-concepts-and-data) debriefing competition data and relevant financial concepts of this trading challenge. Also, Optiver's online course can tell you more about financial market and market making.

For more information about exciting data science opportunities at Optiver, check out their data science landing page [here](https://hubs.li/H0R7Fjx0) or e-mail their recruiting team directly at datascience@optiver.com.



EVALUATION


Submissions are evaluated using the root mean square percentage error, defined as:

RMSPE=1n∑i=1n((yi−y^i)/yi)2

Where RMSPE={}root }{mean} {square} {percentage} {error}

## Submission File

For each `row_id` in the test set, you must predict the `target` variable. The file should contain a header and have the following format:

```
row_id,target
0-0,0.003
0-1,0.002
0-2,0.001
...
```
