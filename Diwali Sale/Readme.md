# Diwali Sale Analysis | Project

![Diwali Sale Image](https://github.com/user-attachments/assets/dcd524d8-3446-4e68-9e38-5527a4ba99ba)


## Project Overview
This project analyzes Diwali sale data to uncover customer spending patterns, popular product categories, seasonal demand fluctuations, and e-commerce trends. The insights will help businesses and retailers optimize pricing, marketing, and inventory strategies.


## Objectives
- Identify top-selling product categories during Diwali sales.
- Analyze customer spending behavior based on demographics.
- Learn how to use Python for data analysis tasks such as aggregation, filtering, and ranking.
- Understand how to calculate and manipulate data in a real-world dataset.
- Develop skills for performance analysis using Pandas by solving different types of data problems related to user performance.


## Project Level: Beginner
This project is a beginners level project.To get me familiar with the basics of Pandas and to gain knowledge on how to handle real-world data analysis problems.I have worked with a small dataset and had used Pandas library to solve different tasks that are commonly encountered in data analytics.


## Dataset
The data for this project is sourced from the Kaggle dataset:
 - **Dataset Link**: [Diwali Sale Dataset](https://www.kaggle.com/datasets/saadharoon27/diwali-sales-dataset)<br><br>


## Dataset Columns
Dataset contains total 13 columns namely :
- User ID
- Cust_name
- Product ID
- Gender
- Age Group
- Age
- Marital_Status
- State
- Zone
- Occupation
- Product_category
- Orders
- Amount<br><br>
  

## SQL Problems and Questions
Here are the SQL problems that I have solved as part of this project:

#### Q1) Gender - <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Maximum buyers and maximum purchasing power with respect to gender.<br>
#### Q2) Age - <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Maximum buyers with respect to age.<br>
#### Q3) State - <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Maximum orders with respect to State.<br>
#### Q4) Marital Status - <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Maximum buyers with respect to Marital Status.<br>
#### Q5) Occupation - <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Maximum buyers with respect to Occupation.<br>
#### Q6) Product Category - <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Top Selling Products.<br><br>



## The Commands That Are Used In This Project 

- `import pandas as pd` - To import Pandas library<br>
- `pd.read_csv` - To import the CSV file in Jupyter notebook<br>
- `head()` - It shows the first N rows in the data (by default, N=5)<br>
- `shape` - It shows the total no. of rows and no. of columns of the dataframe<br>
- `df.isnull().sum()` - It detects the missing values from each column of the dataframe.<br>
- `dropna()` - To drop the column with null value<br>
- `value_counts()` - In a column, it shows all the unique values with their count. It can be applied to a single column only.<br>
- `sort_values()` - It sort values in ascending and descending orders. Sort the entire dataframe by the values of the given column.<br>
- `df.groupby([column])[column].sum()` - To form groups of all unique values of the column and than sum it.<br>
- `import seaborn as sns` - To import the Seaborn library.<br>
- `import matplotlib.pyplot as plt` - To import the Matplotlib library.<br>
- `sns.barplot()` - To plot bar graphs.<br>
- `sns.set()` - To set the size of graphs.<br>


## Conclusion
From the above analysis we came to know that
1. Most of the buyers are Unmarried Women in Age Group of (26-30)
2. They are mostly from UP, Maharashtra and Karnataka
3. They are mostly from IT, Healtcare and Aviation Profession
4. They mostly buy products from Food, Clothing and Electronics category.
This project provides an excellent opportunity for me as a beginners to gain Pandas knowledge to solve practical data problems. By working through these Python queries, I gain hands-on experience with data cleaning, filtering, date manipulation, and conditional logic.

