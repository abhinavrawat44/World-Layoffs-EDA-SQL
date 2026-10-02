# 📈 World Layoffs - Exploratory Data Analysis (EDA) using SQL

## 🎯 Project Overview
Following up on the data cleaning phase, this project dives deep into the cleaned global layoffs dataset to extract meaningful business insights and trends using advanced MySQL querying techniques.

## 🛠️ Advanced SQL Concepts Used
* **Aggregate Functions:** `SUM()`, `MAX()`, `MIN()` to analyze the total scale of layoffs
* **String Manipulation:** `SUBSTRING()` to extract and group data by specific time periods (Months)
* **Common Table Expressions (CTEs):** Used for structuring complex queries like rolling totals and multi-level rankings
* **Window Functions (`OVER()`):** 
  * Calculated running/rolling totals of layoffs chronologically
  * Utilized `DENSE_RANK()` partitioned by years to find the top 5 laid-off companies annually
## 🔍 Key Business Questions Answered
1. What were the maximum layoffs and peak percentages recorded?
2. Which companies faced the highest total layoffs globally?
3. How did layoffs progress month-over-month, and what is the cumulative rolling total over time?
4. Which companies topped the layoff charts year-over-year using ranking window functions?

## 📁 File Included
* `Layoffs_EDA.sql`: Complete script containing all exploratory queries, CTEs, and ranking logics.
