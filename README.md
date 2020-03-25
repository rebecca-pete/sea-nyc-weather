# Weather Comparisons: Seattle & New York City

## Introduction

This report explores the temperature and precipitation data for Seattle and New York City. Using a Jupyter Notebook, you will explore and filter weather data to determine the temperature range at which both cities receive the most precipitation.

This report uses data collected by [Weather Underground](http://wunderground.com) from July 1st, 2014 through June 30, 2015.

## Data dictionary

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
matrix                       | An array of arrays.
method chaining              | A programming technique that allows the user to "chain" or attach subsequent methods to a single object.

## API reference

The following API reference section is divided by Python library.

### pandas methods

Method                       | Description
---                          |---------
`.read_csv('foo.csv')`       | A pandas library method used to read a given file.
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


### numpy methods

Method                       | Description
---                          |---------
`.read_csv('foo.csv')`       | A pandas library method used to read a given file.
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
`.plot(figsize=(a,b))`       | A matplotlib.pyplot library method for data visualization that returns a plot chart. The `figsize` parameter lets you control the size of the displayed chart.
`.plot(kind='scatter', x='foo', y='bar', figsize=(a,b))` | A method for data visualization that returns a plot chart. The `kind` parameter lets you define the kind or type of plot to render. The `x` parameter represents the value for the x-axis. The `y` parameter represents the value for the y-axis. The `figsize` parameter represents the size of the displayed chart.

### matplotlib.pyplot methods

Method                       | Description
---                          |---------
`.read_csv('foo.csv')`       | A pandas library method used to read a given file.
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
`.plot(figsize=(a,b))`       | A matplotlib.pyplot library method for data visualization that returns a plot chart. The `figsize` parameter lets you control the size of the displayed chart.
`.plot(kind='scatter', x='foo', y='bar', figsize=(a,b))` | A matplotlib.pyplot library method for data visualization that returns a plot chart. The `kind` parameter lets you define the kind or type of plot to render. The `x` parameter represents the value for the x-axis. The `y` parameter represents the value for the y-axis. The `figsize` parameter represents the size of the displayed chart.

For more information, visit the [pandas documentation](https://pandas.pydata.org/docs/) page.

## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)
* Sources: [Weather Underground](http://wunderground.com), [538 US Weather History](https://github.com/fivethirtyeight/data/tree/master/us-weather-history)
  
**Note:** This project uses CSV files referenced in the [538 US Weather History](https://github.com/fivethirtyeight/data/tree/master/us-weather-history) repo. The weather data for these files was collected by [Weather Underground](http://wunderground.com).
