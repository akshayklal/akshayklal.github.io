Title: San Francisco Airport (SFO) Global Warming Trends
Date: 2024-09-02 19:30
Category: Blog
Tags: San Francisco, Global Warming
Author: Akshay Lal

This graph shows the increase of the average min and max
temperatures at San Francisco Airport since 1946. Average
min and max temperatures have increased by around 3 °F
over last 70 years. This data clearly shows that global
warming trends are present in the San Francisco Bay Area.

![Average Annual Max and Min Temperatures at San Francisco International Airport (SFO) from 1946 to 2024](/images/sfo-global-warming.png)

It is interesting to see that the average annual minimum temperature
has been consistently over 50 °F for the last ten years, however from
1946 to 1956 the average annual minimum temperature never went above
50 °F. The average annual minimum temperature has been increasing
by 0.06 °F per year (the slope of the trend line in the graph). If
this trend continues, then in 100 years, the average annual minimum
temperature would increase by 6 °F. 

We can see from the graph that the average minimum and maximum
temperatures are increasing, however the average amount of
rainfall during winters is not changing, as seen in the graph
below.

![Total winter rainfall at San Francisco International Airport (SFO) from 1946 to 2024](/images/sfo-rain.png)

The trend line, in the graph above, shows the average amount of
rainfall during winter seasons have remained the same over the years.
However, the four driest winters to date have happened in the last 17
years, with the three driest happening in the last 13 years. These
drier winters, coupled with warmer average temperatures over the last
ten years (as shown in the first graph above), are causing more intense
forest fires around the San Francisco Bay Area.

In order to generate this graph, I first downloaded temperature
data from the National Oceanic and Atmospheric Administration
(NOAA) webservice. Then, for each year, I calculated the annual
average maximum and minimum temperatures. Finally, I graphed the
data to show the average annual temperature trends at San Francisco
Airport (SFO).

I used a python program (using requests, numpy, panda, and matplotlib 
libraries) to download, aggregate, and graph the data. 