# Police Data Analysis | Project

![Police Data](https://github.com/user-attachments/assets/749faa12-e38d-4b27-97e6-1b2d87b3602d)


## Project Overview
This project analyzes traffic police data to uncover trends in road violations and law enforcement efficiency. The goal is to provide insights for improving road safety, reducing accidents, and optimizing traffic management strategies.


## Objectives
- Identify the most common traffic violations and their frequency.
- Analyze accident trends based on gender.
- Learn how to use Python for data analysis tasks such as aggregation, filtering, and ranking.
- Understand how to calculate and manipulate data in a real-world dataset.


## Project Level: Beginner
This project is a beginners level project.To get me familiar with the basics of Pandas and to gain knowledge on how to handle real-world data analysis problems. I have worked with a small dataset and had used Pandas library to solve different tasks that are commonly encountered in data analytics.


## Dataset
The data for this project is sourced from the Kaggle dataset:
 - **Dataset Link**: [Police Data](https://www.kaggle.com/datasets/niteshsahu99/police-data)<br><br>



## SQL Problems and Questions
Here are the SQL problems that I have solved as part of this project:

#### Q1) Remove the column that only contains missing values.
#### Q2) For Speeding , were Men or Women stopped more often ? 
#### Q3) Does gender affect who gets searched during a stop ?
#### Q4) What is the mean stop_duration ?
#### Q5) Compare the age distributions for each violation.<br><br>


## The Commands That Are Used In This Project 

- `import pandas as pd` - To import Pandas library
- `pd.read_csv` - To import the CSV file in Jupyter notebook
- `head()` - It shows the first N rows in the data (by default, N=5)
- `df.isnull().sum()` - It detects the missing values from each column of the dataframe.
- `df.drop(‘Col_name’)` - To drop a column from dataframe.
- `value_counts` - In a column, it shows all the unique values with their count. It can be applied on a single column only.
- `df.groupby(‘Col_1’)[‘Col_2’] .sum()` - To create groups - Two Keys – Apply on Col_2 grouped by Col_1.
- `df['Column_name'].map({ old1:new1,old2:new2})` – Change all values of a column from old to new. Have to write for all values of column otherwise Nan will appear.
- `df['Column_name'].mean()` - To show Mean value of a column.
- `df.groupby('Column_1').Column_2.describe()` - To create groups based on Column1 and show statistics summary based on Column2.
<br><br>


## Conclusion

For Speeding Violation men are caught most.
This project provides an excellent opportunity for me as a beginners to gain Pandas knowledge to solve practical data problems. By working through these Python queries, I gain hands-on experience with data cleaning, filtering, date manipulation, and conditional logic.



