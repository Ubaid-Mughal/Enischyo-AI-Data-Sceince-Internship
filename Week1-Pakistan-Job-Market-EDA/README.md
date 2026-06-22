Week 1 : Pakistan Job Market EDA
Objective: Explore a real Pakistan dataset to understand its structure, quality issues and extract insights through code.
Dataset: Pakistan Job Market Intelligence Dataset
Source: https://www.kaggle.com/datasets/aamir28/pakistan-job-market-intelligence-dataset
Rows: 10500, Columns: 13, Time Period: May 2024 to May 2025
Key Steps Completed
Loaded dataset and ran shape, dtypes, info, describe and value counts. Calculated missing value percentages per column. Detected outliers in Number of Vacancies using IQR method. Identified city name spelling errors as data entry issues. Flagged redundant and problematic columns.
8 Questions Answered
Which city has the most job postings : Karachi. Which sector has the most postings : IT and Technology. What percentage of jobs are remote : 16.8 percent. Which sector has most vacancies on average : Construction and Real Estate. Most required education level : Bachelors. Which sector pays highest : found via salary average calculation. Percentage of jobs preferring male candidates : calculated. Which city has highest average salary : Islamabad.
Data Quality Issues Found
City column has spelling inconsistencies. Salary Range is a string not a number. 3 percent of salary values are missing. Application Deadline column is redundant. Required Skills needs splitting for proper analysis.
