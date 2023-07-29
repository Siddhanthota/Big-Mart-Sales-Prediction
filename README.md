# Big Mart Sales Prediction
The aim is to build a predictive model and find out the sales of each product at a particular store. Create a model by which Big Mart can analyse and predict the outlet production sales.

# Dataset
The data-set is also based on hypotheses of store level and product level. Where store level involves attributes like:- city, population density, store capacity, location, etc and the product level hypotheses involves attributes like:- brand, advertisement, promotional offer, etc.

[Link to Dataset](https://www.kaggle.com/datasets/aakash2016/big-mart-sales-dataset?select=Train_UWu5bXk.csv)

## Variable-Details
- Item_Identifier- Unique product ID
- Item_Weight- Weight of product
- Item_Fat_Content - Whether the product is low fat or not
- Item_Visibility - The % of total display area of all products in a store allocated to the particular product
- Item_Type - The category to which the product belongs
- Item_MRP - Maximum Retail Price (list price) of the product
- Outlet_Identifier - Unique store ID
- Outlet_Establishment_Year- The year in which store was established
- Outlet_Size - The size of the store in terms of ground area covered
- Outlet_Location_Type- The type of city in which the store is located
- Outlet_Type- Whether the outlet is just a grocery store or some sort of supermarket
- Item_Outlet_Sales - Sales of the product in the particulat store. This is the outcome variable to be predicted.

# Project Flow
1. Loading Packages and Data
2. Data Structure and Content
3. Exploratory Data Analysis
4. Missing Value Treatment
5. Feature Engineering
6. Encoding Categorical Variables
7. Label Encoding
8. PreProcessing Data
9. Modeling
10. Linear Regression
11. RandomForest Regressor
12. XGBoost
13. Deployment
