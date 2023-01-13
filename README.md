# job_search_project
Going over data science job descriptions and analyzing. Specific to Estonia.
# Project Overview
Created a tool that analysed all the job offers available in LinkedIn for Tallinn, Estonia on 01.01.2023 for Data Scientist and Data Analyst.
Scraped 24 jobs manualy.
Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.


# Code and Resources Used
Python Version: 3.7
Packages: pandas, numpy, sklearn, matplotlib, seaborn
Kaggle examples.

With each job, we got the following:

Job title
Job Description
Company name
Employee count
Type of work
Remote
Seniority


# Data Cleaning
After scraping the data, I needed to clean it up so that it was usable for our analysis. I made the following changes and created the following variables:

Droped the remote column as it was almos empty
Parsed job titel out of job titel
Made columns for if different skills were listed in the job description:
Python
R
Excel
AWS
Spark
Column for description length

# EDA
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables.

![Company size count](https://user-images.githubusercontent.com/70900293/212374509-5da62a49-cf41-4a06-a2b1-19be603d432b.png)


![job industry count](https://user-images.githubusercontent.com/70900293/212374512-d066a7f0-93f0-404f-bbe4-79544d2890ee.png)


![job title count](https://user-images.githubusercontent.com/70900293/212374514-b5b5eea2-1088-4915-ba57-e9a7e796762b.png)
