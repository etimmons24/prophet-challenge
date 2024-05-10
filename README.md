# Forecasting Net Prophet

With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. Below is an analysis of the company's financial and user data in order to determine ways to make the company grow. This is an exercise to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

The approach to this analysis is broken up into four main steps:

Step 1: Find unusual patterns in hourly Google search traffic

Step 2: Mine the search traffic data for seasonality

Step 3: Relate the search traffic to stock price patterns

Step 4: Create a time series model with Prophet


From the analysis, the following were summarized:
1. Google search traffic increased during the month that MercadoLibre released its financial results.
2. There appears to be more traffic in the start and end of each month. Traffic appears to be it's highest in the beginning of the week (Mondays) and then drops the remaing of the week. The data is less clear when viewing the weekly trends. The trends peaked in the beginning of the year and then is pretty random the rest of the weeks. During the times of the holidays (weeks 40 - 50) it begins to peak again, then drops drastically around week 52.
3. From viewing the time series data, there is a common trend with stock prices observing an increase around March 2020 and then continued increases until the end of the year.  However, the Search trends stay consistent with a spike in May.
4. There was a weak negative relationship among the Lagged Search trends and Stock volatility.  There is not much of a relationship betwee, the Lagged Search trends and hourly stock return.
5. It appears that the start and end of the days are the most popular in search trends.
6. Tuesdays seems to get the most search traffic.
7. October has the lowest point of search traffic.  
