# Deleting rows and columns using python

The provided code performs data analysis on a dataset using Python and Pandas. Here's a summary of the code:
<br>
<br>
The necessary libraries (Pandas, NumPy, Matplotlib, and Seaborn) are imported.<br>
The code reads a CSV file called 'train.csv' into a Pandas DataFrame named df.<br>
The shape of the DataFrame is displayed, showing the number of rows and columns.<br>
The first six rows of the DataFrame are displayed to get an overview of the data.<br>
The code configures Pandas options to display all columns and rows when printing DataFrames.<br>
The last six rows of the DataFrame are displayed.<br>
Information about the DataFrame, such as column names, data types, and non-null values, is shown.<br>
A heatmap is created to visualize missing values in the DataFrame.<br>
The number of missing values for each column is calculated and displayed.<br>
Columns with more than 17% missing values are identified and stored in drop_columns.<br>
The DataFrame is updated by dropping the identified columns with excessive missing values.<br>
The shape of the updated DataFrame is displayed.<br>
Another heatmap is created to visualize missing values in the updated DataFrame.<br>
The DataFrame is further updated by dropping rows that contain any missing values.<br>
The shape of the final DataFrame after dropping rows is displayed.<br>
A heatmap is created to visualize missing values in the final DataFrame.<br>
The number of missing values for each column in the final DataFrame is calculated and displayed.<br>
The column names of numerical data types (int64 and float64) in the final DataFrame are shown.<br>
Density plots are created to visualize the distribution of the 'MSSubClass' column in different scenarios.<br>
Overall, the code focuses on loading and examining a dataset, handling missing values, and visualizing the data using heatmaps and density plots.<br>







