# SQL-API project

## Task Overview
We would like to keep track of accumlated flights data (of The Research Center for Aerospace (RSA)) in combination with weather data from meteostat. Our task is to find a situation where the weather has impacted on flight performance and use this to contribute some knowledge about how different weather affects flights in different cities.

![](images/PIREPs-featured.jpg)   


### Task steps
1. To choose a historical weather event that occured in the United States sometime in the past 30 years that we believe would have led to the cancellation of flights. (we chose Sandy Hurricane 2012, US)

2. To get data on flights & Set up a connection to the SQL database.  
  a. Download csv file containing flights data for the specific years and months needed from the [Bureau of Transportation Statistics website](https://transtats.bts.gov). (we downloaded the two month of OCT, NOV 2012)  
  b. To clean the data (e.g. specify which columns you want to keep, rename columns etc.).  
  c. To reduce the dataframe to include 8 origin airports (4 being affected bu the storm, 4 not being affected).   
  d. To make an EDA on the flights data we have downloaded to explain what data we have and any unexpected findings.   
  e. To connect to database and join the data with the airports table of our database to get the latitude, longitude or city names for the airports in your dataset. 
  
3. As next step, we get historical weather data using the [Meteostat API](https://dev.meteostat.net/api/point/daily.html#endpoint).   
  a. Use the API key to get weather data for our chosen month/year and locations.  
  b. Flatten the JSON data and transform it into a DataFrame for future analysis.   
  
4. To perform a basic EDA on both of the tables.  
  

### Deliverables
1. 
2. A .ipynb Notebook containing the code to connect to database as well as API and EDA part.
3. 10-minutes technical presentation to our colleagues, presenting the results of the data exploration and answering our hypotheses.


