# Census Data Analysis | Project

![Census Image](https://github.com/user-attachments/assets/fd28b693-3e1d-47de-b77a-340fd4ef6a32)


## Project Overview
This project aims to analyze India’s census data to uncover trends in population growth, literacy, employment, urbanization, and socio-economic factors. The insights can help in policymaking, resource allocation, and understanding demographic patterns.


## Objectives
- Learn how to use Python for data analysis tasks such as aggregation, filtering, and ranking.
- Understand how to calculate and manipulate data in a real-world dataset.
- Analyze population distribution across states and districts.


## Project Level: Beginner
This project is a beginners level project.To get me familiar with the basics of Pandas and to gain knowledge on how to handle real-world data analysis problems. I have worked with a small dataset and had used Pandas library to solve different tasks that are commonly encountered in data analytics.


## Dataset
The data for this project is sourced from the Kaggle dataset:
 - **Dataset Link**: [India Census 2011](https://www.kaggle.com/datasets/niteshsahu99/india-census-2011)<br><br>




## SQL Problems and Questions
Here are the SQL problems that I have solved as part of this project:

#### Q1) How will you hide the indexes of the dataframe.
#### Q2) How can we set the caption / heading on the dataframe.
#### Q3) Show the records related with the districts - New Delhi , Lucknow , Jaipur.
#### Q4) Calculate state-wise :
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A. Total number of population.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B. Total no. of the population with different religions.
#### Q5) How many Male Workers were there in Maharashtra state ?
#### Q6) How to set a column as index of the dataframe ?
#### Q7a) Add a Suffix to the column names.
#### Q7b) Add a Prefix to the column names.<br><br>


## The Commands That Are Used In This Project 

- `import pandas as pd` - To import Pandas library<br>
- `pd.read_csv` - To import the CSV file in Jupyter notebook<br>
- `head()` - It shows the first N rows in the data (by default, N=5)<br>
- `shape` - It shows the total no. of rows and no. of columns of the dataframe<br>
- `info()` - To show full information about the dataset.
- `style.hide_index()` - To hide the index of the dataframe.
- `style.set_caption` - To give a caption to the dataframe.
- `isin()` - To show all records including particular elements.
- `groupby(‘Col_1’)[‘Col_2’] .sum()[‘value’]` - GroupBy Two Keys.
- `df[df.Col_1 == 'Element1']['Col_2']` - Filter the records of the dataframe wrt to Element1 of Col1 and then showing results of Col2 only.
- `set_index( ‘Col_Name’ )` - To set any column of a DF as an index.
- `add_prefix(‘value_’)` - To add prefix to the column name.
- `add_suffix(‘_value’)` - To add suffix to the column name.<br><br>


## Conclusion
This project provides an excellent opportunity for me as a beginners to gain Pandas knowledge to solve practical data problems. By working through these Python queries, I gain hands-on experience with data cleaning, filtering, date manipulation, and conditional logic.
The census data analysis provides valuable insights into India's demographic distribution and workforce statistics. Key takeaways from the analysis include:

Data Handling Techniques: Explored methods to hide indexes, set captions, and modify column names for better readability.
Filtering and Querying Data: Retrieved district-specific records for states demonstrating effective data extraction techniques.
State-wise Analysis: Computed total population and religious demographics for each state, offering a broad perspective on population diversity.
DataFrame Customization: Learned techniques to set a column as an index and add prefixes/suffixes to column names for improved data organization.

