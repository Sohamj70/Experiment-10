###  **Experiment – 10**
Title: Study of Pandas Library

### **Aim:**
To study the basic commands of the Pandas library used for data manipulation and analysis in Python.

### **Theory:**
Pandas (Panel Data) is an open-source Python library used for data manipulation and analysis. It provides powerful data structures such as Series and DataFrame which help in handling structured data efficiently. Pandas is widely used in data science, machine learning, and statistical analysis because of its easy-to-use built-in commands.
###### 1. Data Creation Commands
These commands are used to create data structures in Pandas.
- pd.Series() – Creates a one-dimensional labeled array with index.
- pd.DataFrame() – Creates a two-dimensional table using lists or dictionaries.
  
###### 2. Structure and Information Commands

These commands help to understand the structure of the dataset.

- df.shape – Returns the number of rows and columns.
- df.ndim – Returns the number of dimensions.
- df.size – Returns the total number of elements in the dataset.
- df.columns – Displays the column names.
- df.dtypes – Shows the datatype of each column.

These commands help in inspecting and understanding the dataset before performing analysis.

###### 3. Data Accessing Commands

These commands are used to retrieve specific data from the dataset.
- df["ColumnName"] – Access a complete column
- df.loc[row, column] – Access data using row and column labels.
- df.iloc[row, column] – Access data using index position.
- df[condition] – Filter rows based on a condition.

These commands help in selecting the required data for processing.

###### 4. Data Manipulation Commands

These commands are used to modify or manage the dataset.

- df["NewColumn"] = value – Adds a new column to the dataset.
- df.iloc[] = value – Updates a specific value.
- df.drop("Column", axis=1) – Deletes a column.
- df.drop(row_index, axis=0) – Deletes a row.

These commands allow editing and managing the dataset easily.

###### 5. Statistical and Analytical Commands
These commands are used to perform basic data analysis.

- df["Column"].mean() – Calculates the average value.
- df["Column"].min() – Finds the minimum value.
- df["Column"].max() – Finds the maximum value.
- df["Column"].sum() – Calculates the total sum.
- df["Column"].count() – Counts the number of values.
These built-in functions make statistical analysis simple and efficient.

### **Conclusion**

Pandas provides a wide range of commands for data creation, inspection, accessing, manipulation, filtering, and statistical analysis. The availability of powerful built-in functions makes data handling easy and efficient. Therefore, Pandas is an important library used in Python for data analysis and real-world applications.
