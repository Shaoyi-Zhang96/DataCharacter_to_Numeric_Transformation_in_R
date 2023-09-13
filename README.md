# DataCharacter_to_Numeric_Transformation_in_R

Works in situations when you have a large dataset with continuous variables, character variables (yes/no, cold/cool/hot, etc). This saves you the time of recoding the character variables into categorical/ordinal variables for each column.

R Script: Convert character columns to numeric categories. Skips continuous variables. 
Converts "none", "NA", "missing", "blank" to 0. Other categories start from 1. Perfect for quick ML data prep.

This R script efficiently transforms all categorical character variables within a dataset into numeric categorical variables, 
while preserving continuous variables untouched. Key features include:

Automatic detection and skipping of columns with continuous variables.
Standardized treatment for missing values, regardless if they are labeled as "none", "NA", "missing", or "blank", converting them to the numeral 0.
Ensures the consistent transformation of categorical values starting from numeral 1 and incrementing thereafter.
Ideal for data scientists and R users seeking a quick and systematic preprocessing step for machine learning preparation or data analysis."

Note: This description is crafted to be both informative and concise, capturing the key functionalities of the script and its intended audience.
