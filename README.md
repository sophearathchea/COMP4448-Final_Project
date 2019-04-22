# COMP4448-Final_Project
# **Project proposal**

1. Team members:
Team Members Names: Working Alone.

1. Problems/Motivation:  The objective of this project is to use a linear regression model to predict the sale price of a house in Denver County, CO. (Denver County, CO includes the following zip codes https://www.zillow.com/browse/homes/co/denver-county/.)

1. What libraries/tools you will need. What you already know and what else you need to evaluate. <br>
libraries/tools: requests, BeautifulSoup, numpy, pandas, matplotlib, selenium

1. Data Collection details: <br>
Web Scraping Zillow recently sold homes.  <br>
Attributes include: address (city, state, zip), price, sqft, bedrooms, bathrooms, days_on_zillow, sale_type (and maybe more). <br> 
Possibly using the following github page as a starting point: https://github.com/ChrisMuir/Zillow

1. Any Literature review:
https://www.kaggle.com/apapiu/regularized-linear-models/data

1. Required work detail before build model(clean up, hypothesis, data bias analysis etc.):
Data preprocessing: (a)First I'll transform the skewed numeric features by taking log(feature + 1) - this will make the features more normal (b) Create Dummy variables for the categorical features, (c) Replace the numeric missing values (NaN's) with the mean of their respective columns

1. What is the predictive task and model detail. Model evaluation and selection strategy.
Model evaluation: Adjusted R-squared

1. How a user is going to test the final model. is there any webpage/command line interface. It can be like using curl from command line and calling a function(lambda via API gateway) in the cloud(AWS).

1. Tentative time line of activities.

Project Tasks | Tentative Completion Date |
| --- | --- |
| data collection | 05/13/2019 |
| data cleanup | 05/20/2019 |
| statistical summary | 05/27/2019 |
| visualization | 05/27/2009 |
| Final project DUE | 06/05/2019 |
