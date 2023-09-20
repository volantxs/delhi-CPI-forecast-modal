# Delhi CPI forecasting modal using SARIMA method

## Web scraping & exploratory data analysis
Performed data-scraping and data-cleaning to create a dataset of Consumer Price Index for Delhi in various category of goods and Services, which is to be utilized in machine learning model to analyse and predict next 19 months.

## Time series decomposition & stationarity
burgahDecomposed the time series data using Additive Seasonal Decomposition into the following components: Trend, Seasonality & Residue. Conducted Augmented-Dickey Fuller test to check for stationarity. Used first-order differencing to convert non-stationary time series into stationary.

## SARIMA model & forecasting
Built a SARIMA model using seasonal_order = (2, 0, 1, 12) to predict the consimer price index for food and beverages goods in Delhi for 2023. Forecast revealed CPI crossing the 400.00 mark which directly disrupts the F&B companies. Data analysis for predicted values suggest that there has been an astonishing 85% increase in growth rate for CPI of F&B goods in last 10 years with an annual growth rate of 6%
