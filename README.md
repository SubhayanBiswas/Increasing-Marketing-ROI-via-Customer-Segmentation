# Increasing Marketing ROI via Customer Segmentation 🚲

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Pandas%20%7C%20Jupyter-orange)
![SQL](https://img.shields.io/badge/SQL-Data_Extraction-lightgrey)

This repository contains an end-to-end data analytics project designed to solve a core business challenge for a bicycle retailer: transitioning from inefficient, generic mass marketing to a highly targeted, data-driven customer retention strategy.

## 📖 Executive Summary
By analyzing historical transactional data, this project successfully segments the retailer's customer base into four distinct, actionable cohorts. The analysis prioritizes identifying high-value retention opportunities, specifically isolating loyal "Champions" and previously valuable "At-Risk Champions" who are in danger of churning. 

The resulting framework provides specific, targeted marketing recommendations for each group, aiming to significantly increase customer retention, drive revenue growth, and maximize marketing Return on Investment (ROI).



## 🛠️ Methodology & Architecture
* **Data Extraction & Aggregation:** Raw transactional data was extracted and pre-aggregated using SQL (see `queries.sql`).
* **Segmentation Analysis:** Customer behaviors were processed and clustered in Python using Jupyter Notebook, focusing on purchasing patterns, frequency, and monetary value.

## 📊 Key Customer Segments Identified
1. **Champions:** Highly valuable, frequent buyers with strong brand loyalty.
2. **At-Risk Champions:** Previously high-value customers showing recent signs of churn.
3. **New & Promising:** Recent first-time buyers who need nurturing to become repeat customers.
4. **Lost Customers:** Dormant accounts with low probability of return.

## 💡 Strategic Marketing Recommendations
The analysis translates data into the following targeted business actions:
* **Champions:** Launch an exclusive VIP program offering early access to new products, aiming to increase their Annual Recurring Revenue (ARR) by 10%.
* **At-Risk Champions:** Trigger personalized "We Miss You" re-engagement campaigns with limited-time discounts on preferred categories, targeting a 20% win-back rate this quarter.
* **New & Promising:** Automate an onboarding "Welcome" series providing value (e.g., maintenance tips) and a second-purchase incentive, aiming to boost conversion rates by 15%.
* **Lost Customers:** Minimize ad spend; relegate to a low-effort, automated newsletter to maintain basic brand awareness.

## 📂 Repository Structure
* `Bike_Sales.ipynb`: The core Python notebook containing the exploratory data analysis, segmentation logic, and strategic framework.
* `Bike_Sales.sql`: The queries used to extract and aggregate the raw transactional data.
* `bike_sales.zip`: The zip file consisting of all the data used in this analysis.

## 👤 Author
**Subhayan Biswas**
