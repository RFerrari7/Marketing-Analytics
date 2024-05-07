# Marketing Analytics Project

This repository contains a project developed as part of *Marketing Analytics* course of the [Master's degree in Data Science](https://www.unimib.it/graduate/data-science),
University of Milano Bicocca.

## Description

This project aims to obtain a deeper understanding about consumer behaviour by taking advantage of different datasets, which contain information about customers, orders, products,
 customers reviews and more.
Four main marketing analytics techniques have been implemented to reach this goal:
* **RFM model**: this model aims to compute a score for each customer, the so called 'RFM score', through the analysis of three values, i.e. Recency (time passed from last purchase),
   Frequency (number of purchases in a given time period) and Monetary (total amount spent); a valuable customer is represented by a high RFM score.
* **Churn analysis and model**: this method is used to determine which customer is likely to abandon the company, or some of its products/services; a model has been developed to
  help predict customer churn.
* **MBA**: Market Basket Analysis is a marketing technique that aims to predict the associations between products, i.e. the customer's 'basket'; it is particuralry useful to understand
  which goods tend to get buyed togheter, so the company can better its product placement or suggests more specific products and discounts to each customer, enriching its profyling.
* **Sentiment Analysis**: it's a method used to analyze the sentiment expressed by the cusotmers, usually through reviews and feedbacks, in order to understand how the customer base
 of a company perceives a product/service.

## Repository structure

This repository is structured as follows:

```
.
├── MA data                        # data used for the analysis
│   ├── tbl_addresses.csv           # contains info on address corresponding to a customer account
│   ├── tbl_customer_accounts.csv   # contains info on the loyalty account associated to the customers
│   ├── tbl_customer_reviews.csv    # contains the reviews made by the customers
│   ├── tbl_customers.csv           # contains info on the customers
│   ├── tbl_labelled_reviews.csv    # contains a set of review texts with the sentiment labels assigned (ground-truth)
│   ├── tbl_orders.csv              # contains all the orders made by the customers, i.e. all the products purchased or refunded
│   └── tbl_products.csv            # contains info on the products
├── MA notebooks                   # notebooks containing the source code
│   ├── 1.Preprocessing.ipynb       # preprocessing operations
│   ├── 2.EDA.ipynb                 # exploratory data analysis
│   ├── 3.RFM+Churn+MBA.ipynb       # implementation of the methods descrpited before
│   ├── 4.Sentiment analysis.ipynb  # sentiment analysis conducted with BERT
│   └── 5.Extra Point 1+2.ipynb     # sentiment analysis with Doc2Vec and an integration of RFM and MBA
├── README.md
└── presentation.pdf                # slides presenting the results obatained and the marketing strategies developed
```

All the necessary packages are listed at the beginning of every notebook. 


