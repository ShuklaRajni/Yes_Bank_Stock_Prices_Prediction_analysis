# Yes_Bank_Stock_Prices_Prediction_analysis

# Summary:
In this project, exploratory data analysis, visualization, regression models with different types and interesting insights of the data have been performed. This dataset has around 185 observations in it with 5 columns. Fundamental Analysis involves analyzing the company’s future profitability on the basis of its current business environment and financial performance. Technical Analysis, on the other hand, includes reading the charts and using statistical figures to identify the trends in the stock market. The will be on the technical analysis part.

# Objective:
We were asked to create a predictive model that could forecast the future stock prices of the bank due to an unprecedented situation like fraud.

# Introduction:
In our project our goal is to build a prediction model for close price prediction, which focuses on short-term price prediction. A stock market is a public market where you can buy and sell shares for publicly listed companies. The stocks, also known as equities, represent ownership in the company. The stock exchange is the mediator that allows the buying and selling of shares. Stock markets help companies to raise capital.

• It helps generate personal wealth.

• Stock markets serve as an indicator of the state of the economy. 

• It is a widely used source for people to invest money in companies with high growth potential. 

Predicting how the stock market will perform is one of the most difficult things to do. There are so many factors involved in the prediction – physical factors vs. psychological, rational and irrational behavior, etc. All these aspects combine to make share prices volatile and very difficult to predict with a high degree of accuracy. Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations.

# Data Description:
This dataset has around 185 observations in it with 5 columns. 

Date: The month and the year of the stock prices. Open: The price at which the stock begins. 

High: The highest price at which the stock traded during a period. 

Low: The lowest price at which the stock traded during a period. 

Close: The price that determines how a stock performed during a period.

# Approach:
As a first step, the data as loaded the data and mounted the drive. After mounting the drive, important libraries such as numpy, pandas, seaborn, matplotlib and also all regressions model libraries with their metrics were imported, which are useful for our analysis.

Exploration our data was performed by checking all the necessary parameters like shape, head, tail, information of the columns and their datatypes and description of data like mean, min and max. Exploratory data analysis, normalization, lag creation, preparation of the data and two types of splits were performed.

Fundamental Analysis involves analyzing the company’s future profitability on the basis of its current business environment and financial performance. Technical Analysis, on the other hand, includes reading the charts and using statistical figures to identify the trends in the stock market.The will be on the technical analysis part.

# Result:
In this work we use linear regression technique, lasso regression, ridge regression, elastic net regression and XGBoost Regression technique. These five models gives us the following results-

a)-Linear, lasso and ridge regression show almost same R squared values.

b)-Independent variables ( High, Low and Open ) are directly correlated with Dependent variable ( Closing Price )

c)-Xgboost regression results as best model for yes bank stock closing price data with very less mean square error i.e. 0.0016
