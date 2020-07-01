# (Flights data Exploration)
## by (Harshit Kumar)


## Dataset

> This project explores a dataset that reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from January 2006 to April 2008.
>
>Data source#1: http://stat-computing.org/dataexpo/2009/the-data.html  
>Data source#2: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7#
>
>The dataset has 16,984,354 flight details with 29 features. The data ranges from Jan 11, 2006 to April 17, 2008.
>
>The variables in the dataset contains information about flights' origin, departure, date and time, duration, cancellation status, delay (and cause of delay), etc.
>
>Also, a flight is considered delayed when its arrival delay is longer than 15 minutes.
>
>During data wrangling,   
> * The year-wise data of 2006, 2007, and 2008 was combined into a single csv file.  
> * Some of the variables such as ArrTime and DepTime were converted from hh:mm format to datetime (min) format.  
> * Since a flight is considered delayed if its (arrival) delay is over 15 minutes (inclusive), I created a subset of the original dataframe containing delayed flights.


## Summary of Findings

> Some of the findings of the data exploration are:

* The biggest reason for the flights to be cancelled is the Carrier causes followed by Weather causes.
* February and December are the worst month to travel having maximum proportion of delays due to weather.
* The WN airline has the highest number of flights and MQ airline has the highest proportion of cancelled flights (4.1%).
* There is a high correlation between Arrival and Departure delay, which is expected.
* The NAS is the most common delay cause for most of the airlines and Security the least common.
* Weather and Security causes have the the highest and the lowest delay respectively.
* ATL is the busiest airport having more than 900k flights out of which 28.3% were delayed.
* In the top 10 busiest airports, EWR has maximum proportion (32.2%) of delayed flights.


## Key Insights for Presentation

> In the presentation, I'm showing the analysis of cancelled and delayed flights.

![slides_gif.gif](slides_gif.gif)

---

# Communicate Data Findings 

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.
