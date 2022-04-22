# Project_1 Where Do You Want To Eat?


# Background:

Have you or your friends ever struggled to find where to get some grub? Well, all of your struggles end here! For this project we have done all of the research for you. Some of our research has consisted of finding restaurant locations, ratings, pricing, etc. The data used came from both Yelp and the City of Chicago Food Inspections. We used these sources because Yelp is usually the place where customers aire both their positive reviews and grievances, while the City of Chicago Food Inspection supplies us with inspection results. The data gathered is for the years 2020-2022.   

# Table of Contents:


1. [ Clean Data. ](#yelp)
2. [ Summary Statistics. ](#stats)
3. [ Scatter Plot and Correlation/Regression. ](#plot)
4. [ Pie Charts and Bar Graphs. ](#graphs)
5. [ Google Maps. ](#maps)

<a name="yelp"></a>
## 1. Clean Data

What you will find below is the combined data from both Yelp and the City of Chicago Food Inspection into one dataframe. The dataframe consists of categories such as the restaurant name, rating, address, etc. We decided to focus on Chicago because it is the biggest city in the state and one of the biggest cities in the country, therefore we knew that we would be able to gather an enormous amount data to support our findings. 

Note: This image has been modified to fit the page due this being a large set of data, therefore it displays only five rows and eight columns.


![Clean_Data](/images/CleanData.png)


<a name="stats"></a>
## 2. Summary Statistics

Here we generated a summary statistics table by using the groupby function for the zip code. The table contains the mean, median, variance, and standard deviation for the ratings of each restaurant per zip code. We created this table just to give us an early visual on what our graphs/charts could potentially look like when we generate them. 

Note: This image has been limited to display only five rows, due to this being a large data set.


![Summ_Stats](/images/SummStats.png)


<a name="plot"></a>
## 3. Scatter Plot and Correlation/Regression

This section displays both our scatter plot and regression graph. We grouped the data by zip code and then we compared both the average rating for each restaurant to the average price of each restaurant.

Here is the scatter plot:

![Scatter2](/images/ScatterPlot.png)











This next image displays the regression graph based on the scatter plot above. You will find that the linear regression equation is displayed within the graph. Based on the regression graph we can see that both the average rating and the average price are positively correlated, but the connection to one another is weak. 

![Regression](/images/Scatter2.png)



<a name="graphs"></a>
## Pie Charts and Bar Graphs

Below you will find pie charts displaying all of the restaurants that either passed or failed inspections for all of the zip codes in Chicago. Based off of the chart most restaurants in Chicago have passed inspection.

![Inspection_Pie](/images/pie_pass_fail.png)








We also created a bar graph that will give us a visual of how restaurant ratings are distributed in Chicago. If you look at the graph most restaurants were rated between 3.5 - 4.5, which we consider to be good ratings.


![Inspection_Pie](/images/ratings_histogram.png)





<a name="maps"></a>
## Google Maps

These are probably the most important visuals in the project because due to Chicago being a fairly big city it would help if people had visual of exactly where certain restaurants are located and what other places surround them. 












