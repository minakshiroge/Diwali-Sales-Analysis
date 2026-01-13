# Diwali-Sales-Analysis
Analyzed Diwali sales data using Python to identify high-value customer segments, top-performing states, and best-selling product categories through data cleaning, exploratory data analysis (EDA), and visualization.

## Project Objective

To analyze Diwali sales data and uncover insights related to:
- Customer demographics (age, gender, marital status)
- Regional performance
- Occupational spending patterns
- Product category demand

## Key Business Insights

- Female customers generate higher revenue than male customers
- Age group 26–35 years contributes the highest sales
- Married women have the highest purchasing power
- Uttar Pradesh, Maharashtra, and Karnataka contribute the highest orders and revenue
- IT, Healthcare, and Aviation professionals spend the most
- Food, Clothing, and Electronics dominate total festive sales

## Dataset Overview

The dataset contains Diwali sales records with customer and transaction details.

### Key Columns
- User_ID
- Gender
- Age
- Age Group
- Marital_Status
- State
- Zone
- Occupation
- Product_Category
- Product_ID
- Orders
- Amount

The dataset was preprocessed by:
- Removing blank and irrelevant columns
- Handling missing values
- Converting the Amount column to integer for accurate calculations

## Project Workflow
🔹 Step 1: Data Loading (Python – Pandas)

The dataset was loaded into a Pandas DataFrame using read_csv() with proper encoding to avoid data corruption.

🔹 Step 2: Data Cleaning & Validation

Performed:
- Removal of unnecessary columns (Status, unnamed1)
- Null value detection and removal
- Data type corrections for Amount column
- Structural checks using .info() and .describe()

Tools Used: Python (Pandas, NumPy, Matplotlib, Seaborn)

🔹 Step 3: Exploratory Data Analysis (EDA)

Performed grouping and aggregation to analyze:
- Gender Analysis – Compared number of buyers and total revenue contribution by male and female customers
- Age Group Analysis – Studied customer distribution and revenue contribution across different age groups
- State-wise Analysis – Identified top 10 states based on total orders and total sales amount
- Marital Status Analysis – Analyzed purchasing behavior by marital status and gender
- Occupation Analysis – Evaluated revenue contribution from different professional groups
- Product Category Analysis – Determined best-selling product categories and their impact on overall revenue

🔹 Step 4: Data Visualization

Used Matplotlib & Seaborn to create:
- Count plots
- Bar charts
- Pie charts
- Comparative sales graphs

These visuals helped identify:
- Top customer segments
- High-performing regions
- Revenue-driving products

📈 Analytical Findings

- Women aged 26–35 years are the most valuable customer segment
- Married women consistently generate the highest revenue
- Professionals from IT, Healthcare, and Aviation sectors show strong festive spending
- A small set of product categories drives most of the revenue
- Certain states outperform others during festive seasons

📌 Conclusion

Married women aged 26–35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors are the most profitable customers during Diwali.
They primarily purchase products from Food, Clothing, and Electronics categories.

These insights can be used to:
- Design targeted festive marketing campaigns
- Optimize inventory for high-demand categories
- Focus promotions on high-value customer segments








