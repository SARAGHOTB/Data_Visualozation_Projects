Data Visualization Projects contain two projects of 911 Calls data Capstone projects and Finance Project which focus on exploratory data analysis of stock prices.

# 911 Calls Capstone Project

In the capstone project we will be analyzing some 911 call data from [Kaggle](https://www.kaggle.com/mchirico/montcoalert). The data contains the following fields:

- lat : String variable, Latitude
- lng: String variable, Longitude
- desc: String variable, Description of the Emergency Call
- zip: String variable, Zipcode
- title: String variable, Title
- timeStamp: String variable, YYYY-MM-DD HH:MM:SS
- twp: String variable, Township
- addr: String variable, Address
- e: String variable, Dummy variable

# Finance Data Project

In this data project we will focus on exploratory data analysis of stock prices.
We'll focus on bank stocks and see how they progressed throughout the [financial crisis](https://en.wikipedia.org/wiki/Financial_crisis_of_2007%E2%80%9308) all the way to early 2016.

In this project we use pandas to directly read data from Yahoo finance using pandas.

In order to read stock information directly from the internet we used `pandas-datareader`.

- (https://github.com/pydata/pandas-datareader)
- (http://pandas.pydata.org/pandas-docs/stable/remote_data.html).

In order to install pandas-datareader we can run the code :

**pip install pandas-datareader**
