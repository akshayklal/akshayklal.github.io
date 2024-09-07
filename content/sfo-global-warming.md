Title: San Francisco Airport (SFO) Global Warming Trends
Date: 2024-09-02 19:30
Category: Blog
Tags: San Francisco, Global Warming
Author: Akshay Lal

This graph shows the increase of the average min and max
temperatures at San Francisco Airport since 1946. Average
min and max temperatures have increased by around 3 °F
over last 70 years. This data clearly shows that global
warming is present in the San Francisco Bay Area.

![Average Annual Max and Min Temperatures at San Francisco International Airport (SFO) from 1946 to 2024](/images/sfo-global-warming.png)

In order to generate this graph, I first downloaded temperature
data from the National Oceanic and Atmospheric Administration
(NOAA) webservice. Then, for each year, I calculated the annual
average maximum and minimum temperatures. Finally, I graphed the
data to show the average annual temperature trends at San Francisco
Airport (SFO).

I used a python program (using requests, numpy, panda, and matplotlib 
libraries) to download, aggregate, and graph the data. 