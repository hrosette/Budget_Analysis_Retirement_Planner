![image](https://user-images.githubusercontent.com/65314799/100649561-3a8ce800-3308-11eb-9c03-d21703072f34.png)

# Budget Analysis and Retirement Planner

## Budget Analysis

In this section of the project, I used the Plaid API to obtain transaction and account data that will be used for my budget analysis.

![image](https://user-images.githubusercontent.com/65314799/100649490-22b56400-3308-11eb-84b4-2e60e6ad8d81.png)


![image](https://user-images.githubusercontent.com/65314799/100649314-e3871300-3307-11eb-8d17-3589dab51ed6.png)

**Previous year's gross income was:** $7893

**Current monthly income is:** $500

**Projected yearly income is:** $6085

## Retirement Planner 

In this section of the project, I used the Alpaca API to fetch historical closing prices for a retirement portfolio and then ran Monte Carlo simulations to project the portfolio performance at 30 years.

### Monte Carlo Simulation

* Monte Carlo Simulation of 500 runs and 30 years for a 60/40 portfolio. 

![image](https://user-images.githubusercontent.com/65314799/100649416-09141c80-3308-11eb-8473-c7459829d5db.png)


* Using the ending cumulative returns, I plotted a histogram of the results and plotted the 90% confidence interval as vertical lines on the histogram.

![image](https://user-images.githubusercontent.com/65314799/100649370-f7327980-3307-11eb-8c6f-e1c8faf325a4.png)


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
