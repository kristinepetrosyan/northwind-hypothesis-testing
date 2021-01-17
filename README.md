# Northwind Hypothesis Testing

<img src="/Images/sale.jpg" alt="Image of clothes in a shop with various discount labels" >

*By Nadine Amersi-Belton*

## Problem statement

As a data scientist working for Northwind Traders, I have been tasked with drawing insights from a given database. In particular, I will seek to answer the following questions, which are of interest to stakeholders:

1. Do discounts have a statistically significant effect on the number of products customers order? And if so, at what level(s) of discount?
2. Do discounts have a statistically significant effect on the amount a customer spends on their order? And if so, at what level(s) of discount?
3. Does the average order amount vary significally between customers in different regions?

## Components

* **Jupyter Notebooks**

The [Jupyter Notebook](https://github.com/nadinezab/northwind-hypothesis-testing/blob/main/northwind.ipynb) is our key deliverable and contains the answers to the above questions.

## Data

The data was provided in the form of a SQLite database and can be found in this repository.
It was originally provided by Flatiron School in the following [repository](https://github.com/learn-co-students/dsc-2-final-project-online-ds-ft-011419).

## Methodology

* The relevant data was queried from the table and stored as a Pandas DataFrame. 
* Data manipulation was undertaken as required (e.g. creating feature columns). 
* Null and alternative hypothesis were formulated.
* EDA and visualisations were created.
* Statistical (t-tests, ANOVA) were used to formally assess the impact of discounts.


## Findings and Recommendations

* Hypothesis testing revealed that discounts have a statistically significant effect on the number of products customers order. Orders with discounts contain 5 more items on average, which is an increase of 25%. However there are no statistically significant differences between the different levels of discount.
* Hypothesis testing revealed that discounts have a statistically significant effect on the amount a customer spends on their order. On average customers spend USD143 on orders with discounts, which is a 10% increase. However there are no statistically significant differences between the different levels of discount.
* Hypothesis testing revealed that there are statistically significant differences in the average order revenue depending on the customer location.

<span>Photo by <a href="https://unsplash.com/@belart84?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Artem Beliaikin</a> on <a href="https://unsplash.com/s/photos/discount?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>