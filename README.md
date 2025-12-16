# Sales Data Summary using SQLite and Python

## Objective

This project demonstrates how to:
- Connect to a SQLite database using Python
- Import Excel-based sales data
- Run basic SQL queries to calculate total quantity sold and revenue per product
- Display the results using print statements and a bar chart

## Tools Used
- Python
- SQLite (via `sqlite3`)
- Pandas
- Matplotlib
- Google Colab / Jupyter Notebook

## Dataset

An Excel file (`Sales Dataset.xlsx`) containing sales records with the following columns:
- `date`: Date of sale
- `product`: Product name
- `quantity`: Number of units sold
- `price`: Price per unit

## Key Steps

1. Upload & Read Excel File
   - Load the Excel file using `pandas.read_excel()`.

2. Create SQLite Database
   - Create a SQLite database file (`sales_data.db`) and define a `sales` table.

3. Insert Data
   - Populate the `sales` table with the uploaded Excel data.

4. Run SQL Queries
   - Use SQL to calculate total quantity and total revenue per product.

5. Visualize Results
   - Load the query result into a DataFrame.
   - Generate a bar chart showing revenue per product using `matplotlib`.

## Output

- **Printed Sales Summary Table**
- **Revenue per Product Bar Chart**
- Chart saved as: `sales_chart.png`
