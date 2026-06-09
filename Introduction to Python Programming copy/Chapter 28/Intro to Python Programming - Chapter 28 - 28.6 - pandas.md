**Introduction to pandas and Dataframes**
- **pandas** is a Python package that stores and manipulates 2-D datasets
- pandas represents datasets with a **dataframe** object, of data type **DataFrame**, which consists of rows and columns
- A dataframe's row labels are known as the **index** and column labels are known as the **columns**

**Subsetting Data**
- **Subsetting data** involves choosing specific rows and columns from a dataframe according to labels, indices, and slices (a range between 2 indices)

**Subsetting Data Using Comparison and Logical Operators**

| Logical Operator | Description                                                       |
| ---------------- | ----------------------------------------------------------------- |
| &                | AND operator. Outputs True if both operands are True              |
| \|               | OR operator. Outputs True if at least one of the operands is True |
| -                | NOT operator. Outputs the opposite truth value of the expression  |

**Other DataFrame Methods**

| Method            | Parameters                                                               | Description                                                                                                                                                                                                                                                                                                                                                       |
| ----------------- | ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| drop()            | labels=None <br>axis=0 <br>index=None <br>columns=None <br>inplace=False | Removes rows (axis=0`) or columns (`axis=1) from a dataframe by specifying the label name(s) and the axis as parameters. Can also remove a row by specifying the index or a column by the column name as parameters.                                                                                                                                              |
| drop_duplicates() | subset=None<br>inplace=False                                             | Removes duplicate rows from a dataframe. subset specifies the labels of columns used to identify duplicates. If subset=None, all columns are used. Ex: For the country dataframe, df.drop_duplicates(subset=["Name"]) removes any country whose name appears more than once.                                                                                      |
| insert()          | loc<br>column<br>value                                                   | Inserts a column into a specific location of the dataframe. loc specifies the integer position of the new column. column specifies a string or numeric column label. value specifies column values to be inserted. Ex: df.insert(1, "newcol", [99, 89]) inserts a new column into a dataframe labeled "newcol" with 99 in the first row and 89 in the second row. |
| replace()         | to_replace=None<br>value=NoDefault.no_default<br>inplace=False           | Replaces specified values (to_replace) in a dataframe with a different value (value). The variables to_replace and value may be of type int, float, str, dict, list, etc.                                                                                                                                                                                         |
| sort_values()     | by<br>axis=0<br>ascending=True<br>inplace=False                          | Sorts a dataframe's columns or rows. The variable by specifies indices or label names to sort by. Rows (axis=0) or columns (axis=1) can be sorted. Sorting can be in ascending (ascending=True) or descending (ascending=False) order.                                                                                                                            |
