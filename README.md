# Film-Analysis
Developed an analytical approach to define required data and processes for film performance evaluation
Project Summary
This project analyzes movie performance using SQL by exploring a dataset containing movie information such as genre, release year, ratings, budget, and box office revenue. The project focuses on cleaning the data, performing exploratory analysis, and generating business insights to understand the factors related to movie success. The results can support data-driven decisions for film production and marketing strategies.
________________________________________
Narration
The objective of this project is to analyze movie performance using SQL and transform raw movie data into meaningful insights. The analysis focuses on identifying trends in ratings, revenue, and genres to better understand audience preferences and overall film performance.
________________________________________
Data Understanding
The dataset contains information about movies, including:
•	Movie title
•	Genre
•	Release year
•	IMDb rating
•	Budget
•	Box office revenue
•	Runtime
•	Production company
The dataset was reviewed to understand its structure, data types, and overall quality before analysis.
________________________________________
Data Exploration
SQL queries were used to explore the dataset by:
•	Counting the total number of movies
•	Finding average movie ratings using AVG()
•	Calculating total box office revenue using SUM()
•	Identifying the highest and lowest rated movies
•	Comparing movie performance by genre and release year using GROUP BY
•	Ranking top-performing movies based on ratings and revenue
•	Detecting trends across different movie categories
________________________________________
Data Preparation
Data cleaning was performed using SQL to improve data quality by:
•	Identifying and removing duplicate records
•	Checking and handling missing values
•	Standardizing text formatting
•	Validating numeric values
•	Filtering invalid or inconsistent records
•	Preparing clean tables for analysis
________________________________________
Analysis & SQL Techniques
The project applies common SQL operations, including:
•	SELECT
•	WHERE
•	ORDER BY
•	GROUP BY
•	HAVING
•	COUNT()
•	AVG()
•	SUM()
•	MIN() and MAX()
•	CASE WHEN
•	JOIN
•	DISTINCT
•	Common Table Expressions (CTE)
•	Window Functions (RANK(), DENSE_RANK(), ROW_NUMBER())
________________________________________
Evaluation
The analysis results were validated by comparing summary statistics and aggregated values across different categories. SQL queries were reviewed to ensure consistent and accurate outputs, providing reliable insights into movie performance.
________________________________________
Recommendations
Based on the analysis:
•	Focus on genres that consistently generate higher box office revenue.
•	Identify characteristics of highly rated movies for future productions.
•	Analyze release year trends to support production planning.
•	Monitor audience ratings alongside revenue to evaluate overall movie success.
•	Use historical performance data to support marketing and investment decisions.
________________________________________
Tools
•	SQL (MySQL / PostgreSQL)
•	SQL Workbench
•	Git & GitHub
________________________________________
Skills Demonstrated
•	SQL Query Writing
•	Data Cleaning
•	Exploratory Data Analysis (EDA)
•	Aggregate Functions
•	Joins
•	Window Functions
•	Data Validation
•	Business Insight Generation
•	Data-Driven Decision Making
Business Insights
•	Movies with higher audience ratings generally achieved better box office performance, although some high-budget films generated strong revenue despite receiving moderate ratings.
•	Drama and Action were among the most common genres, while Action and Adventure movies contributed the highest average box office revenue.
•	Several genres consistently received higher average ratings, indicating stronger audience satisfaction.
•	Recent release years showed an increase in both the number of movies produced and total box office revenue.
•	A small number of blockbuster movies contributed a significant portion of the total revenue, suggesting that revenue distribution is highly concentrated.
•	Duplicate and incomplete records were identified during data cleaning, highlighting the importance of data quality before performing analysis.
•	SQL aggregation revealed clear differences in average ratings and revenue across genres, supporting more targeted production and marketing decisions.
