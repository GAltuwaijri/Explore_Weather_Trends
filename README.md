# Explore Weather Trends
   In this project, we analyze local and global temperature data by using SQL to extract data from the temperatures database, And Excel worksheet to calculate the moving averages, Create a line chart. Then we will compare the temperature and trends in specific city to overall global temperature and trends.


### Data
For our analysis, we have used data from the Udacity temperature Database [1]. This database contains 3 schemas: city_list, city_data and global_data. We extract the data by writing these queries:

select * from city_list where country= 'Saudi Arabia';
select year, avg_temp from city_data where city = 'Riyadh';
select * from global_data where year BETWEEN 1843 AND 2013;

To find the nearest city, retrieve the average temperatures for Riyadh city by year, And the average global temperatures by the same years. Then we download the result to CSV files.


### Final observations
This graph show that Riyadh city temperatures is higher than global temperatures. Riyadh temperature was the hottest between 2001-2013 by reaching more than 27.00°C. The global temperature is likely range from a low around 7°C to a high of around 9°C. Both of Riyadh and globally averaged temperatures have been rising over the time.



### License
Explore_Weather_Trends is Copyright © 2020 Ghaida Altuwaijri. The content of this repository is licensed under a Creative Commons Attribution License
