# Exploratory-Data-Analysis-EDA-and-Visualization-of-CSV-Data-Using-Pandas-and-Matplotlib
Sales Data Analysis Project
Overview

This project performs data analysis and visualization on a sales dataset using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.
The goal is to extract meaningful insights like revenue trends, product performance, and regional sales patterns.

Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Dataset

The dataset used in this project is:
sales_data.csv

It contains the following information:

Product Category
Product Name
Units Sold
Total Revenue
Region
Payment Method
Steps Performed
1. Data Loading
Loaded dataset using Pandas
Displayed initial data
2. Data Exploration
Used info() to understand structure
Used describe() for statistical summary
3. Data Cleaning
Checked missing values using:
isnull()
isnull().sum()

4. Data Analysis
Calculated average total revenue
Grouped data by product category to find:
Mean revenue
Total units sold

5.Visualizations
Bar Chart – Product Category vs Units Sold
Line Plot – Product Name vs Total Revenue
Scatter Plot – Total Revenue vs Units Sold
Heatmap – Region vs Payment Method (Total Revenue)
Key Insights
Some product categories contribute significantly more to revenue
Higher units sold generally lead to higher revenue (positive correlation)
Revenue varies across regions and payment methods
Certain products dominate total revenue

How to Run

Install required libraries:

pip install pandas numpy matplotlib seaborn
Place sales_data.csv in the correct directory

Run the Jupyter Notebook:

jupyter notebook project1.ipynb
Project Structure
project1.ipynb
sales_data.csv
README.md
