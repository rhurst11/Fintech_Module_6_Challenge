# Fintech_Module_6_Challenge


## Purpose: 

This project aims to employ data visualization tools, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

## Software Requirements:
Python -- version 3.7.10, Conda -- version 4.10.3, Jupyter Lab -- version 3.0.14

Libraries: Pandas, NumPy, HV Plot, Plotly Express

## API Keys

Mapbox api general key


## Examples of plot visuals 

Because a user will need to run the program with their own mapbox api key, it seemed useful to provide examples of hoq each visual would display:

Bar chart:

![alt text](https://github.com/rhurst11/Fintech_Module_6_Challenge/blob/main/Images_For_Readme/barplot_example.png)

Line plot:

![alt text](https://github.com/rhurst11/Fintech_Module_6_Challenge/blob/main/Images_For_Readme/Line_No_Widget.png)

Line plot with widget to select neighborhood

![alt text](https://github.com/rhurst11/Fintech_Module_6_Challenge/blob/main/Images_For_Readme/Line_With_Widget.png)

Scatter plot

![alt text](https://github.com/rhurst11/Fintech_Module_6_Challenge/blob/main/Images_For_Readme/Scatter_Fixed.png)


## Analysis

Question What is the overall trend in housing_units over the period being analyzed?

Answer: The overall trend in housing units between 2010 and 2016 was fairly static. The number of housing units increased slightly from 372560 units in 2010 to 384242 units in 2016, which represents roughly a 3% increase over the time period.


Question What is the lowest gross rent reported for the years included in the DataFrame?

Answer The lowest gross rent was in the year 2010, with a gross rent value

Question * Did any year experience a drop in the average sale price per square foot compared to the previous year?

Answer From 2010-2011, there was a small derease in the average sale price per square foot, but otherwise sale price has been increasing steadily ever since 2011.

Question * If so, did the gross rent increase or decrease during that year?I

Answer The gross rent increased that year regardless of the small drop in average sale price.

Question For the Anza Vista neighborhood, is the average sale price per square foot for 2016 more or less than the price that’s listed for 2012?

Answer For the Anza Vista neighborhood, the average sale price per square foot in 2016 was noticeably less than the average sale price per square foot in 2012


Question Which neighborhood has the highest gross rent, and which has the highest sale price per square foot?

Answer
According to the Scatter plot exclusively, Bayview Heights had the highest gross rent of the neighborhoods we analyzed. However, when verifying this result against the dataframe via direct analysis of the plotted dataframe, it appears that Westwood Park has the highest gross rent in reality.

For the sake of the assignment, I am providing both answers for gross rent to avoid any potential issue.

Union Square District had the highest average price per square foot of the neighborhoods we analyzed. this was verified both using the scatter plot and by running further analysis of the plotted dataframe

Compose your data story:


Question 

How does the trend in rental income growth compare to the trend in sales prices? Does this same trend hold true for all the neighborhoods across San Francisco?

Answer

Assuming that we can make assumptions about rental income growth solely off of gross rental prices, rental income growth grew significantly. Sale Prices also grew during the same time period of 2012-2016, but to a lesser degree. When comparing rental income growth to sale price growth, it becomes clear that rental income grew at a far greater rate than growth in sale prices between 2012 and 2016.

It is important to recognize that the previously stated trend should not be applied to individual neighborhoods without more specific analysis of each relative location.
However, after asessing the relationship between gross rent price and sale price / square foot for a handful of neighborhoods, it does appear that many neighborhoods display a similar trend to the city as a whole, with regard to rental growth rates.

Despite the continued trend in rental income growth, there is much more deviation in sale price on a case by case basis. Both downard and upward reversals of price movement in sale price and rapid shifts in the rate (down or up) of price movement for some neighborhoods display clear deviations from the more general, city-wide trend


Question 

What insights can you share with your company about the potential one-click, buy-and-rent strategy that they're pursuing? Do neighborhoods exist that you would suggest for investment, and why?

Answer

My company should be aware of the fact that some neighborhoods within their focus area have decreased in sale price while still providing solid growth in potential rental income. These neighborhoods that maintain the general trend of increasing rental price while diverging from the general trend in sale price due to downard sale price movement may be good investment opportunities.
Here is a list of some of the neighborhoods that seem like good investment opportunities:
These neighborhoods exhibit one of the following patterns:
* growth in rental income with recent and continuing declines in sale price
* growth in rental income with relatively stable sale price value
* growth in rental income with continuously declining sale price
Ideal Neighborhoods:
* Westwood Park
* Visitacion Valley
* Van Ness / Civic Center
* South of Market
* South Beach
* Portrero Hill



