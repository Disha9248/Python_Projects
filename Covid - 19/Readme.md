# Covid - 19 Data Analysis | Project

![Covid 19 Image](https://github.com/user-attachments/assets/c3ec5f9c-c266-4fcc-b503-db9519b25568)


## Project Overview
This project aims to analyze COVID-19 data to understand case trends, recovery rates, mortality rates and the impact of the pandemic on different regions. The analysis will help identify patterns and insights for better decision-making in public health and policy.


## Objectives
- Learn how to use Python for data analysis tasks such as aggregation, filtering, and ranking.
- Analyze recovery and fatality rates across regions.
- Understand how to calculate and manipulate data in a real-world dataset.
- Track the rise and decline of COVID-19 cases.
- Develop skills for performance analysis using Pandas by solving different types of data problems related to user performance.


## Project Level: Beginner
This project is a beginners level project.To get me familiar with the basics of Pandas and to gain knowledge on how to handle real-world data analysis problems. I have worked with a small dataset and had used Pandas library to solve different tasks that are commonly encountered in data analytics.


## Dataset
The data for this project is sourced from the Kaggle dataset:
 - **Dataset Link** : [Covid -19 Dataset](https://www.kaggle.com/datasets/niteshsahu99/cars-data1/data)


## Dataset Columns
Dataset contains total 6 columns namely :
- Date
- State
- Region
- Confirmed
- Deaths
- Recovered
  

### SQL Problems and Questions
Here are the SQL problems that I have solved as part of this project:

#### Q1) Show the number of Confirmed, Deaths and Recovered cases in each Region.
#### Q2) Remove all the records where the Confirmed Cases is Less Than 10.
#### Q3) In which Region, maximum number of Confirmed cases were recorded ?
#### Q4) In which Region, minimum number of Deaths cases were recorded ?
#### Q5) How many Confirmed, Deaths & Recovered cases were reported from India till 29 April 2020 ?
#### Q6-A ) Sort the entire data wrt No. of Confirmed cases in ascending order.
#### Q6-B ) Sort the entire data wrt No. of Recovered cases in descending order.


## The Commands That Are Used In This Project 

- `import pandas as pd` - To import Pandas library<br>
- `pd.read_csv` - To import the CSV file in Jupyter notebook<br>
- `df.count()` - It counts the no. of non-null values of each column.
- `df.isnull().sum()` - It detects the missing values from the dataframe.
- `head()` - It shows the first N rows in the data (by default, N=5)<br>
- `df.groupby(‘Col_name’)` - To form groups of all unique values of the column.
- `df.sort_values(by= ['Col_name'])` - Sort the entire dataframe by the values of the given column.     
- `df[df.Col_1 = = ‘Element1’]` - Filtering – We are accessing all records with Element1 only of Col_1.


## Conclusion
This project provides an excellent opportunity for me as a beginners to gain Pandas knowledge to solve practical data problems. By working through these Python queries, I gain hands-on experience with data cleaning, filtering, date manipulation, and conditional logic.

The COVID-19 data analysis provides critical insights into the spread and impact of the pandemic across different regions. Key findings include:

Regional Impact: Identified the number of confirmed, death, and recovered cases in each region, highlighting areas most affected by COVID-19.<br>
Data Cleaning: Removed records with confirmed cases less than 10 to ensure meaningful analysis.<br>
Worst & Least Affected Regions: Determined the region with the highest confirmed cases and the region with the lowest number of deaths.<br>
India-Specific Analysis: Extracted COVID-19 statistics for India up to April 29, 2020, providing a snapshot of the situation during that period.<br>
Data Sorting & Organization: Sorted data based on confirmed cases (ascending order) and recovered cases (descending order) to analyze trends effectively.<br>
This analysis helps in understanding the pandemic's impact on different regions, aiding policymakers and healthcare professionals in making informed decisions.

