# AIM: STUDY OF PANDAS LIBRARY


# THEORY:
Pandas stands for Panel Data. It is mainly used for working with structured data like tables.
It helps in performing tasks such as Exploratory Data Analysis (EDA) and data cleaning in an easy and organized way.
It focuses on understanding how Pandas is used to handle structured data, perform data cleaning, and do basic data analysis.

# Creating a Series:
A Series is a one-dimensional data structure in Pandas. In this file, a Series is created using a list of numbers (10, 20, 30, 40).
It shows how Pandas can store and display simple linear data. A Series consists of values and an associated index.
The index represents the position labels for each element in the Series. Series can store different types of data such as integers, floats, strings, or objects.
A Series can also be created from NumPy arrays or dictionaries.

# Creating a DataFrame:
A DataFrame is a two-dimensional data structure, similar to a table with rows and columns. 
In this experiment, a DataFrame is created using a dictionary containing student names and marks. This shows how structured data can be organized in tabular form.
Each column in a DataFrame can contain different data types. DataFrames support labeled rows and columns, making data easy to access.
A DataFrame can also be created from lists, CSV files, Excel files, or databases. It is the most commonly used data structure in Pandas.

# Viewing Data:
The file explains how to view the first five rows using head() and the last five rows using tail(). 
These functions help in quickly checking the data stored in a DataFrame. The number of rows displayed can be changed, for example head(3) shows the first three rows.
tail() is useful for checking recently added or last entries in the dataset. These functions help in quick inspection of large datasets.
They are often used during data exploration and debugging.

# Understanding DataFrame Structure:
Different properties are used to understand the structure of the DataFrame:
> shape shows the number of rows and columns.
> ndim shows the number of dimensions.
> size shows the total number of elements.
> columns displays column names.
> dtypes shows the data type of each column.
These help in analyzing the structure of the dataset.
info() can also be used to get a summary of the DataFrame including non-null values. describe() provides statistical details for numerical columns.
Understanding the structure helps in data cleaning and preprocessing. These properties help identify missing values and incorrect data types.

# Accessing Data:
The experiment demonstrates how to access:
> A single column using column name.
> A specific row using loc[].
This allows selective retrieval of data from the DataFrame.
Multiple columns can be accessed by passing a list of column names. iloc[] can be used to access data based on index position.
Conditional access can be applied to retrieve specific records. Accessing data properly helps in efficient data analysis.

# Adding and Updating Data:
A new column called “Grade” is added to the DataFrame. It also shows how to update existing data by modifying the marks of a student using loc[].
This demonstrates how Pandas allows editing of data easily. New rows can also be added to a DataFrame.
Columns can be added using assignment operations. Existing values can be updated using conditions or indexing.
This flexibility makes Pandas useful for data preprocessing tasks.

# Deleting Data:
A column is removed using the drop() function with axis=1. It also explains that axis=0 is used to delete rows.
This helps in managing and modifying the dataset structure. Multiple columns can be removed by passing a list of column names.
The inplace=True parameter allows direct modification of the DataFrame. Unnecessary or irrelevant data can be removed easily.
This step is important during data cleaning.

# Basic Statistical Analysis:
The file performs basic statistical operations on the “Marks” column:
> mean() calculates average marks.
> max() finds highest marks.
> min() finds lowest marks.
This shows how Pandas can quickly perform simple data analysis.
sum() can be used to calculate the total marks.
count() returns the number of non-null values.
median() provides the middle value in the dataset.
These functions help in understanding data distribution.

# Filtering Data:
The experiment applies a condition to filter students who scored more than 80 marks. 
This demonstrates how conditional filtering can be used to extract specific data from the DataFrame. Multiple conditions can be applied using AND (&) and OR (|) operators.
Filtering helps in selecting relevant data for analysis. It is commonly used in data preprocessing and decision making.
Conditions can also be applied to multiple columns simultaneously.


# CONCLUSION:
This experiment helps in understanding the basic features of the Pandas library, including creating data structures,
modifying data, analyzing structure, performing statistical operations, and applying conditions. It provides a strong foundation for handling structured data in Python.







