# Shopping-Customer-Analysis

### Summary and Recommendations

#### 1. Overview

This project focuses on cleaning and exploring a raw customer dataset using Pandas for data manipulation and Matplotlib/Seaborn for data visualization. The dataset initially contained missing values, inconsistent formatting, and outliers. The goal of this project is to clean the data by handling missing values, standardizing formats, and removing duplicates to create a clean dataset for further analysis.

#### 2. Data

The dataset contains information on customer demographics, purchase behavior, and transaction details. Key columns include:

 - Age: Customer's age
 - Purchase Amount (USD): Total amount spent
 - Item Purchased: The product the customer bought
 - Frequency of Purchases: How often the customer makes purchases (cleaned and standardized)
 - Review Rating: Customer's rating for the purchase
 - Previous Purchases: Total number of purchases made by the customer before the current transaction

#### 3. Data Cleaning Steps

- Handling Missing Values: Non-numeric values in the Frequency of Purchases column were converted to numeric, and missing values were imputed with the column mean.
- Outlier Detection and Correction: Outliers in the Age and Purchase Amount (USD) columns were identified using z-scores and corrected by replacing them with the column mean to ensure a more accurate dataset.
- Standardizing Data: The Gender and Item Purchased columns were cleaned by converting values to lowercase and correcting common spelling mistakes.
- Removing Duplicates: Duplicate records were removed to ensure unique and accurate entries.

#### 4. Exploratory Data Analysis (EDA)

Data Distribution: Histograms were generated to visualize the distribution of key numerical columns, such as Age, Purchase Amount (USD), and Review Rating. The data reveals that most customers are within the middle age range, and purchase amounts are centered around common price points.

Correlation Analysis: A heatmap shows the correlations between numerical variables. For example, there may be a correlation between Purchase Amount and Review Rating or Previous Purchases.

Item Popularity: The most purchased items include blouses, sweaters, jeans, and shoes, as shown by the frequency distribution. These items were the most popular across the dataset. The average purchase amount for each item was also analyzed, with certain high-end items showing significantly higher average prices.

#### 5. Data Visualization

- Histograms of numerical columns
- Correlation heatmap for numerical variables
- Count plots for categorical columns like Gender, Item Purchased, Category
- Bar plots for the most purchased items and the average purchase amount for each item.

#### 7. Key Findings
      
Handling Missing Values: Non-numeric values were found in the Frequency of Purchases column. These values (e.g., "Fortnightly", "Annually") were replaced with the mean value of the column after converting them to numeric data, ensuring consistent numerical analysis. Missing values in the dataset were handled by imputing them with the mean for numeric columns and correcting categorical data.

Outliers in Age and Purchase Amount: Outliers in the Age and Purchase Amount (USD) columns were identified and corrected. These outliers were likely due to data entry errors or extreme values that would distort the overall analysis. By replacing them with the column mean, the dataset was normalized for more accurate insights.

Data Standardization: Spelling mistakes and inconsistent formatting were identified and corrected in the Gender and Item Purchased columns. This step helped standardize the dataset, ensuring consistent analysis of categorical variables.

Data Distribution: The histograms of numerical columns show the distribution of values in Age, Purchase Amount (USD), Review Rating, and Previous Purchases. For example: Most customers tend to be in the middle age range, with fewer younger and older customers.

Correlation Between Variables: There may be a correlation between Purchase Amount (USD) and Review Rating or Previous Purchases.

Item Popularity: The most purchased items include categories like blouses, sweaters, jeans, and shoes. These items are frequently purchased, and their frequency distribution was visualized using a bar plot. The analysis also shows the average purchase amount for each item, with some high-end items having significantly higher average prices compared to others.

Customer Trends: Insights into customer behavior, such as purchase frequency and preferred payment methods, can be derived from the cleaned dataset. For example: Customers who frequently purchase tend to use payment methods like Venmo or Credit Card, while less frequent shoppers may prefer Cash or Bank Transfer.

#### 8.  Source

https://www.kaggle.com/datasets/tabs2255/trends
