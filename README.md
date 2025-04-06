"# AlmaBetter_M2_Paisabazaar-Banking-Fraud-Analysis-EDA" 

# Paisabazaar Banking Fraud Analysis

This project performs Exploratory Data Analysis (EDA) to investigate potential fraud patterns in banking and financial data. The goal is to identify key factors and behaviors that may indicate fraudulent activity, ultimately helping to improve fraud detection strategies.

## Project Description

This EDA project analyzes customer demographics, financial behavior, and transactional patterns to uncover insights related to banking fraud. The analysis includes:

* Data cleaning and preprocessing
* Univariate, bivariate, and multivariate analysis
* Data visualization using Matplotlib, Seaborn, and Plotly
* Identification of potential fraud indicators

## Dataset

The dataset used in this project contains customer information such as:

* Customer demographics (age, occupation, income)
* Financial behavior (credit utilization, outstanding debt, monthly balance)
* Transactional patterns (payment behavior, delayed payments, credit inquiries)
* Credit-related information (number of loans, credit cards, credit score)


1.   Main Dataset: dataset.csv

    This is the initial dataset loaded into the project.

    It contains a variety of customer and banking-related features.

    The features include:
        Customer demographics (age, occupation, income)
        Financial behavior (credit utilization, outstanding debt, monthly balance)
        Transactional patterns (payment behavior, number of delayed payments, and credit inquiries)
        Key variables like the number of loans, credit cards, and credit score   

2.   Processed Dataset: processed_paisabazaar_dataset.csv

    This dataset is created after cleaning and preprocessing the initial dataset.csv.

    The cleaning process involves:
        Handling missing values (specifically in the "Type_of_Loan" column)
        Correcting inconsistencies in the "Type_of_Loan" column (e.g., standardizing delimiters, removing duplicates, and "Not Specified" entries)   

This processed dataset is saved as a new CSV file.  

3.   Cleaned Dataset: cleaned_featured_data1.csv

    This dataset is created later in the analysis, specifically for correlation analysis and potentially for modeling.

    It's derived from data1 (which itself is based on processed_paisabazaar_dataset.csv).

   In summary:

    dataset.csv is the raw input.

    processed_paisabazaar_dataset.csv is a cleaned version, mainly focused on refining the "Type_of_Loan" column.

    cleaned_featured_data1.csv is a further processed version, transformed to be suitable for numerical analysis and modeling

## Key Objectives

* Identify factors affecting customer credit scores.
* Detect behavioral patterns indicative of fraud.
* Analyze relationships between demographics and financial health.
* Provide insights for fraud detection improvement.

## Files Included

* \[Notebook/Script Name]: (e.g., `Paisabazaar_Banking_Fraud_Analysis_EDA_Submission.ipynb`) - Contains the Python code for the EDA.
* `README.md`: This file.
*  `dataset.zip`: This Zip file contains all the three datasets, main dataset and the dataset on which perfromed EDA also. can download it and have a look on datasets.


## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scipy


## Author

* \[Vishesh Alag]

