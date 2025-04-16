In today’s digital age, large retail stores and shopping centers like malls and marts routinely collect sales data as a crucial step toward forecasting future demand. This helps them make smarter decisions about inventory management. Understanding how different features of a product or store influence sales is essential for success in the retail industry.

At BigMart, data scientists have gathered sales data from the year 2013, covering 1,559 products sold across 10 different stores located in various cities. Along with sales figures, the dataset also includes specific details about each product and store. Using this information, the goal is to… [continue your purpose here, e.g., "build a predictive model for sales"]**BigMart is trying to understand the properties of products and stores which play a key role in increasing sales**.

-----------------------------
## **Objective** 
-----------------------------

To build a predictive model that can find out the sales of each product at a particular store and then provide actionable recommendations to the BigMart sales team to understand the properties of products and stores which play a key role in increasing sales.

-----------------------------
## **Dataset** 
-----------------------------

- Item_Identifier : Unique product ID

- Item_Weight : Weight of the product

- Item_Fat_Content : Whether the product is low fat or not

- Item_Visibility : The % of the total display area of all products in a store allocated to the particular product

- Item_Type : The category to which the product belongs

- Item_MRP : Maximum Retail Price (list price) of the product

- Outlet_Identifier : Unique store ID

- Outlet_Establishment_Year : The year in which the store was established

- Outlet_Size : The size of the store in terms of ground area covered

- Outlet_Location_Type : The type of city in which the store is located

- Outlet_Type : Whether the outlet is just a grocery store or some sort of supermarket

- Item_Outlet_Sales : Sales of the product in the particular store. This is the outcome variable to be predicted.

We have two datasets - train (8523) and test (5681) data. The training dataset has both input and output variable(s). You will need to predict the sales for the test dataset.

Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly.
