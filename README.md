# prophet--challenge

Initally we attempted to find Unusual Patterns in hourly Google Search Traffic by reading the search data into a DataFrame, then we sliced the data to just the month of

may 2020. We then calculated the total search traffic for the month and then compare the value to the monthly median across all months. Next we mined the Search

Traffic Data for Seasonality which will allows a greater return on investment. We then mined search data for predictable seasonal trends, grouping by hour and day of the

week, then plotted the results.  We then used the search traffic to identify traffic patterns byt reading in and plotting the stock price data. During this phase we

created a new column in the DataFrame named “Lagged Search Trends” that offsets, or shifts, the search traffic by one hour, including stock volatility and stock return.

We then identifyed the relationship between search data and the companies stock price.  This was acheived by reading in and plotting the stock price. We then

concatenated the stcok price data to search data in a single dataframe. Next We created new columns in the DataFrame named “Lagged Search Trends” that offsets, or 
 
shifts, the search traffic by one hour. Then created two additional columns “Stock Volatility”, which holds an exponentially weighted four-hour rolling average of the

company’s stock volatility,“Hourly Stock Return”, which holds the percent change of the company's stock price on an hourly basis. Finally, we created a time series 

model with Prophet byt setting up a Google search for prophet forecasting model after estimating th emodel and plotted the forecast.  Based on the results, the graph

shows the busiest periods are typically during late hours, especially closer to midnight. This pattern suggests that users are more active during the evenings, possibly 

due to various factors such as people having more free time after work or other daily activities. However, different time zone and regions will ultimately impact the 

search trends. We noticed that there is volitility over the years with peaks during October however, there will be a trend forecast dip during the month of October, 

which repesents the lowest points for search traffic, while Tuesdays and Midnight (00:00:00) represents that most searched traffic and greatest poplarity points.
