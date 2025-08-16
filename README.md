Black Friday Sales Data Analysis (Pandas Case Study)
This repository contains a comprehensive data analysis case study performed using the Pandas library in Python. The analysis focuses on the "Black Friday Dataset," which comprises sales transactions captured at a retail store.

Problem Statement: The primary goal of this case study is to explore and understand the Black Friday sales data, with an ultimate aim to predict purchase amounts (though the prediction model itself is not included in this specific file).

Key Features of the Analysis:

Pandas Fundamentals: Demonstrates core Pandas functionalities for data manipulation, including:
Data loading from CSV files (pd.read_csv).
Inspecting DataFrame shape, dimensions, and data types (.shape, .ndim, .info(), .dtypes).
Viewing top and bottom rows (.head(), .tail()).
Checking for duplicate rows (.duplicated()).
Subsetting DataFrames by selecting specific columns.
Changing column data types (.astype()).
Descriptive Statistics: Generates statistical summaries for both numerical and categorical features (.describe()).
Categorical Data Exploration:
Analyzes the distribution of unique values in categorical columns (.unique(), .value_counts()).
Calculates percentage distribution of product IDs to identify top-selling products.
Demonstrates value replacement in categorical columns.
Missing Value Handling:
Identifies missing values (.isnull().sum()).
Illustrates two common strategies for handling missing data:
Dropping: Removing rows or columns with missing values (.drop()).
Imputation: Filling missing values using forward-fill (.fillna(method="pad")) and backward-fill (.fillna(method="backfill")).
Data Indexing and Slicing:
Utilizes label-based indexing (.loc) and integer-based indexing (.iloc) for precise data selection.
Demonstrates how to fetch specific rows and columns, including rows with maximum/minimum values (.idxmax(), .idxmin()).
Shows single-value access using .at() and .iat().
Applies Boolean indexing for complex data filtering based on multiple conditions.
Uses the .isin() method for searching specific values within the DataFrame.
Illustrates the .mask() function for conditional data visualization.
Data Sorting: Explores sorting data by both index labels (.sort_index()) and column values (.sort_values()), including sorting by multiple columns and in ascending/descending order.
Data Aggregation:
Applies various aggregation functions (e.g., sum, mean) on single and multiple columns using np.sum, np.mean, and .aggregate().
Demonstrates applying multiple aggregation functions simultaneously.
Function Application: Uses the .apply() method for row/column-wise function application, including creating new categorical columns based on existing data (e.g., tagging transactions as "High Focused" or "General").
Group-by Operations: Performs data grouping using .groupby() on single and multiple columns, followed by aggregation to derive insights (e.g., total and average purchase amounts by gender).
One-Hot Encoding: Shows how to convert categorical columns into numerical representations using pd.get_dummies() for further machine learning tasks.
Dataset:

Name: Black Friday Dataset
Source: https://datahack.analyticsvidhya.com/contest/black-friday/
Description: Contains sales transaction data from a retail store, with 550,069 rows and 12 columns.
This case study serves as an excellent resource for anyone looking to learn or refresh their skills in data analysis using the powerful Pandas library.
