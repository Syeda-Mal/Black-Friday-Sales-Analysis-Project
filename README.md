# Black Friday Sales Analysis Project

# Overview
This project involves the analysis of a Black Friday sales dataset using Python and various data analysis libraries, such as Pandas and Seaborn.

## Purpose
The goal is to gain insights into customer behavior, purchasing patterns, and the impact of different demographic factors on sales.Some example questions include:
 Were purchasing patterns dependant on gender and age groups?
 Should consumer's occupation be considered impactful on sales?
 
# Table of content
-- Loading & Cleaning the Dataset
-- Performing basic analysis on columns
-- Analysis (Based on gender, Age, Marital Status)
-- Multicolumn Analysis
-- Analysis (Based on occupation & Gender)
-- Combining Gender and Marital Status

## Dataset (Columns)
1. User_ID
2. Product_ID
3. Gender
4. Age
5. Occupation
6. City_Category
7. Stay_In_Current_City_Years
8. Marital_Status
9. Product_Category_1
10. Product_Category_2
11. Product_Category_3
12. Purchase

## Loading & Cleaning the Dataset
The dataset is loaded using Pandas, and basic information about its structure is displayed using df.info() and df.head(). Null values in the dataset are identified and handled, with columns containing excessive null values dropped to maintain data integrity.

## Performing basic analysis on columns
Basic statistics and visualizations are performed on various columns, such as the count of unique values, summary statistics, and total purchase amount.

## Analysis
### Gender Analysis
Analysis is conducted on the 'Gender' column, including the count of each gender, purchasing patterns, and visualizations representing the gender distribution.

### Age & Marital Status Analysis
The 'Age' and 'Marital_Status' columns are analyzed individually, including visualizations depicting the age distribution, amount spent by age group, and the marital status distribution.

### Multi Column Analysis
Relationships between multiple columns are explored through visualizations, such as the interaction between 'Gender' and 'Age', 'Gender' and 'Marital_Status', 'City_Category' and 'Age', and more.

### Occupation & Product Analysis
Analysis is performed on the 'Occupation' column, including count, purchase amount, and mean purchase amount for each occupation. The 'Product_Category_1' column is analyzed, showing the count, purchase amount, and mean purchase amount for each category. Top products based on purchase amount and mean purchase amount are visualized.

### Combining Gender and Marital Status
A combined analysis is performed to understand the relationship between 'Gender' and 'Marital_Status', including visualizations depicting the distribution.

# Conclusion
The detailed exploration of various columns and their interactions contributes to a better understanding of the factors influencing sales during Black Friday. 
