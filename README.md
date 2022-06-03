# BigMart-Sales
### PROBLEM STATEMENT 
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store. Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.
### DATA  
* Item_Identifier : Unique product ID  
* Item_Weight : Weight of product 
* Item_Fat_Content : Whether the product is low fat or not  
* Item_Visibility : The % of total display area of all products in a store allocated to the particular product  
* Item_Type : The category to which the product belongs  * Item_MRP : Maximum Retail Price (list price) of the product  
* Outlet_Identifier : Unique store ID  * Outlet_Establishment_Year : The year in which store was established  
* Outlet_Size : The size of the store in terms of ground area covered  
* Outlet_Location_Type : The type of city in which the store is located  
* Outlet_Type : Whether the outlet is just a grocery store or some sort of supermarket 
* Item_Outlet_Sales : Sales of the product in the particular store.

# Conclusion
* The Items bought are more of Low Fat
* "Fruits and vegetables" and "Snack food" are the most sold items in all the stores with all sizes.
* The Item Outles sales are high for both Low Fat and Regular Item types, so its not justified why all the outlets have more low fat products than regular.
* The items with visibility near to zero is rarely purchased by the customers.
* You can see that the number of sales made by the second categore which its Maximum Retail Price(MRP) between **((70, 135]) and ((135,205])** are nearly double the number of sales made by any other category, This means we should increase the most purchased product with this range of Maximum Retail Price(MRP) in all supermarkets.

* Also the mean of the products with MRP more than 200 is high , this is because it has higher price but not because it is purchased a lot.
* The "Outlet_Establishment_Year" has no effect on the sales made by any outlet, as the number of sales made or the mean of all years are nearly the same .
