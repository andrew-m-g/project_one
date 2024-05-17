Climate and Real Estate

Research Questions:
Are severe weather events becoming more frequent over time?
Are severe weather events becoming more destructive over time?
What is the effect of weather patterns on home prices?

Data Sources Used:
NOAA web services API   
Openweather API  
Kaggle USA Real Estate dataset    
Zillow datasets  

We first looked at overall weather trends for the United States for the 2000 - 2020 timespan. Specifically, we analyzed the number of significant weather events and their economic impact and lethality on the surrounding regions. This was achieved by Andrew using the below process: 

Code File Name: project1_weathercsv.ipynb
Graphs:
Strm_freeze_freq2.png
Weather_fatality.png
Weather_fatality_sum.png
Wevents_freq1.png
Code Function:
Import downloaded CSV files from National Weather Service
Convert csv files into pandas dataframe
Combine dataframes into one single frame
Remove excessive/unnecessary columns and associated data from combined dataframe
Parse data relevant to questions posed in the project proposal and use to create graphs that would provide relevant, clear insights into macro weather trends across the united states from 2000 to 2020

As is described in the project1_weathercsv.ipynb file and powerpoint located in this repository, we found that the number of weather events and their severity did increase in the US from 2000 - 2020.

Next, Esme utilized the NOAA API to look into the severity of 7 different weather events. This code is located in the NOAA API final.ipynb final. As a group, we settled on narrowing the scope to the Midwest flooding of 2008 and California wildfires of 2018. 

To determine if these events had an effect on the surrounding housing prices, Jomo and Paul utilized datasets from Zillow and Kaggle to analyze home prices during the time of these events.

First, looking at the Midwest Flood event that occurred from April-01-2008 to August-30-2008 in Indianapolis, Indiana. From the data collected and the graphs produced, there seems to be no immediate correlation between the weather event and the price of housing in the area. A slight dip in prices was noticed after the flood but that might be due to other factors as well. The data set that Jomo was working with had monthly price points which was helpful to get a closer view.  From that we noticed a potential inverse relationship, however there was not much of a price difference to make that claim so it is clear that there was no relationship between the weather event and housing prices for that specific period.

Next, In the California wildfires of 2018, housing prices were compared over time, both in the long term, and within the 6 months of the wildfire.  Upon analyzing data obtained from Zillow, there does not appear to be a correlation between housing prices and natural disasters.  A potential explanation would be that while new demand for housing may decrease during and immediately after a natural disaster, it may be counterbalanced by the reduced supply via the houses that the disaster destroyed.  Other financial factors were considered, such as insurance rates and tourism, however a data set with enough historical data could not be found.

In conclusion, while we did find that the number of weather events and their severity has increased over time, we were unable to prove a relationship between housing prices and these weather events. If we were to continue this project, we would look at more immediate indicators of economic health (credit card transactions, tourism data, etc.) to further explore the impact these weather events had on the surrounding areas. It would also be useful to control for external factors. For example, the flooding event we analyzed took place at the same time as the 2008 economic recession. Therefore, it is difficult to define what exactly led to the dip in housing prices over the next few years. Given more time and resources, it would be interesting to attempt to isolate these variables and further understand the impact weather has on the real estate market of a community.

