# Sentiment Data Cleaning and Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing a social media sentiment dataset using Python and Pandas. The objective was to identify and address data quality issues, ensuring the dataset is accurate, consistent, and ready for further analysis.

This project was completed as part of the Data Analytics Internship Program at Codveda Technologies.

## Dataset Information

* Dataset: Sentiment Dataset
* Total Records: 732
* Total Features: 15

## Objectives

* Load the dataset using Pandas
* Identify and check for missing values
* Detect duplicate records
* Remove unnecessary columns
* Standardize inconsistent data formats
* Convert timestamp data into datetime format
* Export a cleaned dataset for analysis

## Tools and Technologies

* Python
* Pandas
* Jupyter Notebook

## Data Cleaning Process

### 1. Data Loading

The dataset was loaded into a Pandas DataFrame for inspection and preprocessing.

### 2. Missing Value Analysis

All columns were checked for missing values using Pandas functions.

**Result:** No missing values were found.

### 3. Duplicate Record Analysis

The dataset was examined for duplicate rows.

**Result:** No duplicate records were found.

### 4. Removing Unnecessary Columns

The following unnecessary index columns were removed:

* Unnamed: 0
* Unnamed: 0.1

### 5. Standardizing Text Fields

Leading and trailing spaces were removed from categorical columns to ensure consistency.

Columns cleaned:

* User
* Platform
* Country
* Sentiment

### 6. Datetime Conversion

The Timestamp column was converted from object format to datetime format for improved usability and analysis.

### 7. Exporting Cleaned Data

The cleaned dataset was exported in CSV and Excel formats.

## Results

* Missing Values Found: 0
* Duplicate Records Found: 0
* Unnecessary Columns Removed: 2
* Timestamp Converted Successfully
* Text Fields Standardized
* Cleaned Dataset Generated Successfully

## Project Files

* Sentiment_Data_Cleaning.ipynb
* cleaned_sentiment_dataset.csv
* cleaned_sentiment_dataset.xlsx

## Conclusion

The dataset was successfully cleaned and preprocessed using Python and Pandas. Data quality checks confirmed that there were no missing values or duplicate records. Formatting inconsistencies were resolved by removing unnecessary columns, standardizing text fields, and converting timestamps to datetime format. The cleaned dataset is now ready for exploratory data analysis, visualization, and machine learning applications.

## Author

Adewale Lateef

Data Analytics Intern
