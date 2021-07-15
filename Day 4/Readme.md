# Day 4 #
Video Link: [Link](https://youtu.be/QUClKFFn1Vk)

Using Pandas (DataFrames and DataSeries)

- Single-Dimension array is called as **DataSeries** whereas **Multi-dimensional** array is called as DataFrame.
- Creating a DataFrame using `.pd(array, index, columns)
- `.head(n = 5(default))` prints first n rows.
- `.to_csv()` convert the file to Comma Seperated View(CSV file). Also has function that coverts this to Excel, Dictionary.
- `.loc[index_name]` Returns the row with the specified index name.
- `.iloc[index_no], .iloc[index_no, column_no]` returns a series according to the query.
- `Dataframe.iloc[].values` revtriving array of the specified ranges.
- `DataFrame.value_counts()` returns the occurance of each value in the DataFrame.
- `Dataframe.iloc[].unique()` returns unique values in DataFrame.
