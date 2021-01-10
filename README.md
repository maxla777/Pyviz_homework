# Pyviz_homework

Background
Harold's company has just started a new Real Estate Investment division to provide customers with a broader range of portfolio options. Harold was tasked with building a prototype dashboard and he needs your help. The real estate team wants to trial this initial offering with investment opportunities for the San Francisco market. If the new service is popular, then they can start to expand to other markets.
The goal of this dashboard is to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in San Francisco.
In this homework assignment, you will help Harold accomplish the following tasks:


Complete a notebook of rental analysis


Create a dashboard of interactive visualizations to explore the market data

Instructions

Rental Analysis
The first step to building the dashboard is to work out all of the calculations and visualizations in an analysis notebook. Once the code is worked out here, it can be copied over to a dashboard code and used with Panel to create the final layout. Use the rental_analysis.ipynb to complete the following:

Housing Units Per Year
In this section, you will calculate the number of housing units per year and visualize the results as a bar chart using the Pandas plot function.
Note: By default, the limits auto-scale to the data. However, it is hard to see the difference between the yearly data. In the optional challenge, you can use the min, max, and standard deviation of the data to manually scale the y limits of the plot.
Default Bar Chart

Bar Chart with y-axis limits adjusted


Average Gross Rent in San Francisco Per Year
In this section, you want to visualize the average gross rent per year to better understand the trends for rental income over time. You will visualize the average (mean) gross rent per year and visualize it as a line chart.

Calculate the mean gross for each year.
Visualize the mean gross rent per year as a line chart.



Average Sales Price Per Year
In this section, you want to determine the average sales price per year to better understand the sales price of the rental property over time. For example, a customer will want to know if they should expect an increase or decrease in the property value over time so they can determine how long to hold the rental property. You will visualize the average (mean) sales_price_sqr_foot and visualize it as a bar chart.

Calculate the mean gross for each year.
Visualize the mean gross rent per year as a line chart.



Average Prices By Neighborhood
In this section, you want to compare the average prices by neighborhood.

Group the data by year and by neighborhood and calculate the average (mean) sales_price_sqr_foot.
Visualize the mean sales_price_sqr_foot per year with the neighborhood as a dropdown selector. Hint: Use hvplot to obtain the interactive dropdown selector for the neighborhood.



Top 10 Most Expensive Neighborhoods
In this section, you want to figure out which neighborhoods are the most expensive. You will need to calculate the mean sale price for each neighborhood and then sort the values to obtain the top 10 most expensive neighborhoods on average. Plot the results as a bar chart.


Parallel Coordinates and Parallel Categories Analysis
In this section, you will use plotly express to create parallel coordinates and parallel categories visualizations so that investors can interactively filter and explore various factors related to the sales price of the neighborhoods.
Using the DataFrame of Average values per neighborhood (calculated above), create the following visualizations:

Create a Parallel Coordinates Plot



Create a Parallel Categories Plot



Neighborhood Map
In this final section, you will read in neighborhood location data and build an interactive map with the average prices per neighborhood. Use a scatter mapbox object from plotly express to create the visualization. Remember, you will need your mapbox API key for this.
Remember that in order to create maps visualizations using Plotly Express, you will need to create an account at mapbox and create an access token.


Dashboard
Now that you have worked out all of the code and analysis, you will use the Panel library to build an interactive dashboard for all of the visualizations. There are no hard requirements for the layout of this dashboard, so use your own imagination and creativity!
Create a new dashboard.ipynb for your dashboard code. Copy over the code for each visualization and place this into separate functions (1 function per visualization). This will make it easier to build and modify the layout later. Each function should return the plot figure in a format that Panel can use to plot the visualization.
Sample Dashboard:



Submission


Create separate notebooks for the analysis and the dashboard and upload these to Github.


Complete your README to explain how to run and use your dashboard.


Note: You should not submit your mapbox access token to Github!


Submit the Github URL repository to Bootcampspot.