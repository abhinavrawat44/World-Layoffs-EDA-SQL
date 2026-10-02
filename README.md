# 📈 World Layoffs - Exploratory Data Analysis (EDA) using SQL

## 🎯 Project Overview
Following up on the data cleaning phase, this project dives deep into the cleaned global layoffs dataset to extract meaningful business insights and trends using advanced MySQL querying techniques.

## 🛠️ Advanced SQL Concepts Used
* **Aggregate Functions:** `SUM()`, `MAX()`, `MIN()` to analyze the total scale of layoffs[cite: 6].
* **String Manipulation:** `SUBSTRING()` to extract and group data by specific time periods (Months)[cite: 6].
* **Common Table Expressions (CTEs):** Used for structuring complex queries like rolling totals and multi-level rankings[cite: 6].
* **Window Functions (`OVER()`):** 
  * Calculated running/rolling totals of layoffs chronologically[cite: 6].
  * Utilized `DENSE_RANK()` partitioned by years to find the top 5 laid-off companies annually[cite: 6].

## 🔍 Key Business Questions Answered
1. What were the maximum layoffs and peak percentages recorded?[cite: 6]
2. Which companies faced the highest total layoffs globally?[cite: 6]
3. How did layoffs progress month-over-month, and what is the cumulative rolling total over time?[cite: 6]
4. Which companies topped the layoff charts year-over-year using ranking window functions?[cite: 6]

## 📁 File Included
* `Layoffs_EDA.sql`: Complete script containing all exploratory queries, CTEs, and ranking logics[cite: 6].
