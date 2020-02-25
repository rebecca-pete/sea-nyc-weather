# US Coastal Weather Comparisons:
# Seattle & New York City

## Introduction

This project compares weather patterns of Seattle and New York City over a two-year period, beginning July 1, 2014 through June 30 2015.

Uses csv datasets referenced in the [538 US Weather History](https://github.com/fivethirtyeight/data/tree/master/us-weather-history) repo and created with source data pulled from [Weather Underground](http://wunderground.com).

## Data Dictionary

Field | Description
---|---------
`date` | The date of the weather record, formatted YYYY-M-D
`actual_mean_temp` | The measured average temperature for that day
`actual_min_temp` | The measured minimum temperature for that day
`actual_max_temp` | The measured maximum temperature for that day
`average_min_temp` | The average minimum temperature on that day since 1880
`average_max_temp` | The average maximum temperature on that day since 1880
`record_min_temp` | The lowest ever temperature on that day since 1880
`record_max_temp` | The highest ever temperature on that day since 1880
`record_min_temp_year` | The year that the lowest ever temperature occurred
`record_max_temp_year` | The year that the highest ever temperature occurred
`actual_precipitation` | The measured amount of rain or snow for that day
`average_precipitation` | The average amount of rain or snow on that day since 1880
`record_precipitation` | The highest amount of rain or snow on that day since 1880
`Month` | Month extracted from date.
`Year` | Year extracted from date.

## Final Report
In this report we will compare the temperature and precipitation for Seattle and New York City from July 1st, 2014 through June 30, 2015.

We will use data sourced from Weather Underground.

We will use line plots to visualize the following:

We will compare the Actual Mean Temp for Seattle and New York City.
We will compare the Record Max Temp for Seattle and New York City.
We will compare the Actual Precipitation for Seattle and New York City.
We will compare the Record Precipitation for Seattle and New York City.
We will use scatter plots to visualize the following:

We will compare the Actual Precipitation and Actual Mean Temp for Seattle.
We will compare the Actual Precipitation and Actual Mean Temp for New York City.

## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)
* Source: [Weather Underground](http://wunderground.com)
  

