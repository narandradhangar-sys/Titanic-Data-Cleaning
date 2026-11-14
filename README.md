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

- # SWYNEX Internship – Task 2: Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the cleaned Titanic dataset from Task 1 using Python, Pandas, Matplotlib, and Seaborn.

The objective is to calculate important statistics, identify patterns and trends, detect anomalies, and visualize the data using charts.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Dataset
The cleaned Titanic dataset contains **891 rows and 12 columns**.

## Analysis Performed
1. Loaded the cleaned Titanic dataset.
2. Checked dataset shape and first few records.
3. Calculated statistical summaries.
4. Analyzed passenger survival rates.
5. Compared survival by gender and passenger class.
6. Studied age groups and embarkation ports.
7. Analyzed family size and ticket fare distribution.
8. Created charts and a correlation heatmap.

## Key Insights

### 1. Overall Survival
Approximately 38.4% of passengers survived, while around 61.6% did not survive.

### 2. Gender and Survival
Female passengers had a significantly higher survival rate than male passengers.

### 3. Passenger Class
First-class passengers had a higher survival rate than second-class and third-class passengers.

### 4. Age Group Analysis
Survival rates varied across age groups. Children generally had better survival chances than many adult groups.

### 5. Embarkation Port
Passengers boarding at Cherbourg (C) had a higher survival rate than passengers boarding at Southampton (S) and Queenstown (Q).

### 6. Fare Distribution
Ticket fares were unevenly distributed. Most passengers paid lower fares, while a few passengers paid very high fares.

### 7. Family Size
Survival rates varied according to family size, showing that family structure may have influenced survival chances.

## Visualizations
The following charts were created:

- Titanic Survival Count
- Survival Rate by Gender
- Survival Rate by Passenger Class
- Age Distribution
- Fare Distribution
- Survival Rate by Embarkation Port
- Correlation Heatmap

## Conclusion
Exploratory Data Analysis helped identify important patterns in the Titanic dataset. Gender, passenger class, age, embarkation port, and family size showed interesting relationships with passenger survival.

This task improved my understanding of data analysis, statistical summaries, data visualization, and extracting meaningful insights using Python.

## Files Included
- `cleaned_titanic.csv`
- `eda_analysis.ipynb`
- `chart1_survival_count.png`
- `chart2_gender_survival.png`
- `chart3_class_survival.png`
- `chart4_age_distribution.png`
- `chart5_fare_distribution.png`
- `chart6_embarked_survival.png`
- `chart7_correlation_heatmap.png`

## Internship
**Organization:** SWYNEX Technologies  
**Task:** Task 2 – Exploratory Data Analysis (EDA)  
**Status:** Completed

---

# Task 3 – Interactive Power BI Dashboard

## Project Overview
Created an interactive Titanic Survival Analysis Dashboard using Microsoft Power BI.

## Tools Used
- Microsoft Power BI
- DAX
- Power Query

## Key Performance Indicators (KPIs)
- Total Passengers: 891
- Total Survivors: 342
- Non-Survivors: 549
- Survival Rate: 38.38%

## Dashboard Visualizations
1. Gender-wise Survival Analysis
2. Passenger Class Survival Analysis
3. Age Group Survival Analysis
4. Embarked Port Survival Analysis

## Interactive Filters
- Gender
- Passenger Class
- Embarked Port
- Survival Status

## Key Findings
- Female passengers had higher survival rates than male passengers.
- First-class passengers had better survival chances than third-class passengers.
- Survival patterns varied across different age groups.

## Project Files
- Titanic_Survival_Analysis.pbix
- Titanic_Dashboard_Screenshot.png

## Conclusion
This dashboard provides interactive insights into Titanic passenger survival using data visualization and business intelligence techniques.
