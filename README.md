# RFM-analysis / Customer Segmentation Analysis

## Story and Background
Transaction data, like PoS (point of sales) data, is analyzed based on customers' purchasing behaviour: recency (R), frequency (F) and monetary (M). Redefine customer segmentation is always been a good practice in terms of marketing research. In this repo, I defined/redefined customers segments using non-hierarchical cluster analysis (K-means clustering) techniques based on customers' RFM scores.

## Data Gathering and Analysis
Although, for a small dataset, all data manipulation can be done in python. When dealing with extremely large dataset, use SQL to perform ETL is always a good practice. In customer segmentation analysis, 1) find the most recent transaction for each customer (days from now), 2) sum up all payment transactions over time for each customer (Total spent), and 3) count the number of purchases for each customer (Number of Purchases).

Python can be used to analyze the data. 1) assign RFM scores based on the values, 2) perform K-means clustering and define the different groups of customers to be targeted by different marketing strategies. 

## Impact and Results
Targeted different segments of customers with different communications such that 1) best customers would feel valued and appreciated; 2) high spender would feel incentive to interact with the brand more; 3) loyal but low spender would feel incentive to spend more; 4) churned customer would want to come back and try the brand again.

It cultivates loyal, high spending customers, saves communication/marketing budget and achieved more sales and increase in profit.
 
