# Diwali_Sales_Analysis

An Exploratory Data Analysis (EDA) project in Python focused on evaluating customer purchasing behaviors during the Diwali holiday season.



## Dataset Architecture
Primary Features: User_ID, Cust_name, Product_ID, Gender, Age Group, Age, Marital_Status, State, Zone, Occupation, Product_Category, Orders, and Amount.

Dataset Size: Contains over 11,000 transaction records capturing retail activity during the peak festival window.


## Data Processing Pipeline

Cleaning & Preprocessing: Removed empty columns (Status, unnamed1), dropped records containing missing values in the critical Amount feature, and cast floating-point numbers to integers (Amount.astype('int')) to save memory and ensure numeric consistency.

Statistical Overview: Utilized df.describe() to inspect central tendency metrics (mean, median, standard deviation) across total spend and order counts.


## Exploratory Data Analysis (EDA) Highlights

Gender Demographics: Grouped orders and amount totals by gender using Seaborn bar plots (sns.barplot), proving that married women drive a majority of both sales volume and revenue contribution.

Age Distribution: Segmented age brackets (e.g., 0-17, 18-25, 26-35, 36-45) using sns.countplot to pinpoint the 26–35 age group as the primary spending cohort.

Geographical Distribution: Aggregated top 10 states by sales volume and expenditure using Pandas .groupby(), highlighting Uttar Pradesh, Maharashtra, and Karnataka as top drivers.

Product & Industry Trends: Filtered product categories and customer occupations to show that professionals in IT, Healthcare, and Aviation lead overall spending, primarily on Food, Clothing, and Electronics.


 ## Problem Statement 
 Retailers often struggle to maximize holiday sales efficiency due to a lack of clear visibility into customer demographics, regional purchasing power, and top-performing product categories. Without actionable data insights, marketing campaigns and inventory management strategies risk misallocating budget and resources toward underperforming customer segments. The primary objective of this project is to analyze Diwali sales dataset records ($11,239$ clean entries) to identify key buyer profiles and purchasing patterns, enabling businesses to optimize target marketing and inventory planning.


## Solution 
Using Python data analysis and visualization libraries (Pandas, NumPy, Matplotlib, and Seaborn), this project carries out data cleaning, transformation, and thorough exploratory analysis to uncover the demographic and geographic drivers of sales volume and total spending.  
