# Credit-Card-Clustering

This project, will be performing an unsupervised clustering of data on the Credit Card customer's.
Customer segmentation is the practice of separating customers into groups that reflect similarities among customers in each cluster. and divide customers into segments to optimize the significance of each customer to the business. To modify products according to distinct needs and behaviours of the customers. It also helps the business to specify manage risk on customers.

# Data Information
  - CUSTID : Identification of Credit Card holder (Categorical)
  - BALANCE : Balance amount left in their account to make purchases
  - BALANCEFREQUENCY : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
  - PURCHASES : Amount of purchases made from account
  - ONEOFFPURCHASES : Maximum purchase amount done in one-go
  - INSTALLMENTSPURCHASES : Amount of purchase done in installment
  - CASHADVANCE : Cash in advance given by the user
  - PURCHASESFREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
  - ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
  - PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
  - CASHADVANCEFREQUENCY : How frequently the cash in advance being paid
  - CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"
  - PURCHASESTRX : Numbe of purchase transactions made
  - CREDITLIMIT : Limit of Credit Card for user
  - PAYMENTS : Amount of Payment done by user
  - MINIMUM_PAYMENTS : Minimum amount of payments made by user
  - PRCFULLPAYMENT : Percent of full payment paid by user
  - TENURE : Tenure of credit card service for user

# Data Processing Approach
Several approach on processing the data
  - Data Describe
  - Data Cleaning
  - Exploratory Data Analysis
  - Outlier Treatment
  - Modelling (KMeans, PCA)
  - Evaluate
  - Insight / Plot
 
 # Clustering
 ![image](https://user-images.githubusercontent.com/92531579/162015537-ca561a90-6dd2-4b85-bf96-16b04e72a35a.png)
 ![clustering](https://user-images.githubusercontent.com/92531579/162014584-b241a614-ff9f-4662-a1d0-9649ac48727e.png)
 
 Into 4 Cluster
 
 ![table cluster](https://user-images.githubusercontent.com/92531579/162015054-1f34a3bd-ca7e-48d0-99a2-03b8a2de0037.PNG)
 

 
  - Cluster 0 = Average Income & Low Spending
  - Cluster 1 = Low Income & High Spending
  - Cluster 2 = High Income & High Spending
  - Cluster 3 = High Income & Low Spending

# Data Understanding
After we know what kind of our customer, we can modify products according to distinct needs and behaviours of the customers. It also helps the business to concerns of different types of customers.

Based on this cluster :
Cluster 0 = customer with average income who have to low spending on their credit card
- This customer may be financialy cautios to spend
- They might used it for their routine essential or small purchase
- Stable customer with predictable pattern, Low Risk of default
- Low profitable in term interest and fee

Cluster 1 = customer with low level income but with high spending on their card
- By their high spending with low income this customer could lead to higher debt and great chance to default on the High Risk status
- Used it on day to day expense
- Targeted financial product such credit debt insurance
- Highly alert on monitoring this cluster

Cluster 2 = customer with high income and had high spending on their card
- Profitable for company due to high transcations volume and potential interest
- Used it for personal or luxury expense
- Targeted for premium card offering with higher limit or exclusive rewards
- On categories Low Risk less likely on default due to high income

  Cluster 3 = with high income but had low spending
  - Potentialy prefer use other form of payment rather relying on credit cards
  - More conservative on debt to maintain low credit
  - Could be opportunities through specific targeted marketing such promoting reward program or incentives for higher usage
  - Monitoring their spending habits to help in design product that encourage more used without breach about their preference for financial security (Insurance)

 By Undestanding these cluster, you can make a strategies marketing, financial products and customer support to meet the needs for each group.
 Targeted offer or personalized communication to enhance satisfaction and retention and monitoring to allow adjust credit policies or product offerings
