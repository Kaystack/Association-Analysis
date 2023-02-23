# Association-Analysis

This repository contains Python code for performing association rule mining on the Online Retail dataset using the Apriori algorithm from the mlxtend library.

# Dataset
The Online Retail dataset is a transactional dataset containing customer purchases from an online retail store. The dataset includes information such as the date of the purchase, the product description, the quantity purchased, and the country of the customer.

# Code
The Python code in this repository reads in the Online Retail dataset and performs the following steps:

- Clean up the dataset by removing missing values and negative transaction IDs.
- Consolidate items into one transaction per row for each country (in this case, France).
- Encode the dataset so that each item is either a 0 (not purchased) or 1 (purchased).
- Use the Apriori algorithm to generate frequent itemsets with a minimum support of 0.07.
- Generate association rules with a minimum lift of 6 and a minimum confidence of 0.8.
- Visualize the results with a stacked bar chart showing the number of purchases for each item.
- Requirements
The code in this repository requires the following Python libraries:

- pandas
- matplotlib
- mlxtend
# Usage
To use the code in this repository, simply download the association_rule_mining.py file and run it in a Python environment with the required libraries installed.

# Credits
This code was written by me, Doris Kosy Eze and is based on the Online Retail dataset from the UCI Machine Learning Repository. The Apriori algorithm is implemented using the mlxtend library.

Feel free to modify and use this code for your own projects.
