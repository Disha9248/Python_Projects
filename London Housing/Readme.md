# London Housing Data Analysis | Project

![Housing Image](https://github.com/user-attachments/assets/7a758730-dc9f-42e2-b16a-016c82436055)


## Project Overview
This project analyzes London’s housing focusing on property prices, rental affordability, neighborhood comparisons, and factors influencing real estate trends. The goal is to provide insights for buyers, investors, and policymakers.


## Objectives
- Learn how to use Python for data analysis tasks such as aggregation, filtering, and ranking.
- Understand how to calculate and manipulate data in a real-world dataset.
- Identify factors influencing property values.
- Develop skills for performance analysis using Pandas by solving different types of data problems related to user performance.


## Project Level: Beginner
This project is a beginners level project.To get me familiar with the basics of Pandas and to gain knowledge on how to handle real-world data analysis problems.I have worked with a small dataset and had used Pandas library to solve different tasks that are commonly encountered in data analytics.


## Dataset
The data for this project is sourced from the Kaggle dataset:
 - **Dataset Link**: [London Housing Dataset](https://www.kaggle.com/datasets/justinas/housing-in-london)<br><br>


## Dataset Columns
Dataset contains total 6 columns namely :
- Date
- Area
- Average Price
- Code
- Houses_Sold
- No_Of_Crimes<br><br>
  

## SQL Problems and Questions
Here are the SQL problems that I have solved as part of this project:

#### Q1) Convert the Datatype of 'Date' column to Date-Time format.
#### Q2) Add a new column ''year'' in the dataframe, which contains years only.
#### Q2B) Add a new column ''month'' as 2nd column in the dataframe, which contains month only.
#### Q3) Remove the columns 'year' and 'month' from the dataframe.
#### Q4) Show all the records where 'No. of Crimes' is 0. And, how many such records are there ?
#### Q5) What is the maximum & minimum 'average_price' per year in england ?
#### Q6) What is the Maximum & Minimum No. of Crimes recorded per area ?
#### Q7) Show the total count of records of each area, where average price is less than 100000.<br><br>



## The Commands That Are Used In This Project 

- `import pandas as pd` - To import Pandas library<br>
- `pd.read_csv` - To import the CSV file in Jupyter notebook<br>
- `head()` - It shows the first N rows in the data (by default, N=5)<br>
- `shape` - It shows the total no. of rows and no. of columns of the dataframe<br>
- `df.info()` - To show the datatype of each column.
- `pd.to_datetime()` - Converts the data-type of Date-Time Column into datetime[ns] datatype.
- `df[new col] = df['date col'].dt.year` - Creating a new column with only year values
- `df[new col] = df[date col].dt.month` - Creating a new column with only month values.
- `df.drop(['Col_name'] , axis=1 , inplace = True)` - To drop a column from the dataframe permanently.
- `df.groupby(‘Col_name’)` - To form groups of all unique values of the column.
- `df[df.Col_1 = = ‘Element1’]` - Filtering – We are accessing all records with Element1 only of Col_1.
- `df.groupby(‘Col_1’)[‘Col_2’] .mean( )` - To create groups - Two Keys – Apply on Col_2 grouped by Col_1.
- `df['area'].unique()` - To check unique values in column.



## Conclusion
This project provides an excellent opportunity for me as a beginners to gain Pandas knowledge to solve practical data problems. By working through these Python queries, I gain hands-on experience with data cleaning, filtering, date manipulation, and conditional logic.









