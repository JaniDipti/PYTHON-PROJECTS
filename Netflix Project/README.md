Project Name :- 🎬 Netflix Data Analysis 

This project uses a real Netflix dataset to perform Data Analysis using Python. 
The goal is to answer key business questions using popular Python libraries such as pandas, matplotlib, and seaborn.
This is a perfect beginner project for those starting out in Data Analytics with Python.

📌 Project Overview
In this project:-
Cleaned and explored the Netflix dataset
Answered real-world questions using Python code
Created visualizations to better understand trends
Learned how to manipulate and analyze time, text, and categorical data

--  Libraries and Commands Used --
head(), tail(), shape, size, columns, dtypes, info()
value_counts(), unique(), nunique(), duplicated(), isnull(), dropna()
isin(), str.contains(), str.split(), to_datetime(), groupby()

Time Series & Filtering
df['Date'].dt.year, dt.year.value_counts(), Filtering with AND / OR

Seaborn & Matplotlib for Visualization
sns.countplot(), plt.show()

✅ Key Tasks 
Data Cleaning

Task 1: Check and remove duplicate records
Task 2: Check for null values and visualize them with a heatmap

🔍 Analysis & Business Questions

Get the Show ID and Director of House of Cards
In which year were the most Movies/TV Shows released? (Bar Graph)
Count of Movies vs. TV Shows (Bar Graph)
All Movies from the year 2000
Titles of TV Shows released only in India
Top 10 Directors by number of Netflix titles

Records where:
Category is Movie and Type is Comedies, OR
Country is United Kingdom
How many Movies/Shows starred Tom Cruise?
What are the different Ratings used by Netflix?
9.1: How many Movies got a 'TV-14' rating in Canada?
9.2: How many TV Shows got an 'R' rating after 2018?
What is the maximum duration of a Movie/Show?
Which country has the most TV Shows?
How to sort the dataset by Year?
Find all records where:
Category is Movie and Type is Dramas
OR Category is TV Show and Type is Kids' TV

📁 Files Included

NetFlix Data.ipynb — Main Jupyter Notebook
netflix_dataset.csv — Cleaned Netflix dataset
README.md — Project overview and instructions

▶️ How to Run This Project
Clone the repository or download the ZIP

Install required Python libraries:
pip install pandas matplotlib seaborn

Run the Jupyter Notebook:
jupyter notebook NetFlix Data.ipynb

Project Summary:

Basic data cleaning and handling
Working with strings, dates, filters, and conditions
Visualization with Seaborn
Answering real business questions with data




