#  Sales Analysis

## 📌 Project Overview

**Sales Analysis** is a data analytics project focused on understanding customer purchasing behavior and identifying important sales trends during the Diwali festival season.

The project uses **Exploratory Data Analysis (EDA)** to analyze customer demographics, geographical regions, occupations, purchasing behavior, and product categories. The insights generated from the analysis can help businesses improve **targeted marketing strategies, customer engagement, and inventory management**.

---

## 🎯 Problem Statement

During major festival seasons such as Diwali, businesses receive large volumes of sales data from customers across different demographic groups and geographical regions. However, without proper analysis, it can be difficult to identify:

* Which customer groups contribute the most to sales.
* Which age groups have higher purchasing activity.
* Which states and regions generate the highest number of orders and revenue.
* How gender and marital status influence purchasing behavior.
* Which occupations represent high-value customer groups.
* Which product categories and products are the most popular.

The challenge of this project was to transform raw sales data into meaningful business insights that could support better marketing and inventory decisions.

---

## 💡 Solution

To solve this problem, I performed **Exploratory Data Analysis (EDA)** using Python.

The project followed these major steps:

### 1. Data Collection and Loading

The Diwali sales dataset was imported using **Pandas**. The dataset initially contained **11,251 records and 15 variables**.

### 2. Data Cleaning and Preprocessing

The following preprocessing steps were performed:

* Removed irrelevant and empty columns.
* Checked the dataset for missing values.
* Removed records containing missing values.
* Converted the `Amount` column into an appropriate integer data type.
* Performed descriptive statistical analysis.

### 3. Exploratory Data Analysis

Customer purchasing patterns were analyzed based on:

* 👩 **Gender**
* 🎂 **Age Group**
* 🗺️ **State and geographical location**
* 💍 **Marital Status**
* 💼 **Occupation**
* 🛍️ **Product Category**
* 📦 **Product ID and number of orders**
* 💰 **Purchase Amount**

Various visualizations were created to identify trends and compare customer groups.

### 4. Business Insights

The analysis helps identify:

* Important customer demographic segments.
* High-performing geographical markets.
* Customer groups with higher purchasing behavior.
* High-performing occupational segments.
* Popular product categories.
* Top-selling products.

These insights can support businesses in developing more effective **targeted marketing campaigns** and improving **inventory planning during peak festival seasons**.

---

## 🛠️ Technologies and Libraries Used

* **Python**
* **Jupyter Notebook**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization

---

## 📊 Dataset Information

| Feature          | Description                    |
| ---------------- | ------------------------------ |
| User_ID          | Unique customer identification |
| Cust_name        | Customer name                  |
| Product_ID       | Unique product identification  |
| Gender           | Gender of the customer         |
| Age Group        | Customer age category          |
| Age              | Customer age                   |
| Marital_Status   | Marital status                 |
| State            | Customer's state               |
| Zone             | Geographical zone              |
| Occupation       | Customer occupation            |
| Product_Category | Category of purchased product  |
| Orders           | Number of orders               |
| Amount           | Purchase amount                |

**Dataset Size:** 11,251 records and 15 variables before data cleaning.

---

## 📁 Project Structure

```text
Diwali-Sales-Analysis/
│
├── Diwali Sales Analysis.ipynb
├── Diwali Sales Data.csv
├── README.md
└── images/
    └── visualizations/
```

---

## 🎯 Project Objective

The primary objective of this project is to transform raw Diwali sales data into meaningful insights by identifying key consumer demographic profiles, high-performing geographical regions, and popular product categories.

The findings can help businesses:

* Improve customer targeting.
* Develop data-driven marketing strategies.
* Identify valuable customer segments.
* Optimize product offerings.
* Improve inventory management during festival seasons.

---

## 👤 Author

**Ayan Paul**

This project was completed **independently from start to finish**. I was responsible for data preparation, cleaning, exploratory data analysis, visualization, interpretation of results, and documentation.

---

## ⭐ If You Like This Project

If you find this project useful or interesting, consider giving the repository a **star ⭐**!

