Project Overview

This project performs sales data analysis using Python.
The objective of the project is to analyze total sales, identify the best-selling product, and study monthly sales trends using a given CSV dataset.

Tools and Technologies Used
Google Colab was used as the development environment.
Python programming language was used for analysis.
Pandas library was used for data manipulation.
Matplotlib library was used for data visualization.

Dataset Description
The dataset is provided in CSV format.
It contains the following fields:
order_id, order_date, product_name, category, quantity, unit_price, and total_amount.
The dataset represents sales transactions for different products.

Methodology
The CSV file was loaded into the notebook using Pandas.
Basic data inspection was performed using head() and info().
Total sales amount was calculated using the total_amount column.
The best-selling product was identified by grouping products based on sales.
The order_date column was converted into datetime format.

Monthly sales were calculated and analyzed.
A line graph was plotted to visualize monthly sales trends.

Results
The total sales amount was successfully calculated.
The product with the highest sales was identified.
Monthly sales trends were visualized using a graph.
Conclusion
This project shows how Python can be used for basic sales data analysis.
It helps in understanding sales performance and trends from raw data.
