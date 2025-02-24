# Netflix Data Analysis | Project

![Netflix Image](https://github.com/user-attachments/assets/dacfc831-01d4-42a7-b09c-160af918ca55)


## Project Overview
This project explores Netflix’s content catalog to analyze trends in genres, movie vs. TV show distribution, content ratings, and regional preferences. The goal is to gain insights into content diversity, popularity, and Netflix’s evolving strategy over time.


## Objectives
- Analyze the distribution of movies vs. TV shows on Netflix.
- Explore regional content preferences
- Study ratings and Predict the success of a Netflix title based on past trends.
- Learn how to use Python for data analysis tasks such as aggregation, filtering, and ranking.
- Understand how to calculate and manipulate data in a real-world dataset.
- Analyze population distribution across states and districts.


## Project Level: Beginner
This project is a beginners level project.To get me familiar with the basics of Pandas and to gain knowledge on how to handle real-world data analysis problems. I have worked with a small dataset and had used Pandas library to solve different tasks that are commonly encountered in data analytics.


## Dataset
The data for this project is sourced from the Kaggle dataset:
 - **Dataset Link**: [Netflix Data](https://www.kaggle.com/datasets/imtkaggleteam/netflix)<br><br>



## SQL Problems and Questions
Here are the SQL problems that I have solved as part of this project:

#### Q1) For 'House of Cards', what is the Show Id and Who is the Director of this show ?
#### Q2) In which year the highest number of the TV Shows & Movies were released ? Show with Bar Graph.
#### Q3) How many Movies & TV Shows are in the dataset ? Show with Bar Graph.
#### Q4) Show all the Movies that were released in year 2000.
#### Q5) Show only the Titles of all TV Shows that were released in India only.
#### Q6) Show Top 10 Directors, who gave the highest number of TV Shows & Movies to Netflix ?
#### Q7) Show all the Records, where "Category is Movie and Type is Comedies" or "Country is United Kingdom".
#### Q8) In how many movies/shows, Tom Cruise was cast ?
#### Q9) What are the different Ratings defined by Netflix ?
#### Q9A) How many Movies got the 'TV-14' rating, in Canada ?
#### Q9B) How many TV Shows got the 'R' rating, after year 2018 ?
#### Q10) What is the maximum duration of a Movie/Show on Netflix ?
#### Q11) Which individual country has the Highest No. of TV Shows ?
#### Q12) How can we sort the dataset by Year ?
#### Q13) Find all the instances where: Category is 'Movie' and Type is 'Dramas' or Category is 'TV Show' & Type is 'Kids' TV'.<br><br>


## The Commands That Are Used In This Project 

- `import pandas as pd` - To import Pandas library<br>
- `pd.read_csv` - To import the CSV file in Jupyter notebook<br>
- `head()` - It shows the first N rows in the data (by default, N=5)<br>
- `shape` - It shows the total no. of rows and no. of columns of the dataframe<br>
- `info()` - To show indexes, columns, data-types of each column, memory at once.
- `value_counts` - In a column, it shows all the unique values with their count. It can be applied on a single column only.
- `unique()` - It shows the all unique values of the series.
- `duplicated()` - To check row wise and detect the Duplicate rows.
- `isnull()` - To show where Null value is present.
- `dropna()` - It drops the rows that contains all missing values.
- `str.contains()` - To get all records that contains a given string.
- `str.split()` - It splits a column's string into different columns.
- `to_datetime()` - Converts the data-type of Date-Time Column into datetime[ns] datatype.
- `dt.year.value_counts()` - It counts the occurrence of all individual years in Time column.
- `groupby()` - Groupby is used to split the data into groups based on some criteria.
- `df.plot()` - To show the count of all unique values of any column in the form of bar graph.
- `max(), min()` - It shows the maximum/minimum value of the series.
- `mean()` - It shows the mean value of the series.
- `df[df.Col_1 = = ‘Element1’]` - Filtering – We are accessing all records with Element1 only of Col_1.
<br><br>


## Conclusion
This project provides an excellent opportunity for me as a beginners to gain Pandas knowledge to solve practical data problems. By working through these Python queries, I gain hands-on experience with data cleaning, filtering, date manipulation, and conditional logic.


