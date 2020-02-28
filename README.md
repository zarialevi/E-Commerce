# E-Commerce Price Predictions

## Project Scope
E-Commerce data is used to for sales forecasting.

Sales forecasting is the process of estimating future sales, using past data. Accurate sales forecasts enable companies to make informed business decisions and predict short-term and long-term performance.

Insigihts are also given on trends seen in the data, and suggestions made about where further data collection may reveal further patterns in the data.

The data was provided by O-List Store, Brazil's largest E-Commerce Store. We have access to their Marketplace data, where Olist connects customers with small businesses from all over Brazil. Sellers use the platform to sell directly to customers, and ship to the customers using Olist logistics partners.

This project aims to provide a reliable way of handling sales and sales forecasting using linear regression model to forecast sales for an E-Commerce market place.

## Summary of Repository Files
- README.md  
- EDA_Enginering.ipynb
A walkthrough of all data cleaning and exploritory analysis.
- Price_Predictions.ipynb
Building our regression model, and extracting useful information about our data.

## Data
With access to data from 2016 - 2018, we have data on over 90,000 orders, anonymized for confidentiality. We have information on the products, customers and sellers, as well as the reviews left. 

## Model Selection

It was deemed appropriate to use a Linear Regression model for this task. This means we can give predictions on future sales through the Marketplace, and give insight on which factors impact this the most. Our model gave us an R-Squared value of * once validated, and could be further improved with more data.

# Results

The model found the coefficients with the most positive impact were as follows:

![top_coeffs] (top_coefs.png)

Using this, we can give insights to Olist and their independent sellers about what factors have the most impact on sales.