# Customer-Personality-Analysis
![GitHub repo size](https://img.shields.io/github/repo-size/Gbolahan-Aziz/Customer-Personality-Analysis)

This project involves using clustering alogrithm to cluster customer into segments, using the segments to better understand the customer.
This way the company can target the right customers when advertising available or new products
# Approach to solving this problem
- Data cleaning and wrangling
- Exploratory Data analysis
- Feature Selection and Engineering
- Clustering Model Building
- Model Testing
- Conclusion and Observation
# Dataset
This dataset was gotten from Kaggle and can be accessed via https://www.kaggle.com/imakash3011/customer-personality-analysis


# Attributes

## People
- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise

## Products

- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years

## Promotion

- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

## Place

- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to company’s website in the last month

# Target
- Need to perform clustering to summarize customer segments.

# Acknowledgement
The dataset for this project is provided by Dr. Omar Romero-Hernandez.
