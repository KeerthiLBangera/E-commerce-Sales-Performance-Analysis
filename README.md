# E-commerce Sales Performance Analysis

## Project Overview
This project involves a comprehensive analysis of an e-commerce retail dataset to uncover key sales trends, identify top-performing products, understand customer purchasing behavior, and visualize geographical sales distribution. The insights gained are presented in an interactive dashboard to support data-driven decision-making.

## Problem Statement / Business Questions
* What are the overall sales figures and average order values?
* How have sales trends evolved over time (monthly, daily, hourly)?
* Which products are the top revenue generators?
* Who are the most valuable customers?
* What is the geographical breakdown of sales?

## Data Source
The dataset used for this analysis contains transactional data from a UK-based online retail store. It includes information on invoices, stock codes, product descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

## Tools Used
* **Python:** For data cleaning, preprocessing, and exploratory data analysis (EDA).
    * Libraries: Pandas (for data manipulation), Matplotlib & Seaborn (for initial visualizations).
* **Jupyter Notebook:** For developing and documenting the Python analysis workflow.
* **Tableau Public:** For creating an interactive and visually appealing business intelligence dashboard.
* **GitHub:** For version control and project hosting.

## Key Steps Taken
1.  **Data Loading & Initial Inspection:** Loaded the raw CSV data into a Pandas DataFrame and performed initial checks on data types, missing values, and statistical summaries.
2.  **Data Cleaning & Preprocessing:**
    * Handled missing values in `CustomerID` and `Description`.
    * Removed rows with non-positive `Quantity` and `UnitPrice`.
    * Converted `InvoiceDate` to datetime objects and `CustomerID` to integer.
3.  **Feature Engineering:**
    * Created `TotalPrice` by multiplying `Quantity` and `UnitPrice`.
    * Extracted `InvoiceYearMonth`, `InvoiceDayOfWeek`, and `InvoiceHour` from `InvoiceDate` for time-based analysis.
4.  **Exploratory Data Analysis (EDA):**
    * Calculated overall sales metrics (Total Sales, Average Order Value, Unique Customers, Unique Products).
    * Analyzed sales trends by month, day of week, and hour of day.
    * Identified top 10 selling products by revenue.
    * Identified top 10 customers by total spending.
    * Analyzed sales distribution by country.
5.  **Interactive Dashboard Development:**
    * Built a comprehensive dashboard in Tableau Public, incorporating all key insights.
    * Included interactive filters (e.g., by Country) for deeper exploration.

## Key Findings & Insights
* The total sales amounted to **£8,911,407.90** over the analyzed period.
* Sales show a distinct **upward trend towards the end of the year**, with November typically being the highest-grossing month.
* **Thursdays and Tuesdays** are the busiest sales days, while there are no recorded sales on Saturdays.
* The peak sales hours are typically between **10 AM and 3 PM**.
* The product **'Papercraft, Little Birdie'** was the highest revenue-generating product.
* **Customer ID 14646** was the top-spending customer.
* The **United Kingdom** accounts for the vast majority of sales, followed by the Netherlands and EIRE.

## Live Dashboard
Explore the interactive dashboard on Tableau Public:
[**E-commerce Sales Performance Dashboard**](https://public.tableau.com/app/profile/keerthi.l.bangera/viz/Book1_17484349023770/Dashboard1?publish=yes)


---
