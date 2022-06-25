# Groceries dataset - Market-Basket-Analysis

![istockphoto-1194709125-170667a](https://user-images.githubusercontent.com/70154122/175789490-635508e0-1e36-4dbd-8f7e-54a7a27c7474.jpg)

## About Dataset
Association Rule Mining
Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy.
Association Rules are widely used to analyze retail basket or transaction data and are intended to identify strong rules discovered in transaction data using measures of interestingness, based on the concept of strong rules.

## Details of the dataset
The dataset has 38765 rows of the purchase orders of people from the grocery stores. These orders can be analysed and association rules can be generated using Market Basket Analysis by algorithms like Apriori Algorithm.

## Apriori Algorithm
Apriori is an algorithm for frequent itemset mining and association rule learning over relational databases. It proceeds by identifying the frequent individual items in the database and extending them to larger and larger item sets as long as those item sets appear sufficiently often in the database. The frequent itemsets determined by Apriori can be used to determine association rules which highlight general trends in the database: this has applications in domains such as market basket analysis.

## An example of Association Rules
Assume there are 100 customers
10 of them bought milk, 8 bought butter and 6 bought both of them.
bought milk => bought butter
support = P(Milk & Butter) = 6/100 = 0.06
confidence = support/P(Butter) = 0.06/0.08 = 0.75
lift = confidence/P(Milk) = 0.75/0.10 = 7.5

Note: this example is extremely small. In practice, a rule needs the support of several hundred transactions, before it can be considered statistically significant, and datasets often contain thousands or millions of transactions.

## Some important terms:
Support: This says how popular an itemset is, as measured by the proportion of transactions in which an itemset appears.

Confidence: This says how likely item Y is purchased when item X is purchased, expressed as {X -> Y}. This is measured by the proportion of transactions with item X, in which item Y also appears.

Lift: This says how likely item Y is purchased when item X is purchased while controlling for how popular item Y is.

## Objective

The objective of this project was to find the buying behaviour of the customers of Instacart. The lift, confidence and support for items are studied over the entire period of 2 years, followed by the change in shopping behaviour of the customers based on weekends and weekdays as well as the behaviour of the customers on a half-yearly basis.
These insights will allow for a better understanding of customers buying behaviours as well as items which should be discounted more or customers who can be given special discounts to increase sales of the e-commerce organization.
The project has been completed using python language on Google Colab notebook.
Market Basket Analysis, Apriori, association rules and other techniques have been used to draw insights from the data.
