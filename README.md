# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI to uncover meaningful business insights from retail transaction data. The project follows a complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), SQL-based business analysis, dashboard creation, and reporting.

The objective is to understand customer purchasing patterns, product preferences, spending behavior, and subscription trends to support data-driven business decisions.

---

## Dataset

The dataset contains customer shopping transactions with demographic, purchase, and behavioral information.

**Dataset Highlights**
- Customer demographics
- Product categories
- Purchase amounts
- Review ratings
- Discounts and promotions
- Shipping methods
- Subscription status
- Purchase frequency

---

## Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn

- **SQL**
  - PostgreSQL
  - MySQL
  - Microsoft SQL Server

- **Power BI**

- **Jupyter Notebook**

---

## Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas
- Explored dataset structure and summary statistics

### 2. Data Cleaning
- Handled missing values
- Standardized column names
- Removed redundant columns
- Created new features for analysis
- Verified data consistency

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer demographics
- Studied purchase behavior
- Compared spending patterns
- Examined category-wise sales
- Identified customer trends using visualizations

### 4. SQL Analysis
Performed business analysis using SQL on PostgreSQL, MySQL, and SQL Server, including:

- Revenue by gender
- Subscriber vs non-subscriber analysis
- Top-rated products
- Customer segmentation
- Shipping method comparison
- Repeat customer analysis
- Product performance
- Revenue by age group
- Discount analysis

### 5. Power BI Dashboard
Created an interactive dashboard to visualize key business metrics, including:

- Total Revenue
- Customer Segments
- Product Categories
- Purchase Trends
- Subscription Analysis
- Sales Distribution
- Customer Demographics

### 6. Business Report
Prepared a report summarizing the analysis, findings, visualizations, and business recommendations.

---

## Key Results

- Identified customer purchasing patterns.
- Analyzed spending behavior across different customer groups.
- Discovered top-performing products and categories.
- Evaluated the impact of subscriptions on revenue.
- Compared purchasing behavior based on shipping methods.
- Generated actionable business recommendations using data insights.

---

## Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── Customer_Shopping_Dashboard.pbix
│
├── report/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
├── images/
│   └── dashboard_screenshot.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Dashboard

The Power BI dashboard provides an interactive view of:

- Revenue Analysis
- Customer Demographics
- Product Performance
- Customer Segmentation
- Subscription Insights
- Purchase Trends

> *(Add dashboard screenshots here after uploading them.)*

---

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/Customer-Shopping-Behavior-Analysis.git
```

2. Install the required Python libraries.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Execute the notebook to perform:
- Data loading
- Data cleaning
- Exploratory data analysis

5. Import the cleaned dataset into PostgreSQL, MySQL, or SQL Server.

6. Execute the SQL queries provided in the `sql` folder.

7. Open the Power BI dashboard (`.pbix`) to explore the interactive visualizations.

---

## Future Improvements

- Build predictive models for customer spending.
- Create customer lifetime value analysis.
- Develop interactive web dashboards.
- Automate data refresh and reporting.

---

## Author

**Shruti Raskar**

Aspiring Data Analyst passionate about transforming raw data into meaningful business insights using Python, SQL, and Power BI.

---
