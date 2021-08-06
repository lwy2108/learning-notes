# pandas

With Python in Jupyter Notebook

Referenced from [Corey Schafer's Pandas Tutorials (Youtube Playlist)](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS), [pandas-docs/API reference](https://pandas.pydata.org/docs/reference/index.html#api)

## Import library

```py
# by convention
import pandas as pd
```

## Read data file into dataframe

```py
# read .csv file (Comma Separated Values)
df = pd.read_csv(file_path)

# read Excel file (.xlsx, .ods, ...)
df = pd.read_excel(file_path)

# print the dataframe
df

# df is short for dataframe
# file_path is given as str, relative to location of .py file
# read in multiple dataframes to different variables, e.g. df_schema, ...
```

## Dataframes

```py
# a dataframe can be thought of simply as a table, consisting of rows,
# and columns, with an index for rows and headers for columns

# more specifically, ?

# the leftmost column is the index, similar to lists

# return a tuple of a dataframe's dimensions
df.shape
# e.g. output: (4, 2); 4 rows and 2 columns

# summarise a dataframe
df.info
# print a truncated representation of some columns (with index)

# return the first 5 rows
df.head()
# alternative: pass an argument for a specfic number of rows
df.head(3)
```

## Display settings

```py
# increase the columns displayed for wider dataframes
pd.set_option('display.max_columns', columns_displayed)

# increase the rows displayed for longer dataframes
pd.set_option('display.max_rows', rows_displayed)

# derive columns_displayed and rows_displayed from the dataframe's
# dimensions

# these settings prevent the truncation of dataframes when printed
```

## Accessing specific data

```py
# ...
```
