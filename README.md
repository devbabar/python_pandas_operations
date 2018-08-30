# python_pandas_operations.
This script will demonstrate several operations for data manipulation and analysis using python's Pandas software library.

# Objective:
* Create a DataFrame.
* How to grab any column, it return a Series.
* Grab multiple columns, it will return a DataFrame.
* Insert a new column, add two columns and add sum of values into new column.
* Drop or delete any column.
* Deleting any row.

### Using loc() and iloc()
* Selecting rows using loc( ) and iloc( ) method.
* Multiple rows return Dataframe.
* Select a specific item in the DataFrame.
* Get a subset of any 2 rows.

### Conditional Operations.
* Show values which are greater than 0, return boolean values.
* Apply condition on only one column, it will return boolean.
* Get the whole DataFrame back but only apply condition to only one column.
* Multiple conditions

### Reset index
* Index becomes a new column.
* Insert new column and set it as index.

# Steps To Run:
For this demonstration, I am using the Jupyter Notebook, open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

### Step 1:
Create a new folder and called it pandas.

$ mkdir pandas ---> $ cd pandas ----> $ mkdir python_pandas_operations

### Step 2:
Create a virtual enviroment and install dependencies by running requirements.txt.

$ pip install virtualenv env

$ source env/bin/activate

$ pip install -r requirements.txt

### Step 3:
Run the script.

$ cd python_pandas_operations

$ jupyter notebook
