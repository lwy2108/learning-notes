# pandas

With Python in Jupyter Notebook

Referenced from [Corey Schafer's Pandas Tutorials (Youtube Playlist)](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS), [pandas-docs/API reference](https://pandas.pydata.org/docs/reference/index.html#api)

# Import library

```py
# by convention
import pandas as pd
```

# Read data file

```py
# read .csv file (Comma Separated Values)
df = pd.read_csv(file_path)

# read Excel file (.xlsx, .ods, ...)
df = pd.read_excel(file_path)

# df is short for dataframe
# file_path is given as str, relative to location of .py file
```
