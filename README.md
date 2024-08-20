# Retail Sales Data Analysis Project

This project involves analyzing retail sales data using Python, pandas, and NumPy. Below is a step-by-step plan for the analysis.

## 1. Load the Data

-  Load the dataset into a pandas DataFrame.

## 2. Basic Exploration

- Display the first 10 rows of the dataset.
- Display the summary statistics of the dataset.
- Find the total number of unique stores.
- Find the total number of unique products.
- Calculate the total revenue generated by all stores.

## 3. NumPy Operations

- Convert the `Quantity` column into a NumPy array.
- Calculate the mean, median, and standard deviation of the quantities sold using NumPy.
- Create a new NumPy array that contains the square root of the `Revenue` values.

## 4. Data Manipulation with pandas

- Create a new column `Revenue_per_Unit` which is the revenue divided by the quantity.
- Find the top 5 products by total revenue.
- Group the data by `Store` and calculate the total revenue for each store.
- Group the data by `Store` and `Product` and find the total quantity sold for each combination.
- Filter the data to show only sales where the revenue per unit is greater than the average revenue per unit.
- Add a new column `Cumulative_Revenue` that shows the cumulative revenue for each store over time.

## 5. Advanced Analysis

- Find the correlation between `Quantity` and `Revenue`.
- Calculate the percentage contribution of each product to the total revenue.
- Identify the store with the highest average revenue per sale.

## Getting Started

1. Clone this repository.
2. Install the required packages (e.g., pandas, numpy, matplotlib).
3. Run the analysis following the steps outlined above.
