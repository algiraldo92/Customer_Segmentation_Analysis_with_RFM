# Customer_Segmentation_Analysis_with_RFM
RFM is a customer analysis technique that allows segmenting them into groups based on their purchasing behavior. The name comes from the three dimensions it analyzes: Recency, Frequency and Monetary.

---

## Objective

The main objective of this project is to:

Identify and categorize customers according to their purchasing patterns.

Understand which customers are the most loyal, most valuable, or at risk of churning.

Provide actionable insights to improve marketing campaigns, retention strategies, and customer engagement.

---

## Methodology

Data Collection
The dataset used in this project is based on online retail transactions.
It contains customer IDs, invoice numbers, dates, product details, quantities, and purchase amounts.

Data Cleaning and Preparation

Removal of missing values and duplicates

Filtering out canceled orders and negative quantities

Converting invoice dates to datetime format

RFM Calculation

Recency (R): How recently a customer made a purchase.

Frequency (F): How often the customer makes purchases.

Monetary (M): How much money the customer spends.

RFM Scoring
Customers are assigned a score for each RFM dimension.
Higher scores indicate more desirable customers.

Customer Segmentation
Using the combined RFM scores, customers are grouped into meaningful segments

---

### Technologies used:
* pandas
* numpy
* matplotlib
* scipy
* seaborn
* sklearn

---

[See Project](https://github.com/algiraldo92/Customer_Segmentation_Analysis_with_RFM/blob/main/Cluster_RFM.ipynb)
