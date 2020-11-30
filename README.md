# San Francisco Rental Analysis with Interactive Visualizations 

## Rental Analysis

The first step in building out the dashboard was to work out all of the calculations and visualizations which are outlined below.

### Housing Units Per Year

Here I calculated the number of housing units per year and visualized the results as a bar chart using the Pandas plot function. I had to use the min, max, and standard deviation of the data to manually scale the y limits of the plot.

### Average Gross Rent in San Francisco Per Year

Here I visualized using a line chart the average gross rent per year to better understand the trends for rental income over time. 

### Average Sales Pricce Per Year

Here I wanted to determine the average sales price per year to better understand the sales price of the rental property over time. I did this by visualizing the mean `sales_price_sqr_foot` as a line chart.

### Average Prices By Neighborhood

Here I grouped the data by year and by neighborhood and calculated the average `sales_price_sqr_foot`.
I used hvplot to obtain the interactive dropdown selector for the neighborhood.

### Top 10 Most Expensive Neighborhoods

Here I calculated the mean sale price for each neighborhood and then sorted the values to obtain the top 10 most expensive neighborhoods on average. Results are shown as a bar chart.

### Parallel Coordinates and Parallel Categories Analysis
