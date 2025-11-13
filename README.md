# Data-Cleaning-and-Preprocessing
Cleaned and preprocessed the Mall Customers dataset using Python (Pandas) — handled missing values, duplicates, standardized data, and created visual insights.

# Task 1: Data Cleaning and Preprocessing

## Objective
The main goal of this task is to clean and prepare a raw dataset by handling missing values, duplicates, inconsistent formats, and incorrect data types.  
Dataset used: Mall Customers Segmentation Data (from Kaggle)

## Tools Used
- Python (Pandas)
- Google Colab

## Steps Performed
1. Checked for missing values using `.isnull()` and removed them.
2. Removed duplicate records using `.drop_duplicates()`.
3. Standardized text values (for example, made gender values consistent).
4. Renamed column headers to lowercase and replaced spaces with underscores.
5. Converted date formats to `dd-mm-yyyy` for consistency.
6. Checked and corrected data types (age as int, date as datetime).
7. Removed outliers and verified numeric distributions.
8. Created a clean, final dataset ready for analysis.

## Before and After Summary
| Description | Before Cleaning | After Cleaning |
|--------------|-----------------|----------------|
| Total Rows | 200 | 197 |
| Missing Values | Present | None |
| Duplicates | Present | Removed |
| Column Names | Inconsistent | Cleaned and uniform |

## Output Files
- `Mall_Customers.csv` – Original raw dataset  
- `Mall_Customers_cleaned.csv` – Final cleaned dataset  
- `data_cleaning.ipynb` – Python notebook with all code  
- `README.md` – Documentation file

## Summary of Changes
The dataset was cleaned by handling missing and duplicate values, standardizing formats, correcting data types, and renaming columns for better readability.  
After cleaning, the dataset is ready for analysis or visualization.

## Author
Smruti S Nair  

