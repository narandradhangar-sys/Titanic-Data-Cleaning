# Titanic Dataset Cleaning Project

## Project Overview
This project is about cleaning the Titanic passenger dataset using Python and Pandas.

## Dataset Information
- Dataset Name: Titanic Dataset
- Total Rows: 891
- Total Columns: 12
- Dataset Source: Kaggle

## Problems Identified
- Missing Age values: 177
- Missing Cabin values: 687
- Missing Embarked values: 2
- Duplicate Records: 0

## Data Cleaning Steps
1. Removed duplicate records.
2. Removed extra spaces from text values.
3. Standardized Sex and Embarked columns.
4. Converted Age and Fare into numeric data types.
5. Filled missing Age values using median.
6. Filled missing Embarked values using mode.
7. Replaced missing Cabin values with "Unknown".

## Tools Used
- Python
- Pandas
- Google Colab

## Final Results
- Total Records: 891
- Missing Values After Cleaning: 0
- Duplicate Records After Cleaning: 0

## Conclusion
The Titanic dataset was successfully cleaned using Python and Pandas. All missing values were handled, duplicate records were checked, and text values were standardized.

## Project Files
- cleaned_titanic.csv
- README.md
