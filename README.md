# prophet-challenge

Initally we attempted to find Unusual Patterns in hourly Google Search Traffic by reading the search data into a DataFrame, then we sliced the data to just the month of

may 2020. We then calculated the total search traffic for the month and then compare the value to the monthly median across all months. Next we mined the Search

Traffic Data for Seasonality which will allows a greater return on investment. We then mined search data for predictable seasonal trends, grouping by hour and day of the

week, then plotted the results.  We then used the search traffic to identify traffic patterns byt reading in and plotting the stock price data. During this phase we

created a new column in the DataFrame named “Lagged Search Trends” that offsets, or shifts, the search traffic by one hour, including stock volatility and stock return.

We then identifyed the relationship between search data and the companies stock price.  This was acheived by reading in and plotting the stock price. We then

concatenated the stcok price data to search data in a single dataframe. Next We created new columns in the DataFrame named “Lagged Search Trends” that offsets, or 
 
shifts, the search traffic by one hour. Then created two additional columns “Stock Volatility”, which holds an exponentially weighted four-hour rolling average of the

company’s stock volatility,“Hourly Stock Return”, which holds the percent change of the company's stock price on an hourly basis. Finally, we created a time series 

model with Prophet byt setting up a Google search for prophet forecasting model after estimating th emodel and plotted the forecast.


Questions:
After estimating the model, plot the forecast. How's the near-term forecast for the popularity of MercadoLibre?  There is volitility over the years with peaks during 

the October however, there will be a trend forecast dip during the month of October 2020 

Plot the individual time series components of the model to answer the following questions in the space provided in the starter file:

What time of day exhibits the greatest popularity?
00:00:00 exhibits the greatest popularity.

Which day of the week gets the most search traffic?
Tuesday appears to get the most traffic searches.

What's the lowest point for search traffic in the calendar year?
October represents the lowest point for search traffic in the calendar year
