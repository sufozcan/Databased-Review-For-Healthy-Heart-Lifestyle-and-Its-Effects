# Databased Review for Healthy Heart: Lifestyle and Its Effects
This project analyzes the relationship between lifestyle habits (smoking, exercise, physical activity) and heart health indicators (BMI, cholesterol, blood pressure) using Python.

## Project Overview
The study examines a dataset of 150 individuals to identify correlations between daily routines and the risk of heart disease. The primary focus was on how individual habits contribute to or mitigate cardiovascular risks.

## Tools & Libraries
Python: Core programming language.

Pandas & NumPy: Extensive use for data tidying, handling missing values (NaN), and numerical transformations.

Matplotlib & Seaborn: Used to create insightful visualizations such as violin plots, stacked bar charts, and scatter plots.


## Data Cleaning & Tidying (The Core Effort)
A significant portion of this project involved transforming a "dirty" dataset into a reliable source for analysis:

String Formatting: Standardized inconsistent categorical values (e.g., Gender, Smoking Status) and removed unnecessary whitespaces.

Numerical Formatting: Converted data types, handled negative values by taking absolute values, and corrected decimal separators.

Missing Value Imputation: Handled NaN values using statistical measures (mean, mode) based on the distribution of each variable.

Outlier Detection: Identified and managed outliers in sections like "Exercise Duration" using quantile analysis.

## Key Research Findings

BMI & Glucose vs. Heart Disease: A strong positive association was found; individuals with a BMI > 28 and Glucose > 125 mg/dL almost universally showed signs of heart disease.


Smoking & Blood Pressure: Smokers constituted a significantly higher percentage (15.9% more) of the "High Blood Pressure" group compared to non-smokers.


Gender & Family History: While heart disease is common in males, family history has a more drastic impact on females—increasing their risk by approximately 20 times.


Physical Activity: High levels of physical activity clearly correlate with lower, more ideal BMI values (median BMI of ~25).
