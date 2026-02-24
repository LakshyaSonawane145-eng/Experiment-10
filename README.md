# Experiment-10
#Title : Study of Pandas library
**Theory**

Pandas (Panel Data) is an open-source Python library used for data manipulation and analysis. It provides powerful data structures like Series (1D) and DataFrame (2D) to handle structured data efficiently. Pandas is widely used in data analysis because of its simple and powerful built-in commands.

🔹 1. Data Creation Commands
- These commands are used to create data structures:
- pd.Series() → Creates a one-dimensional array with index.
- pd.DataFrame() → Creates a two-dimensional table using dictionary, list, etc.

Example:
pd.Series([10,20,30])
pd.DataFrame(data)

🔹 2. Structure & Information Commands
- These commands help to understand the structure of data:
- df.shape → Returns number of rows and columns.
- df.ndim → Returns number of dimensions.
- df.size → Returns total elements.
- df.columns → Displays column names.
- df.dtypes → Shows datatype of each column.
- These commands are useful to inspect the dataset before analysis.

🔹 3. Data Accessing Commands
- Used to retrieve specific data:
- df["ColumnName"] → Access full column.
- df.loc[row, column] → Access data using label.
- df.iloc[row, column] → Access data using index position.
- df[condition] → Filter data based on condition.
- These commands help in selecting required data for processing.

🔹 4. Data Manipulation Commands
- Used to modify the dataset:
- df["NewColumn"] = value → Add new column.
- df.iloc[] = value → Update specific value.
- df.drop("Column", axis=1) → Delete a column.
- df.drop(row_index, axis=0) → Delete a row.
- These commands allow editing and managing data easily.

🔹 5. Statistical & Analytical Commands
- Used for basic data analysis:
- df["Column"].mean() → Calculate average.
- df["Column"].min() → Minimum value.
- df["Column"].max() → Maximum value.
- df["Column"].sum() → Total sum.
- df["Column"].count() → Count of values.
- These built-in functions make statistical analysis simple and fast.

📌 Conclusion

Pandas provides a wide range of commands for data creation, inspection, accessing, manipulation, filtering, and statistical analysis. The variety of built-in functions makes data handling easy, efficient, and less time-consuming. Because of these powerful commands, Pandas is an essential library for data analysis and real-world applications in Python.
