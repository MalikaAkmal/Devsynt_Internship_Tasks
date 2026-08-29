# Chinook Digital Media Store - Data Analysis Project

## Project Overview
This project is an exploratory data analysis of the Chinook Digital Media Store database. The objective is to extract actionable business intelligence regarding sales trends, customer purchasing behavior, and employee performance using SQL and Python.

## Project Deliverables
* **`analysis.sql`**: Contains 20 structured SQL queries extracting key business metrics.
* **`analysis.ipynb`**: A Jupyter Notebook demonstrating database connection, data extraction, and Matplotlib/Seaborn visual analysis.
* **`chinook_dashboard.png`**: A consolidated data dashboard generated via Python highlighting high-level KPIs.
* **CSV Data Extracts**: Raw tabular data exported directly from the SQLite database.

## Top 5 Business Insights

1. **Rock Music Dominates Sales:** 
   The "Rock" genre is the primary revenue driver for the store, vastly outperforming all other genres. Marketing efforts and inventory expansion should heavily prioritize this category.

2. **The USA is the Primary Market:** 
   The United States generates the highest total revenue and holds the largest customer base, followed by Canada and France. Targeted promotional campaigns in North America yield the highest return on investment.

3. **Consistent Average Order Value (AOV):** 
   Customers maintain a steady average transaction size of approximately $5.65. Bundling tracks or offering album-level discounts could help push this average higher.

4. **Equal Sales Representative Performance:** 
   Revenue generation is highly balanced across the sales support team. No single employee is severely lagging or dominating, indicating a well-distributed customer assignment system.

5. **Heavy Reliance on Top Artists:** 
   A small, concentrated group of legacy artists (e.g., Iron Maiden, U2) accounts for a disproportionate amount of total sales, while a significant number of available tracks have never been purchased. The store could save on licensing or storage by auditing unpurchased inventory.