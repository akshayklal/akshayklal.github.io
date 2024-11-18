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
years, with the three driest happening in the last 13 years.

The graph below shows concentration of particulate matter with a diameter
of 2.5 micrometers or less (PM2.5). The peaks in the graph correspond to
large forest fires which have affected the San Francisco Bay Area.

![San Francisco Air Quality from 2016 to 2024](/images/san-francisco-pm2.5.png)

* The peak in October 2017 corresponds to the Tubbs Fire which burned around 36000
acres.
* The peak in November 2018 corresponds to the Camp Fire, which burned over 153,000
acres and is considered to be the worst forest fire in California history. I remember
this fire very well because the air quality was so bad that my school was closed and
we had to wear masks for a few days.
* The peak in October 2019 corresponds to the Kincade Fire which burned around 78,000
acres.
* The peak in September 2020 corresponds to the SCU Lightning Complex Fires which burned
almost 400,000 acres, and the CZU lightning Complex fires which burned almost 90,000 acres.
* The peak in August 2021 corresponds to the Dixie Fire which burned close to 1000,000 acres
and is considered one of the worst in California history.
* The peak in August 2023 corresponds to the Deep Fire, but it only burned a little over 4000
acres.

Although direct correlation is harder to establish, it seems as if these
drier winters, coupled with warmer average temperatures(as shown in the 
first graph above), are causing more intense forest fires in recent years.

In order to generate this graph, I first downloaded temperature
data from the National Oceanic and Atmospheric Administration
(NOAA) webservice. Then, for each year, I calculated the annual
average maximum and minimum temperatures. Finally, I graphed the
data to show the average annual temperature trends at San Francisco
Airport (SFO).

I used a python program (using requests, numpy, panda, and matplotlib 
libraries) to download, aggregate, and graph the data. 