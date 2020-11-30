# Budget Analysis and Retirement Planner

## Budget Analysis

In this section of the project, I used the Plaid API to obtain transaction and account data that will be used for my budget analysis.

## Retirement Planner 

In this section of the project, I used the Alpaca API to fetch historical closing prices for a retirement portfolio and then ran Monte Carlo simulations to project the portfolio performance at 30 years.

### Monte Carlo Simulation

* Monte Carlo Simulation of 500 runs and 30 years for a 60/40 portfolio. 
* Using the ending cumulative returns, I plotted a histogram of the results and plotted the 90% confidence interval as vertical lines on the histogram.

## Retirement Analysis

The expected cumulative returns at 30 years for the following percentiles:
* 10th percentile = 2.08923
* 50th percentile = 7.622968
* 90th percentile = 29.44046

Given an initial investment of $20,000, the expected portfolio returns in dollars for the following percentiles are:
* 10th percentile = 41784.596576
* 50th percentile = 152459.353509
* 90th percentile = 588809.209971

Given the current projected annual income from the Plaid analysis, a 4% withdraw rate from the retirement portfolio does not meet or exceed the value at the 10th percentile. Retirement income would be $1671.38 and current projected income is $6085. A 50% increase in the initial investment amount will increase the 4% retirement withdrawal from $1671.38 to $2507.07. This still does not meet the current projected income of $6085
