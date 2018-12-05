# Introduction to Data Analysis with Python

## [01 Tutorial](./01%20Tutorial.ipynb)

- [Getting the data into Python](./tutorial.ipynb#Getting-the-data-into-Python)
    -  using `read_csv` and dealing with missing data
- [Accessing columns](./tutorial.ipynb#Accessing-the-columns)
    -  using dot notation and square brackets
    -  setting the index
    -  using `loc`
- [Sorting and filtering](./tutorial.ipynb#Sorting-and-filtering)
    -  the `sort_values` function
    -  how to get documentation
    -  default arguments
    -  passing a Boolean to `loc[]`
    -  compound filters
- [Summary statistics](./tutorial.ipynb#Summary-statistics)
    -  not so useful for this data set but good to know
- [Investigating relationships](./tutorial.ipynb#Investigating-relationships)
    -  drawing scatter plots in `pandas`
    -  drawing better scatter plots in `seaborn`
    -  getting the correlation coefficient
- [Time series](./tutorial.ipynb#Time-Series)
    -  plotting simple time series
    -  applying a calculation and creating new columns
    
## [02 Blackbirds](./02%20Blackbirds.ipynb)
- [Practice of day 01 techniques](./02%20Blackbirds.ipynb#Practice)
- [Setting a column to datetime format](./02%20Blackbirds.ipynb#Setting-a-column-to-datetime-format)
- [Introducing groupby](./02%20Blackbirds.ipynb#Introducing-groupby)
- [Distribution plots with `distplot`](./02%20Blackbirds.ipynb#Distribution-plots)
    -  Includes, using `subplots` to get two graphs in one figure
- [Hypothesis testing](./02%20Blackbirds.ipynb#Hypothesis-testing)
    -  Using `scipy.stats` to run a t-test
- [Box plots](./02%20Blackbirds.ipynb#Boxplots)
- [Ordinal data](./02%20Blackbirds.ipynb#Ordinal-data)
    -  The age categories happened to make sense in alphabetical order. What if they didn't?
- [Time series](./02%20Blackbirds.ipynb#Time-series)
    -  Now we've grouped by year we can aggregate by mean to plot a time series
