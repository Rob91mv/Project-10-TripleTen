# Maximizing Profitability in Oil Exploration Using Predictive Modeling and Bootstrapping
![](https://i.guim.co.uk/img/media/4ae11065cd3b3025ce9b455626ec99d0c74bf7d8/0_100_3000_1800/master/3000.jpg?width=620&dpr=2&s=none&crop=none)


## Project Overview:

The project, conducted for OilyGiant, aims to identify the most profitable locations for developing 200 new oil wells. Using geological data from three regions, the task involves building a linear regression model to predict oil reserves and selecting the wells with the highest estimated volumes.

Key conditions include a total investment budget of 100 million USD, with revenue calculated at 4,500 USD per unit (thousand barrels). From 500 surveyed points in each region, the top 200 will be chosen to estimate potential profits. A bootstrapping technique will be applied to assess profit distributions and risks, retaining only regions with a loss probability below 2.5%.

The outcome will determine the region offering the highest average net profit with acceptable risk, supporting data-driven decision-making for OilyGiant’s expansion strategy. To assess risk, bootstrapping with 1,000 samples is applied to the top 200 wells per region, estimating the average profit, 95% confidence interval, and loss probability (risk <2.5%). The final recommendation identifies the region with the highest profit margin and lowest risk


## Data Dictionary:

For each 3 different region datasets, the variables are the following:

| Variable | Description                                                                                  |
|----------|----------------------------------------------------------------------------------------------|
| id       | Unique oil well identifier                                                                   |
| f0       | Crude oil quality feature (specific meaning not important, but the characteristic is relevant) |
| f1       | Crude oil quality feature (specific meaning not important, but the characteristic is relevant) |
| f2       | Crude oil quality feature (specific meaning not important, but the characteristic is relevant) |
| product  | Volume of reserves in the oil well (thousands of barrels)  

## Impact

This project successfully identified the most profitable region for developing 200 new oil wells by applying linear regression models, benefit analysis, and bootstrapping risk evaluation.

Key findings include:

- All three regions demonstrated potential profitability, with projected profits exceeding the $100 million investment threshold.

- Region 1 stood out as the most favorable option, achieving an estimated net profit of $103.3M with a 0% loss risk at a 95% confidence level.

- Bootstrapping confirmed that Region 1 consistently offered the highest benefit-to-risk ratio, with confidence intervals for profit significantly above the investment threshold.

- While initial RMSE analysis suggested Region 2 as the strongest candidate, incorporating financial metrics and risk analysis shifted the decision toward Region 1.

Overall, the project shows that combining predictive modeling with financial and risk-based evaluation enables more reliable and informed investment decisions for oil exploration.

"TripleTen" Project #10
