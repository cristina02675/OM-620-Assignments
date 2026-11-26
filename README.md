# OM-620-Assignments
Assignments completed in OM 620 course. In this project we use Python, Pandas, NumPy, SciPy and Jupyter Notebooks to turn transaction data into safety stock recommendation for the products. 

Project Overview 
We decide how much extra inventory to keep for the products so the company does not run out. The data has 3 years of transaction data from 2023-2025:

# Assignment 1 
In assignment 1 there was a focus on preparing and exploring the inventory dataset. Data formatting and cleaning, identifying and addressing any missing values and extracting country information. We used Python coding and Pandas in our Jupyter Notebooks to work on our data and create these insights.

- We re-named columns to match the metadata. 

-Corrected any data-entry errors i.e. lead times with extra zeros or negative unit prices and negative quantities. 

- Handled missing values in five columns with "unknown".

- Extracted the country of manufacture from the Site ID.

- Filtered to finished goods that are made to stock, the products safety stock applies to and calculated value for each order. 

# Assignment 2 
In assignment 2 focused on inventory management and safety stock analysis. We did more transaction data transformation and calculating the safety stock levels and analyzing safety stock across SKUs. 

- Summed the demand per SKU
  
- Calculated safety stock

-Found the SKUs with the largest and smallest safety stock 

-Tested the formula's normal distribution assumption against a non-parametric method based on empirical quantiles. 


  
