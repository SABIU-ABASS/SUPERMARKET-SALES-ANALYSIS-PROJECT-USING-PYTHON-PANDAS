# SUPERMARKET-SALES-ANALYSIS-PROJECT-USING-PYTHON-PANDAS
### Overview
This project aims to analyse the sales, profit and profit margin of a supermarket in the United states over a period of four years and gives insights to factors affecting their sales and how they can best optimize their profit using Python PANDAS.
### CONTENTS
- [INTRODUCTION](#introduction)

- [DATA CLEANING](#data-cleaning)

- [DATA PROCESSING](#data-processing)

- [INSIGHTS](#insights)

- [CONCLUSION](#conclusion)

### INTRODUCTION
This dataset comprises of information of a supermarket in United States, which includes the product id, quantity of product order, the year of the order, the customer id, the year of the order, the price of the unit order, the tax on each product and so on.
The datasets has 1,105 rows and 26 columns, all which are arranged with no particular pattern.

In this project, we are going to use the Python PANDAS to clean, analyse and draw valuable insights from the dataset that will enhance good decision and policy making among concerned stakeholders, which can be the company heads, customers and even researchers. We are going to check which year and month do we have the largest sales and which year and month do we have the lowest sales, we are going to check the trajectory of the company if it has more sales than the previous year or not, and also give recommendation on how to further improve sales and increase performance and trajectory.

Lastly in this project, we are going to forecast key performance of the business, which is order and sales for the next ten years and give recommendation that could help the company's growth.

### DATA CLEANING
Data cleaning is the process of identifying and correcting errors, inconsistencies and inaccuracies in data to ensure its accurate, complete, and reliable for analysis and decision making.
```python
import pandas as pd

df = pd.read_csv('pappystone_new.csv') # This is to load the dataset

df.head(10) # This to have a view of the dataset

df.info() # This to check for null values and data type in each column of the dataset

df.columns # This to show all the columns in the dataset

df.describe() # This is to statistically summarize the dataset

# Congratulations! The dataset has no null values and has no repetition
```
