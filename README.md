# Project3-Product-Sales-Analysis-Data-Visualization
Creating a Power BI dashboard to analyze product sales performance of a manufacturing company.

# Project Background
A global manufacturing company that produces bicycle equipment and accessories needs to track KPIs such 
as revenue and profit, compare performance among product categories, and analyze trends.

Insights and recommendations are provided on the following key areas:
* Sales Growth
* Increased Transaction Volume
* Cross-category Purchasing

The SQL Data Warehousing project that is responsible for cleaning the data for this project can be found here [link].

An interactive Power BI dashboard used for data analysis can be found here [link].

---

# Data Structure & Initial Checks
The following fact and dimension tables are used for this project: Sales Transactions, Product Lookup, 
Customer Lookup, and Calendar Lookup. Data Modelling used is STAR schema.

![Data Model](https://github.com/carigokva/Project3-Product-Sales-Analysis-Data-Visualization/blob/main/images/Data%20Model.png)

---

# Executive Summary

## Overview of Findings
Revenue remained steady from 2011 to 2013, then began a strong upward trend upon the introduction of 
new product categories (Accessories and Clothing). The transaction volume is driven mainly by Accessories sales. 
Even if the revenue brought by the new categories are low, it amplified the Bike sales by introducing cross category purchasing.

![Exec Dashboard](https://github.com/carigokva/Project3-Product-Sales-Analysis-Data-Visualization/blob/main/images/Dashboard.png)

---
# Insights Deep Dive

## Sales Growth
* The average revenue for 2011 to 2013 is $538,221.63.
* A clear positive trend began at the start of 2013, marking the consistent revenue growth through 2014.
  Average monthly revenue grew to $1,362,489.17 (+153%).

![Revenue Trend](https://github.com/carigokva/Project3-Product-Sales-Analysis-Data-Visualization/blob/main/images/Revenue%20Trend.png)

## Transaction Volume increased upon the introduction of new product categories
* The new product categories (Accessories and Bike) brought small revenue gains on their sales alone.
* Total number of transactions spiked from 2013 onwards, which coincides with the introduction of new product categories. Average monthly transactions from 2011 to 2013
  is 229, and 1,774 for 2013 to 2014. This results to 674% increase in the average monthly transactions.
* The spike was primarily driven by Accessories purchases which is attributed to 81.6% of the total transactions in 2013.

![Sales by Category](https://github.com/carigokva/Project3-Product-Sales-Analysis-Data-Visualization/blob/main/images/Sales%20by%20Category.png)
![Transactions by Category](https://github.com/carigokva/Project3-Product-Sales-Analysis-Data-Visualization/blob/main/images/Transactions%20by%20Category.png)

## Complementary Purchasing
* In 2013, 24.6% of the total transactions include products from the Accessories and Bike category.
* In 2013, cross-category purchases that include at least one item from Bike category, made up 40.0% of all transactions.
  This indicates a strong overlap between the Bike and other categories.

![Category Transaction Contribution](https://github.com/carigokva/Project3-Product-Sales-Analysis-Data-Visualization/blob/main/images/Category%20Transaction%20Contribution.png)

## Product Synergy
* Accessories and Clothing had minimal direct revenue impact (4.1% and 2.0%), but their synergy with the
  Bike category significantly boosted sales.
* Cross-category purchases were the main revenue driver — with Accessories & Bike purchases accounting for 54.0%,
  Accessories, Bike & Clothing for 20.5%, and Bike & Clothing for 10.6% of total sales.

![Category Revenue Contribution](https://github.com/carigokva/Project3-Product-Sales-Analysis-Data-Visualization/blob/main/images/Category%20Sales%20Contribution.png)

---

# Recommendations

## Expand Complementary Product Portfolio
* Leverage product synergy to sustain growth.
* Introduce new items that naturally complement the existing product lineup. Diversifying around the Bike category
  ensures continued revenue expansion through stronger cross-category engagement.

## Optimize Pricing and Profitability of Add-On Categories
* Turn small-ticket items into profit drivers. While Accessories and Clothing currently contribute less revenue individually,
  they play a crucial role in driving total transactions.
* Evaluate pricing strategies and consider premium positioning or bundle-based pricing for products frequently purchased with
  Bikes to maximize overall margin and order value.

## Continuously Monitor and Leverage Customer Purchase Behavior
* Regularly track and analyze cross-category purchase patterns to identify
  emerging customer preferences and protect against market shifts.
