
## _Pandas_ in Python:

#### Importing:
```
In [1]: import numpy as np

In [2]: import pandas as pd
```

#### Object Creation:
* Creating a Series by passing a list of values, letting pandas create a default integer index:
```
In [3]: s = pd.Series([1, 3, 5, np.nan, 6, 8])
```

* Creating a DataFrame by passing a NumPy array, with a datetime index and labeled columns:
```
In [5]: dates = pd.date_range('20130101', periods=6)
```

* Creating a DataFrame by passing a dict of objects that can be converted to series-like.
```
In [9]: df2 = pd.DataFrame({'A': 1.,
   ...:                     'B': pd.Timestamp('20130102'),
   ...:                     'C': pd.Series(1, index=list(range(4)), dtype='float32'),
   ...:                     'D': np.array([3] * 4, dtype='int32'),
   ...:                     'E': pd.Categorical(["test", "train", "test", "train"]),
   ...:                     'F': 'foo'})
   ...: 
```


# class pandas

- class pandas.DataFrame(data=None, index=None, columns=None, dtype=None, copy=False)

- Two-dimensional, size-mutable, potentially heterogeneous tabular data. Data structure also contains labeled axes (rows and columns). Arithmetic operations align on both row and column labels. Can be thought of as a dict-like container for Series objects. The primary pandas data structure.
## Parameters

- datandarray (structured or homogeneous), Iterable, dict, or DataFrame Dict can contain Series, arrays, constants, dataclass or list-like objects. If data is a dict, column order follows insertion-order.

- Changed in version 0.25.0: If data is a list of dicts, column order follows insertion-order.


- DataFrame.to_numpy() gives a NumPy representation of the underlying data. Note that this can be an expensive operation when your DataFrame has columns with different data types, which comes down to a fundamental difference between pandas and NumPy: NumPy arrays have one dtype for the entire array, while pandas DataFrames have one dtype per column. When you call DataFrame.to_numpy(), pandas will find the NumPy dtype that can hold all of the dtypes in the DataFrame. This may end up being object, which requires casting every value to a Python object.
- DataFrame.to_numpy() does not include the index or column labels in the output.

- describe() shows a quick statistic summary of your data.
- When selecting subsets of data, square brackets [] are used. Inside these brackets, you can use a single column/row label, a list of column/row labels, a slice of labels, a conditional expression or a colon.

    - Select specific rows and/or columns using loc when using the row and column names
    - Select specific rows and/or columns using iloc when using the positions in the table
    - You can assign new values to a selection based on loc/iloc.

- Getting data in to pandas from many different file formats or data sources is supported by read_* functions.
- Exporting data out of pandas is provided by different to_*methods.

    
#### Missing data:
pandas primarily uses the value np.nan to represent missing data. It is by default not included in computations. See the Missing Data section.

Reindexing allows you to change/add/delete the index on a specified axis. This returns a copy of the data.
```
In [55]: df1 = df.reindex(index=dates[0:4], columns=list(df.columns) + ['E'])
```
