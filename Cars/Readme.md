# Cars Analysis | Data Cleaning Project

![Car Image](https://github.com/user-attachments/assets/f83f11a8-251f-49eb-9d96-930cfc589fd4)

## Project Overview
The project demonstrates the use of Pandas to analyze data of cars. This type of analysis can help understand key factors that influence car prices and customer preferences,price trends, fuel efficiency, brand comparisons, and performance metrics to improve business.


## Objectives
- Learn how to use Python for data analysis tasks such as aggregation, filtering, and ranking.
- Understand how to calculate and manipulate data in a real-world dataset.
- Develop skills for performance analysis using Pandas by solving different types of data problems related to user performance.

## Project Level: Beginner
This project is a beginners level project.To get me familiar with the basics of Pandas and to gain knowledge on how to handle real-world data analysis problems. I have worked with a small dataset and had used Pandas library to solve different tasks that are commonly encountered in data analytics.

## Dataset
The data for this project is sourced from the Kaggle dataset:
 - **Dataset Link**: [Cars Dataset](https://www.kaggle.com/datasets/niteshsahu99/cars-data1/data)

## Dataset Columns
Dataset contains total 15 columns namely :
- Make
- Model
- Type
- Origin
- Drive Train
- MSRP
- Invoice
- Engine Size
- Cylinders
- Horsepowers
- MPG_City
- MPG_Highway
- Weight
- Wheelbase
- Length

### SQL Problems and Questions
Here are the SQL problems that I have solved as part of this project:

#### Q1) For Data Cleaning - <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Find all Null Values in the dataset. If there is any null value in any column, then fill it with the mean of that column.<br>
#### Q2) Based on Value Counts - <br>
         Check what are the different types of Make are there in our dataset.what is the count (occurrence) of each Make in the data?
#### Q3) Filtering - <br>
         Show all the records where Origin is Asia or Europe.
#### Q4) Removing unwanted records - <br>
         Remove all the records (rows) where Weight is above 4000.
#### Q5) Applying function on a column - <br>
         Increase all the values of 'MPG_City' column by 3.


## The Commands That We Used In This Project 

`import pandas as pd` - To import Pandas library<br>
`pd.read_csv` - To import the CSV file in Jupyter notebook<br>
`head()` - It shows the first N rows in the data (by default, N=5)<br>
`shape` - It shows the total no. of rows and no. of columns of the dataframe<br>
`df.isnull().sum()` - It detects the missing values from each column of the dataframe.<br>
`fillna()` - To fill the null values of a column with some particular value<br>
`value_counts` - In a column, it shows all the unique values with their count. It can be applied to a single column only.<br>


## Conclusion
This project provides an excellent opportunity for me as a beginners to gain Pandas knowledge to solve practical data problems. By working through these Python queries, I gain hands-on experience with data cleaning, filtering, date manipulation, and conditional logic.

