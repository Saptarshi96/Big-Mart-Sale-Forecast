# Big-Mart-Sale-Forecast
A model to predict the sales of a specific item found at a particular supermarket outlet. 

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet. 

Following features are present.

Item_Identifier: Unique product ID
Item_Weight: Weight of product
ItemFatContent: Whether the product is low fat or not
Item_Visibility: The % of total display area of all products in a store allocated to the particular product
Item_Type: The category to which the product belongs
Item_MRP: Maximum Retail Price (list price) of the product
Outlet_Identifier: Unique store ID
OutletEstablishmentYear: The year in which store was established
Outlet_Size: The size of the store in terms of ground area covered
OutletLocationType: The type of city in which the store is located
Outlet_Type: Whether the outlet is just a grocery store or some sort of supermarket
ItemOutletSales: Sales of the product in the particular store. This is the outcome variable to be predicted.

An exploratory analysis of the data has been performed. 
Feature engineering has been conducted so as to handle categorical variables through the means of ordinal encoding and one-hot encoding.
The missing values have been handled through KNN Imputation. 
The best variables for the purposes of prediction are selected through SelectKBest algorithm. 
A linear regression model has been applied to the data to predict the sales of a particular item in a particular supermarket outlet. 
The findings have been explained in the business context so as to help the business team of BigMart. 


