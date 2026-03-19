SQL EDA - Tech Layoffs Dataset
A beginner-friendly MySQL project that explores a cleaned real-world tech layoffs 
dataset. Covers aggregations, trend analysis, and rankings using GROUP BY, CTEs, 
window functions, and rolling totals.

Queries
1. Max Layoffs & 100% Shutdowns - companies that fully closed down
2. Layoffs by Group - broken down by company, industry, country, location, stage, and year
3. Top Companies per Year - DENSE_RANK() to rank companies by layoffs each year
4. Rolling Monthly Total - cumulative layoffs over time using CTEs and SUM() OVER()

Tools
* MySQL 8.0+
* Dataset: `layoffs_staging2` (output of the Data Cleaning project)

How to Run
1. Complete the Data Cleaning project first
2. Run `eda_project.sql` against `layoffs_staging2`
