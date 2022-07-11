Program Description:
Visualize and analyse data of the global average sea level change since 1880 until 2013, and returns a
prediction about the sea level change through year 2050, using Pandas and Matplotlib.

This program creates a scatter plot that will predict how much the sea level will rise on the year 2050.

Using the available data, the following tasks in sea_level_predictor.py will be executed:

. Import the data from epa-sea-level.csv, using Pandas.

. Create a scatter plot using the Year column as the x-axis and the CSIRO Adjusted Sea Level column as the
  y-axix.

. Get the slope and y-intercept of the line of best fit, using a 'linregress' function.
  Plot the line of best fit over the top of the scatter plot.
  Make the line go through the year 2050 to predict the sea level rise in 2050.

. Plot a new line of best fit just using the data from year 2000 through the most recent year in the
  dataset.
  Make the line also go through the year 2050 to predict the sea level rise in 2050 if the rate of rise
  continues as it has since the year 2000.

. x label will be Year, the y label will be Sea Level (inches) , and the title will be Rise in Sea Level.


Note: see examples figures of the expected output charts.


Data Description:
Global average sea level change since 1880, until 2013.

File name: epa-sea-level.csv
