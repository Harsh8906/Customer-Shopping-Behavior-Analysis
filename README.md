# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using **Python, Pandas, MySQL, and Power BI**. The objective is to clean and analyze customer purchase data, identify purchasing patterns, and create an interactive dashboard to support data-driven decision-making.

The project follows an end-to-end data analysis workflow:

**Raw Data → Data Cleaning and Feature Engineering → MySQL Analysis → Power BI Dashboard**

---

## Business Objectives

The analysis focuses on answering the following questions:

- Which customer segments contribute the most to revenue?
- How does purchasing behavior vary across product categories and age groups?
- What is the impact of subscription status on customer purchasing patterns?
- How do customer ratings vary across different product categories?
- What patterns can be identified in discounts and purchase behavior?

---

## Dataset

- **Records:** 3,900 customer purchase records
- **Attributes:** 18
- **Data includes:** Customer demographics, product categories, purchase amounts, review ratings, discounts, subscription status, shipping type, and purchase frequency.

The repository contains both the original dataset and the cleaned dataset generated during the data cleaning process.

---

## Tools and Technologies

- **Python** – Data cleaning and analysis
- **Pandas** – Data manipulation and feature engineering
- **MySQL** – SQL-based data analysis
- **SQLAlchemy and PyMySQL** – Database connectivity
- **Power BI** – Interactive dashboard and data visualization

---

## Data Cleaning and Feature Engineering

The data was cleaned and prepared using Python and Pandas.

Key steps included:

- Checked and handled missing values.
- Imputed **37 missing review ratings** using the median rating of the corresponding product category.
- Performed data quality checks and transformations.
- Created an **Age Group** feature for customer segmentation.
- Created a purchase-frequency feature to support customer behavior analysis.
- Exported the processed data as a cleaned CSV file for further analysis.

---

## MySQL Analysis

The cleaned dataset was loaded into MySQL for further analysis.

The project includes **10 SQL queries** using:

- Aggregate functions
- `GROUP BY`
- `CASE` statements
- Common Table Expressions (CTEs)
- Window functions

The SQL analysis explores:

- Revenue and purchasing patterns
- Customer segmentation
- Product ratings
- Discount usage
- Subscription behavior

---

## Power BI Dashboard

An interactive Power BI dashboard was developed to analyze customer purchasing behavior.

### Dashboard Features

- KPI cards for key performance metrics.
- Revenue analysis by product category.
- Customer record counts by category.
- Purchasing analysis across different age groups.
- Subscription status analysis.
- Interactive filters for gender, product category, subscription status, and shipping type.

### Key KPIs

- **Average Purchase Amount:** $59.76
- **Average Review Rating:** 3.75

---

## Key Insights

- Male customers contributed approximately **67.74% of total revenue**.
- Non-subscribers represented approximately **73% of purchase records**.
- The dashboard enables comparison of revenue and purchasing patterns across customer segments, product categories, and age groups.

---

## Project Files

This repository contains:

- Original customer shopping dataset
- Cleaned customer shopping dataset
- Jupyter Notebook for data cleaning and analysis
- SQL file containing MySQL queries
- Power BI dashboard (`.pbix` file)
- Dashboard screenshot
- `requirements.txt` file containing Python dependencies

---

## How to Run the Project

1. Download or clone this repository.

2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook to review the data cleaning and analysis process.

4. Update the MySQL connection details with your own local database credentials.

5. Run the SQL queries using MySQL.

6. Open the Power BI `.pbix` file using Power BI Desktop to explore the interactive dashboard.

---

## Dashboard Preview

The repository includes a screenshot of the interactive Power BI dashboard.

---

## Author

**Harsh Panchal**

### Skills Demonstrated

**Data Cleaning | Exploratory Data Analysis | Feature Engineering | SQL | MySQL | Python | Pandas | Power BI | Data Visualization**
