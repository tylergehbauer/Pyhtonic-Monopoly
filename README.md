# Pythonic-Monopoly
Unit 6 Homework Assignment - Pyviz

# How To Navigate and Operate my Dashboard 

## 'Welcome'
The first tab 'Welcome' contains a scatter mapbox of San Francisco, and a description of my dashboard. 
The color of the circle indicates the gross rent. The darker the color, the lower the monthly rent.
Furthermore, each circle's size is based on the average sales price per square foot. So the larger the circle, the higher the average sale price per sqaure foot.

*Note: On my machine, this plot is buggy on the dashboard, however, calling 'neighborhood_map().show()' makes the plot easier to navigate*

---

## 'Yearly Market Analysis'
This tab contains a bar plot and two line plots. The line plots helps to better understand housing costs over time.

The bar plot labeled 'Housing Units' illustrates the number of housing units per year (from 2010 to 2016).

The red line plot, labeled 'Average Gross Rent by Year' shows the average gross rent per year (from 2010 to 2016).

The purple line plot, labeled 'Average Sales Price per SqFt by Year' shows the average price per square foot per year (from 2010 to 2016).

---

## 'Monthly Neighborhood Analysis'
This tab contains 2 hvplots. You can use the drop down tab to change the neighborhood that is being analyzed. 

The first visualization shows the trend of average price per square foot over time for each neighborhood.

The second visualization shows the trend of average montly rent over time for each neighborhood.

---

## 'Expensive Neighborhood Analysis'
This first graph displayed in this tab is a bar plot showing the top 10 most expensive neighborhoods based on average sales price per square foot.

The second graph is a comparison bar plot, comparing the average price per square foot versus average monthly rent by year (from 2010 to 2016) for each neighborhood.
For the comparison bar plot, feel free to change the neighborhood being analyzed using the drop down tab.

---

## 'Parallel Plots Analysis'
This tab contains a Parallel Catergories plot and a Parallel Coordinates plot that analyzes the most expensive neighborhoods in San Francisco.
You may interact with these plots to see how each catergory/ variable is related to each other.

---

## 'Sunburst Analysis'
This tab contains a Sunburst plot that shows the most expensive neighborhoods in San Francisco per year.
You may interact with this plot to see the average sales price per square foot for whichever neighborhood desired. Each year displaued on this sunburst plot shows which neighborhoods were the most expenisve. Additionally, the darker the color is implies a higher monthly rent. 




