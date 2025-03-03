# Udemy Course Data Analysis | Project

![Udemy Image](https://github.com/user-attachments/assets/fa7f1fe3-8198-4638-b127-116b520cc5f6)


## Project Overview
This project analyzes Udemy course data to uncover trends in course popularity, pricing, student engagement, and instructor performance. The goal is to provide insights that help learners choose the best courses and instructors improve their offerings.


## Objectives
- Identify the most popular course categories and subcategories.
- Compare free vs. paid courses in terms of ratings and enrollments.
- Learn how to use Python for data analysis tasks such as aggregation, filtering, and ranking.
- Understand how to calculate and manipulate data in a real-world dataset.
- Develop skills for performance analysis using Pandas by solving different types of data problems related to user performance.


## Project Level: Beginner
This project is a beginners level project.To get me familiar with the basics of Pandas and to gain knowledge on how to handle real-world data analysis problems.I have worked with a small dataset and had used Pandas library to solve different tasks that are commonly encountered in data analytics.


## Dataset
The data for this project is sourced from the Kaggle dataset:
 - **Dataset Link**: [Udemy Course Dataset](https://www.kaggle.com/datasets/hosammhmdali/udemy-courses-dataset)<br><br>


## Dataset Columns
Dataset contains total 11 columns namely :
- Course_id
- Course_title
- Is_paid
- Price
- Num_subscribers
- Num_reviews
- Num_lectures
- Level
- Content_duration
- Published_timestamp
- Subject<br><br>
  

## SQL Problems and Questions
Here are the SQL problems that I have solved as part of this project:

#### Q1) What are all different subjects for which Udemy is offering courses ?
#### Q2) Which subject has the maximum number of courses.
#### Q3) Show all the courses which are Free of Cost.
#### Q4) Show all the courses which are Paid.
#### Q5) Which are Top Selling Courses ?
#### Q6) Which are Least Selling Courses ?
#### Q7) Show all courses of Graphic Design where the price is below 100 ?
#### Q8) List out all the courses that are related to 'Python'.
#### Q9) What are courses that were published in the year 2015 ?
#### Q10) What is the Max. Number of Subscribers for Each Level of courses ?<br><br>



## The Commands That Are Used In This Project 

- `import pandas as pd` - To import Pandas library<br>
- `pd.read_csv` - To import the CSV file in Jupyter notebook<br>
- `head()` - It shows the first N rows in the data (by default, N=5)<br>
- `shape` - It shows the total no. of rows and no. of columns of the dataframe<br>
- `df.info()` - To show the datatype of each column.
- `pd.to_datetime()` - Converts the data-type of Date-Time Column into datetime[ns] datatype.
- `unique()` - It shows the all unique values of the column.
- `value_counts` - In a column, it shows all the unique values with their count. It can be applied to a single column only.
- `df[df.Col_1 = = ‘Element1’]` - Filtering – We are accessing all records with Element1 only of Col_1.
- `df.sort_values(‘Col_name' , ascending=False)` - To sort the dataframe wrt any column values in descending order.
- `df[ (df.Col1 = = ‘Element1’) & (df.Col2 == ‘Element2’)]` - Multilevel filtering - And Filter – Filtering the data with two & more items.
- `str.contains('Value_to_match’)` - To find the records that contains a particular string.
- `dtypes` - To show datatypes of each column..
- `dt.year` - Creating a new column with only year values.
- `df.groupby(‘Col_1’)['Col_2'].max()` - Using groupby with two different columns.


## Conclusion
This project provides an excellent opportunity for me as a beginners to gain Pandas knowledge to solve practical data problems. By working through these Python queries, I gain hands-on experience with data cleaning, filtering, date manipulation, and conditional logic.

The Udemy course data analysis provides insights into course offerings, pricing, popularity, and subject trends. Key findings include:


- Identified different subjects available on Udemy.
- Determined which subject has the highest number of courses.
- Filtered courses based on pricing to analyze availability and accessibility.
- Listed courses in the Graphic Design category priced below $100.
- Extracted all courses related to Python, indicating its popularity in online learning.
- Identified courses published in 2015 to track historical trends.
- Found the maximum number of subscribers for each course level (beginner, intermediate, advanced).

This analysis helps learners and educators understand course trends, pricing strategies, and subject popularity on Udemy, aiding in informed decision-making.


