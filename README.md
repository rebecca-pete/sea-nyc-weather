# US Weather Comparisons:
# Seattle & New York City

## Introduction

This project compares the weather behavior for Seattle and New York City over a twelve month period, beginning July 1, 2014 through June 30 2015.

### Source 
This project uses csv datasets referenced in the [538 US Weather History](https://github.com/fivethirtyeight/data/tree/master/us-weather-history) repo and created with source data pulled from [Weather Underground](http://wunderground.com).

## Data Dictionary

Field                   | Description
---                     |---------
`date`                  | The date of the weather record, formatted YYYY-M-D.
`actual_mean_temp`      | The measured average temperature for that day.
`actual_min_temp`       | The measured minimum temperature for that day.
`actual_max_temp`       | The measured maximum temperature for that day.
`average_min_temp`      | The average minimum temperature on that day since 1880.
`average_max_temp`      | The average maximum temperature on that day since 1880.
`record_min_temp`       | The lowest ever temperature on that day since 1880.
`record_max_temp`       | The highest ever temperature on that day since 1880.
`record_min_temp_year`  | The year that the lowest ever temperature occurred.
`record_max_temp_year`  | The year that the highest ever temperature occurred.
`actual_precipitation`  | The measured amount of rain or snow for that day.
`average_precipitation` | The average amount of rain or snow on that day since 1880.
`record_precipitation`  | The highest amount of rain or snow on that day since 1880.
`Month`                 | The month extracted from `date`.
`Year`                  | The year extracted from `date`.

## Terminology

Term                         | Description
---                          |---------
dataframe                    | An object of data, similar to a matrix.
matrix                       | A matrix is an array of arrays. A nested loop is an example of a matrix.
method chaining              | A programming technique that allows the user to "chain" or attach sequential methods to a single object.

## Method Dictionary

Method                       | Description
---                          |---------
`.read_csv('foo.csv')`       | A method used to read a given file.
`.head()`                    | A method that displays the first five entries or rows of an object or dataframe instance.
`.tail()`                    | A method that displays the last five entries or rows of an object or dataframe instance.
`.shape`                     | A method whose output returns the number of rows and columns respectively, in a given dataframe.
`.columns`                   | A method that returns the column names in a given dataframe.
`.dtypes`                    | A method that returns the data types of a given input.
`.DataFrames`                | A method that returns an object copy of a given input.
`.merge()`                   | A method that merges two dataframes on a specified column.
`.isnull()`                  | A method that returns a boolean value.
`.sum()`                     | A method that adds given inputs together.
`.to_datetime()`             | A method that explicitly converts dates to time.
`dt.month`                   | A method that returns a given date's month.
`dt.year`                    | A method that returns a given date's year.
`set_index()`                | A method that sets an index for a given input.
`.apply`                     | A method or function whereby ...
`.plot(figsize=(a,b))`       | A method for data visualization that returns a plot chart. The `figsize` parameter lets you control the size of the displayed chart.
`.plot(kind='scatter', x='foo', y='bar', figsize=(a,b))` | A method for data visualization that returns a plot chart. The `kind` parameter lets you define the kind or type of plot to render. The `x` parameter represents the value for the x-axis. The `y` parameter represents the value for the y-axis. The `figsize` parameter represents the size of the displayed chart.

For more information, visit the [pandas documentation](https://pandas.pydata.org/docs/) page.


## Final Report
The following Jupyter Notebook compares the temperature and precipitation for Seattle and New York City from July 1st, 2014 through June 30, 2015, using data sourced from Weather Underground.

You will use line plots to visualize comparisons of the following:

1. The Actual Mean Temp for Seattle and New York City.
1. The Record Max Temp for Seattle and New York City.
1. The Actual Precipitation for Seattle and New York City.
1. The Record Precipitation for Seattle and New York City.

You will use scatter plots to visualize comparisons of the following:

1. The Actual Precipitation and Actual Mean Temp for Seattle.
1. The Actual Precipitation and Actual Mean Temp for New York City.

## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)
* Source: [Weather Underground](http://wunderground.com)
