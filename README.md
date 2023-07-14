# ML_Project_Data_Preprocessing

This repository contains a robust data preprocessing system designed to address common challenges such as missing values, outliers, inconsistent formatting, and noise. The objective of this project is to enhance the quality, reliability, and usefulness of the data for machine learning.

## Dataset
Employee.csv

## Key Components

The ML_Project_Data_Preprocessing repository focuses on the following key components:

### Data Exploration

The first step in data preprocessing is to explore the data. This involves listing down the unique values in each feature and finding their lengths. Statistical analysis is performed, and the columns may be renamed for clarity and consistency.

### Data Cleaning

Data cleaning is an essential step in data preprocessing. In this project, missing and inappropriate values are identified and treated appropriately. Duplicate rows are removed, and outliers are identified.

Specifically, the following actions are taken during data cleaning:

- The value 0 in the "age" column is replaced with NaN.
- Null values in all columns are treated using various measures, such as removing rows with null values or replacing null values with mean, median, or mode values.

### Data Analysis

Data analysis is performed to gain insights from the preprocessed data. In this project, the following analysis tasks are performed:

- Filtering the data based on conditions such as age > 40 and salary < 5000.
- Creating a chart to visualize the relationship between age and salary.
- Counting the number of people from each place and representing it visually.

### Data Encoding

Categorical variables need to be converted into numerical representations to make them suitable for analysis by machine learning algorithms. This project includes techniques such as one-hot encoding and label encoding to perform data encoding.

### Feature Scaling

After the data encoding process, feature scaling is performed to normalize the features. This project uses standard scaling (StandardScaler) and min-max scaling (MinMaxScaler) techniques to scale the features.
