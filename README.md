# AIM: STUDY OF PANDAS LIBRARY


# THEORY:
Pandas stands for Panel Data. It is mainly used for working with structured data like tables.
It helps in performing tasks such as Exploratory Data Analysis (EDA) and data cleaning in an easy and organized way.
It focuses on understanding how Pandas is used to handle structured data, perform data cleaning, and do basic data analysis.

# Creating a Series:
A Series is a one-dimensional data structure in Pandas. In this file, a Series is created using a list of numbers (10, 20, 30, 40).
It shows how Pandas can store and display simple linear data.

# Creating a DataFrame:
A DataFrame is a two-dimensional data structure, similar to a table with rows and columns. 
In this experiment, a DataFrame is created using a dictionary containing student names and marks. This shows how structured data can be organized in tabular form.

# Viewing Data:
The file explains how to view the first five rows using head() and the last five rows using tail(). 
These functions help in quickly checking the data stored in a DataFrame.

# Understanding DataFrame Structure:
Different properties are used to understand the structure of the DataFrame:
> shape shows the number of rows and columns.
> ndim shows the number of dimensions.
> size shows the total number of elements.
> columns displays column names.
> dtypes shows the data type of each column.
These help in analyzing the structure of the dataset.

# Accessing Data:
The experiment demonstrates how to access:
> A single column using column name.
> A specific row using loc[].
This allows selective retrieval of data from the DataFrame.

# Adding and Updating Data:
A new column called “Grade” is added to the DataFrame. It also shows how to update existing data by modifying the marks of a student using loc[].
This demonstrates how Pandas allows editing of data easily.

# Deleting Data:
A column is removed using the drop() function with axis=1. It also explains that axis=0 is used to delete rows.
This helps in managing and modifying the dataset structure.

# Basic Statistical Analysis:
The file performs basic statistical operations on the “Marks” column:
> mean() calculates average marks.
> max() finds highest marks.
> min() finds lowest marks.
This shows how Pandas can quickly perform simple data analysis.

# Filtering Data:
The experiment applies a condition to filter students who scored more than 80 marks.
This demonstrates how conditional filtering can be used to extract specific data from the DataFrame.


# CONCLUSION:
This experiment helps in understanding the basic features of the Pandas library, including creating data structures,
modifying data, analyzing structure, performing statistical operations, and applying conditions. It provides a strong foundation for handling structured data in Python.







