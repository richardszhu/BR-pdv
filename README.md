# Investment Portfolio Diversity Visualization Tool
## REQUIRES MatPlotLib
Installation instructions: https://matplotlib.org/users/installing.html

Utilizes Blackrock API to "fetch data" and create a tool to visualize diversity of numerous security data attributes of an investment portfolio, including global diversity and sector diversity

Created by Riley Dyer, Richard Zhu, Shreyash Sridhar, and David Zhu, all in one day at CalHacks 6.0

## To Use:
Load vis_clean.ipynb in Jupyter Notebooks


## To Do:

make a way to pass in tickers to create a portfolio. Possibly a front end.

Options of what to measure diversity of: country, currency, exchangeAcronym, issFtse1Industry, issFtse3Sector

create a list of countries in the portfolio and find a way to calculate the percentage + number of stocks from those countries

visualize the diversity in NumPy or another tools

## Resources Used
http://rockthecode.io/api/

https://www.blackrock.com/tools/api-tester/hackathon?apiType=securityData
