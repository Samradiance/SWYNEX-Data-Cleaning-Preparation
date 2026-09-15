SWYNEX -Data Cleaning and Preparation

# Overview:
This project was completed as part of Task 1 of my internship with SWYNex Technologies. The objective of this  task was to clean and prepare a public dataset for further analysis.

# Dataset:
The dataset used in this project is a music dataset containing information about tracks, artists, albums, geners, release dates, popularity and audio features. 
The dataset contains 50,000 records and 33 columns.

# Data cleaning Performed:
The following steps were performed using Python and Pandas:
  1. Checked the dataset structure and data types.
  2. Checked for missing values.
  3. Checked for duplicate values.
  4. Checked numerical values for consistency.
  5. Converted the 'release_data' column from string type to datetime format.
  6. Removed duplicate records using Pandas.
  7. Saved the cleaned dataset as a new CSV file.

# Data Quality Findings:
  - No missing values were found.
  - No duplicates record were found.
  - The 'release_date' columns was identified as an incorrect data type and was converted to datetime.
  - Numerical columnsd were checked for reasonable value ranges.
  - No major inconsistent values were found.

# Tools Used:
  - Python
  - Pandas
  - GitHub

# Files:
  - 'music_dataset.csv' (Oringinal Dataset)
  - 'cleaned_music_dataset.csv' (Cleaned Dataset)
  - 'data_cleaning.py' (Python code used for data cleaning

# Conclusion:
The dataset was successfully inspected, cleaned, and prepared for further analysis. This task provided practical experience in data cleaning, data validation, and handling data types using Python and Pandas
