# Task 7: Basic Sales Summary from a Tiny SQLite Database using Python

## Objective
The goal of this task is to practice using SQL inside Python to analyze a small sales dataset, summarize basic metrics like total quantity and revenue, and visualize the results using a bar chart.

## Tools Used
- *Google Colab* (Python environment)
- *SQLite* (sqlite3 library)
- *Pandas* (for data handling)
- *Matplotlib* (for visualization)

## Steps Performed

1. *Created a SQLite database* (sales_data.db) with a simple sales table.
2. *Inserted sample sales data* including product name, quantity sold, and price.
3. *Ran an SQL query* to calculate total quantity sold and total revenue per product.
4. *Loaded SQL results into Pandas DataFrame* for easy data handling.
5. *Displayed results* using print() and visualized them using a bar chart with matplotlib.
6. *Saved the chart* as sales_chart.png.

## Output
- A bar chart showing total revenue by product.
- A printed summary of total quantity and revenue for each product.

## Files Included
- sales_data.db: SQLite database containing the sales table and data
- task7_sales_summary.ipynb: Google Colab notebook with all the code
- sales_chart.png: Saved bar chart of total revenue by product
- README.md: This file

## Sample Output Table
| Product   | Total Quantity | Total Revenue |
|-----------|----------------|---------------|
| Keyboard  | 24             | 1080.0        |
| Laptop    | 15             | 10500.0       |
| Monitor   | 6              | 900.0         |
| Mouse     | 45             | 1125.0        |

## Sample Chart
![Sales Chart](sales_chart.png)

## Summary
This task helped demonstrate the integration of SQL and Python for simple data analysis and visualization, which is a useful skill in data analytics and reporting roles.
