## Help people find part time job in retail industry

People, especially college student students planning to make some extra money and work part time jobs in retail industry should plan in advance even several months. Also, retail stores should know the exact time to hire new part time employees. I plan to help these people to know their chance based on their location (state and city) and time (year and month) that they need that part time job. The number of employees in retail depends on both time and specific region. Through years, the number of total retail employees in Illinois show a different trend comparing to Texas. These trends depends on several factors which but the most important source is the history of the retail employment in that region. I propose to use the historical retail employment data in each area and develop a model as a function of location and time which can predict the industry demand for part time employees. 
### Data: 
I use the data from the following [The Federal Reserve Bank of St. Louis]( 
https://fred.stlouisfed.org/search?st=retail+employee).
Also, other data such as population of each region, number of retail stores and etc. might be useful, but I believe that some time-series forecasting approaches would be enough for forecasting the monthly trends of retail employee demands.   There are also neural network models that can be applied to these time series which use lagged predictors, such as Neural Networks Autoregression (NNAR). There are even time-series models borrowed from deep learning, specifically in the RNN (Recurrent Neural Network)  which gives high accuracy for prediction. 
I would need to scrape the data from the web/download the data, then clean them.  
See for example this figure which shows the retail job in each county: 
![alt text]( https://github.com/Hassan-Dashtian/PartTimeJobForecast/blob/gh-pages/retailjobs.png)

For each county/state we would forecast the future demand of the employees that each county/state is needed. See the following figure, for example for a county in texas, now we need 8 employees, in June we need 44 and in november we need 69:

![alt text]( https://github.com/Hassan-Dashtian/PartTimeJobForecast/blob/gh-pages/estimate.png)
