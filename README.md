# Airbnb-NYC-Booking-Analysis-2019

Problem Statement

To explore Airbnb New York City 2019 the questions I would like to ask on the dataset are:
•	How the price varies in the neighborhood and with room type
•	How room type varies and price distribute among neighborhood groups
•	Which is the top 10 neighborhood with the highest average price
•	How rooms are distributed to latitude and longitude

Solution Approach

I initially did the data cleansing steps like finding the null values column and missing values check. Later, I explored the categorical variables like room type, neighborhood and explored the distribution of the variables using histograms. I checked the correlation of the price variable with other variables in the dataset. Correlation tells us the strength of the relationship between the variables.

Conclusion

This dataset appeared to be a very rich dataset with a variety of columns that allowed us to deep data exploration on each significant column presented. 

Here I used the libraries ‘NumPy’, ‘Pandas’, ‘Matplotlib’, and ‘Seaborn’. Using these libraries, first, I have found the highest number of neighborhood groups and the highest preferred room by bar plot. Next, by using the count plot, I established a relation between Neighborhood Groups and Room Type and showed the counts of observations in each categorical variable also in the same way I find the hosts with the most listings in NYC. Further, I analyzed how the price of the room was distributed in each Neighborhood Groups. As price is a numerical value, so here I used to violin plot to explain the distribution of the room’s price according to the neighborhood groups. Then I showed the top 10 neighborhoods and also shown the top 10 neighborhoods with the highest average room price; using the groupby function. Then I calculated the average cost for each room type using the groupby function. Next, I established a relation between the neighborhood and room type using a count plot. Next, I calculated the minimum nights spent by the users and visualized it by box plot. After that, I showed the distribution of neighborhood groups concerning latitude and longitude. And finally, I showed the distribution of room type to latitude and longitude using a scatter plot, to show how much one variable is affected by another.

Interesting Insights

The minimum number of nights stay is not impacting the price of the hotel.
