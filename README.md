# Association-Analysis

Association analysis is a data mining technique that identifies associations or relationships among items in a large dataset. In other words, it helps to find out which items or events are most likely to occur together. This technique is widely used in various domains such as marketing, retail, and healthcare to analyze customer behavior, sales patterns, and disease diagnosis, respectively.

The purpose of this association analysis project is to identify the frequent itemsets and association rules between items in the transactional dataset. The dataset used for this project is the Online Retail dataset, which contains transactional data of a UK-based online retail store. The analysis is focused on the transactions made in France only.

To achieve this, we used the Apriori algorithm to generate the frequent itemsets with a minimum support threshold of 7%. From the frequent itemsets, we then used the Association Rule algorithm to extract the rules based on a minimum lift threshold of 1 and a minimum confidence threshold of 0.8. The analysis provides insights into the co-occurrence of items in the transactions, which can be used to make informed decisions such as product bundling, pricing, and marketing strategies.

The code and the output of the analysis have been shared on GitHub for anyone interested in exploring the details of the analysis.

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

# Requirements
The code in this repository requires the following Python libraries:

- pandas
- matplotlib
- mlxtend
# Usage
To use the code in this repository, simply download the association_rule_mining.py file and run it in a Python environment with the required libraries installed.

# Credits
This code was written by me, Doris Kosy Eze and is based on the Online Retail dataset from the UCI Machine Learning Repository. The Apriori algorithm is implemented using the mlxtend library.

Feel free to modify and use this code for your own projects.
