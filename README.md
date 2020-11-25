# **Predicting-Currency-Movements.**

![](https://www.travelex.com/media/2555/10832869_s.jpg)

## **Background**
This repo is about testing the time-series tools in order to predict future movements in the value of the Japanese yen versus the U.S. dollar. Using historical Dollar-Yen exchange rate futures data and applying time series analysis and modeling to determine whether there is any predictable behavior. Building a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

### **With the Time-Series Forecasting notebook we found:**
 - The overall trend Yen/ USD is upward. Prices are increasing so it  would be a good time to buy the Yen.
 - The volatility is increasing therefore the risk is increasing.
 -  The ARMA model is not significant based on the (p > 0.05), so it doesn't allow us to do a good judgement call. 
 - The ARIMA model (p > 0.05) wouldn't bet that accuarate either. 
 - The GARCH model (p < 0.05) gives us more confidence to predict volatility but it does not allow to make a buy/sell call.

 ### **With the Linear Regression Forecasting notebook we found:**
 
 - Out-of-Sample Performance Root Mean Square Error (RMSE): 0.41545437184712763 is lower than In-of-Sample Performance Root Mean Square Error (RMSE): 0.5962037920929946 so Out-of-Sample data are more significant.