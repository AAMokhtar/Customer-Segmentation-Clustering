<h1 style="font-size:200%"> <center> Supermarket Customer Segementation</center></h1>

---

<img src="https://www.segmentify.com/wp-content/uploads/2021/08/Top-Customer-Segmentation-Examples-every-Marketer-Needs-to-Know.png" width="100%">

# Introduction

Ad spend waste is major problem facing all businesses. In 2021 alone, [US$3 billion of ad spend was wasted](https://www.contentgrip.com/digital-advertisers-waste/#:~:text=In%202021%2C%20Next%26Co%20reported%20that,producing%20high%2Dquality%20branded%20content.). One of the major contributors to this waste is the mistake of targeting the wrong audience. An ad campaign's goal is to grab the attention of as many customers as possible. Therefore, it should be marketed towards the group that is most likely to buy the product. In turn, bringing more revenue.

# About This Project 

In this project, we will explore the data collected by a supermarket about its cutomers. We will get some statistics about the general customers of the supermarket and their habits. Then we will attempt to divide the customers into segments using various clustering techniques. We will try to evaluate the clustering using some popular metrics. However, we will have to delve deep into the cluster in order to assess the correctness of the clustering algorithm. 

In the end of the project we would have a statistical description of the various customer segments and their spending habits. The supermarket can then utilize those segments in order to market their products better.

# About the Dataset

The [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) dataset contains a description of the ideal customers of a company. It contains 29 columns detailing the habits and demographic of the customer. The features are divided into 5 categories

<h2 style="font-size:100%"> People:</h2>

| # | Feature | Description
| --- | --- | --- 
| 1 | ID | Customer's unique identifier
| 2 | Year_Birth | Customer's birth year
| 3 | Education | Customer's education level
| 4 | Marital_Status | Customer's marital status
| 5 | Income | Customer's yearly household income
| 6 | Kidhome | Number of children in customer's household
| 7 | Teenhome | Number of teenagers in customer's household
| 8 | Dt_Customer | Date of customer's enrollment with the company
| 9 | Recency | Number of days since customer's last purchase
| 10 | Complain | 1 if the customer complained in the last 2 years, 0 otherwise

<h2 style="font-size:100%"> Products:</h2>

| # | Feature | Description
| --- | --- | --- 
| 11 | MntWines | Amount spent on wine in last 2 years
| 12 | MntFruits | Amount spent on fruits in last 2 years
| 13 | MntMeatProducts | Amount spent on meat in last 2 years
| 14 | MntFishProducts | Amount spent on fish in last 2 years
| 15 | MntSweetProducts | Amount spent on sweets in last 2 years
| 16 | MntGoldProds | Amount spent on gold in last 2 years

<h2 style="font-size:100%"> Promotion:</h2>

| # | Feature | Description
| --- | --- | --- 
| 17 | NumDealsPurchases | Number of purchases made with a discount
| 18 | AcceptedCmp1 | 1 if customer accepted the offer in the 1st campaign, 0 otherwise
| 19 | AcceptedCmp2 | 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
| 20 | AcceptedCmp3 | 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
| 21 | AcceptedCmp4 | 1 if customer accepted the offer in the 4th campaign, 0 otherwise
| 22 | AcceptedCmp5 | 1 if customer accepted the offer in the 5th campaign, 0 otherwise
| 23 | Response | 1 if customer accepted the offer in the last campaign, 0 otherwise

<h2 style="font-size:100%"> Place:</h2>

| # | Feature | Description
| --- | --- | --- 
| 24 | NumWebPurchases | Number of purchases made through the company’s website
| 25 | NumCatalogPurchases | Number of purchases made using a catalogue
| 26 | NumStorePurchases | Number of purchases made directly in stores
| 27 | NumWebVisitsMonth | Number of visits to company’s website in the last month

<h2 style="font-size:100%"> Uncategorized:</h2>

| # | Feature | Description
| --- | --- | --- 
| 28 | Z_CostContact | -
| 29 | Z_Revenue | -
