# <p align = "center">Data Analysis Of Boston Airbnb Listings Using R</p>

In our project, we have included airbnb listings centered around Boston. Our analysis revolves around how we can effectively consider a booking based on different factors in Boston. <br>
These factors mainly include, the neighbourhood, facilities available close to it, and price distribution on various room types. This helped to get desired results on preferences, basically by observing their occupancy rates.

In this analysis, we observed,
1. How the vibe varies with neighborhood
2. How price of each listing vary by their room type and neighbourhood
3. Which neighbourhood in Boston have the great number and least number of listings?

The Dataset is collected from <a href = "http://insideairbnb.com/get-the-data.html">Inside Airbnb</a> <br>
listings.csv.gz - consists of details of all the airbnb listings in Boston including their price, ratings, name, host id, neighbourhood overview and many other columns describing details of listings with Number of listings: 3,213

# Methods
- Implemented leaflet map in R Shiny to show all the airbnb listings
- Used Cluster marker to find the density of airbnb listings in the map
- Plotted Price and Monthly Income Distribution of airbnb listings
- Leveraged Bar Plots to find the number of listings per room type in the selected Neighborhood
-  Used wordcloud2 library to find the word frequencies and plot a wordcloud to analyze the vibe of the selected neighbourhood

# Conclusion
- We can find the neighbourhood vibe based on the word cloud generator.
- Average price of listing is more for hotel rooms.
- No. of listings are more in Dorchester and less in West Roxbury.
- As we move away from the city, we can observe a decline in number of listings.
- There are more Entire room/apartment in the listings in all of Boston neighbourhoods and less shared rooms among room types.
 
