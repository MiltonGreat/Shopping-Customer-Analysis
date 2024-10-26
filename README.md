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

- Handling Missing Values
- Outlier Detection and Handling
- Standardizing Categorical Values
- Handling Duplicates

#### 4. Exploratory Data Analysis (EDA)

- Summary Statistics: It generated summary statistics for numerical columns to understand basic trends in age, purchase amount, previous purchases, and review ratings.

- Unique Value Checks for Categorical Variables: It printed unique values in categorical columns like Gender, Item Purchased, Category, etc., to verify the integrity and consistency of the data.

#### 5. Data Visualization

- Histograms of numerical columns
- Box Plots show distribution of purchase amounts by gender and subscription status, revealing patterns of spending behavior
- Count plots for categorical columns like Gender, Item Purchased, Category
- Bar plots for the most purchased items and the average purchase amount for each item
- Pair plots were used to visualize relationships between multiple numerical variables

#### 7. Key Findings
      
Customer Demographics: The average age of customers across different categories is quite similar, with values around 44 years. The Footwear category has the highest average customer age, while Clothing has the lowest.

Most Popular Items by Season: The most popular items vary by season. For instance, jackets are most popular in fall, sweaters in spring, pants in summer, and sunglasses in winter.

Purchasing Behavior: The analysis of the most purchased items revealed the top 10 most frequently bought products, while additional plots showed that the average purchase amount varies significantly depending on the item and the season.

Seasonal Trends: Purchases peak in certain seasons, with significant differences in the types of items bought across seasons. Winter and fall are seasons where jackets and sunglasses are more commonly purchased, while pants dominate summer.

Payment Methods: Credit cards, PayPal, and bank transfers are the most common payment methods, suggesting a mix of traditional and online payment preferences among customers.

Promo Code Usage: The distribution of promo code usage and discounts applied suggests that customers frequently take advantage of promotions, which is further analyzed by comparing purchase amounts with and without promo codes.

#### 8.  Source

https://www.kaggle.com/datasets/tabs2255/trends
