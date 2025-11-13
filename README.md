Task 1 – Data Cleaning & Preprocessing
Data Analyst Internship
✅ Overview

In this task, I performed basic data cleaning on the Netflix Movies and TV Shows dataset.
The aim was to make the raw data clean, consistent, and ready for analysis.

🧹 What I Did (Simple Explanation)
1️⃣ Loaded the Dataset

Opened the Netflix dataset to understand its structure and contents.

2️⃣ Checked for Missing Values

Identified columns that had empty or missing information
(e.g., director, cast, country, date added).

3️⃣ Filled Missing Data

Replaced missing directors with "Unknown"

Replaced missing cast with "Not available"

Filled missing country values with the most common country in the dataset

Removed rows that had no date_added value since date is important

4️⃣ Removed Duplicate Records

This helps avoid repeated data and ensures accurate analysis.

5️⃣ Cleaned and Standardized Text

Converted text to lowercase or uppercase where needed

Removed unwanted spaces

Made column names simple, clean, and consistent (no spaces)

6️⃣ Converted Date Format

Changed date_added into a proper date format and created:

year_added

month_added

So it becomes easier to analyze trends.

7️⃣ Saved the Cleaned Dataset

Exported the final cleaned file as:

netflix_titles_cleaned.csv

📁 Files Included

Raw dataset (netflix_titles.csv)

Cleaned dataset (netflix_titles_cleaned.csv)

Jupyter Notebook

README file

📘 What I Learned

How to identify and handle missing values

How to remove duplicate records

How to standardize text fields

How to clean date formats

Importance of data cleaning in real-world analysis