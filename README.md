# OM-620-Assignments
Assignments completed in OM 620 course. In this project we use Python, Pandas, NumPy, SciPy and Jupyter Notebooks to turn transaction data into safety stock recommendation for the products. 

## Project Overview 
We decide how much extra inventory to keep for the products so the company does not run out. The data has 3 years of transaction data from 2023-2025:

# Assignment 1 
In assignment 1 there was a focus on preparing and exploring the inventory dataset. Data formatting and cleaning, identifying and addressing any missing values and extracting country information. We used Python coding and Pandas in our Jupyter Notebooks to work on our data and create these insights.

- We re-named columns to match the metadata. 

- Corrected any data-entry errors i.e. lead times with extra zeros or negative unit prices and negative quantities. 

- Handled missing values in five columns with "unknown".

- Extracted the country of manufacture from the Site ID.

- Filtered to finished goods that are made to stock, the products safety stock applies to and calculated value for each order. 

# Assignment 2 
In assignment 2 focused on inventory management and safety stock analysis. We did more transaction data transformation and calculating the safety stock levels and analyzing safety stock across SKUs. 

- Summed the demand per SKU
  
- Calculated safety stock

- Found the SKUs with the largest and smallest safety stock 

- Tested the formula's normal distribution assumption against a non-parametric method based on empirical quantiles. 

## Key Findings 

- The cleaned data has 760,460 transactions. After filtering through the finished goods, we had 360 SKUs to work with.

- Going from a 75% to a 95% service level doubles the safety stock.

- Canada is the largest manufacturing country which is followed by Japan, United States and Poland. 

- At a 95% service level, safety stock ranges from 35 units to 347 units.

## Repository Structure 
OM-620-Assignments/
├── README.md
├── data/
│   ├── meta_data.csv 

│   └── transaction_data.zip     
└── notebooks/
    └── 620_assignments_combined.ipynb   
    
## How to Run 
1. Download or clone this repository.
2. Open notebooks/620_assignments_combined.ipynb in Jupyter or VS Code
3. Run all cells from top to bottom. The notebook will read the data from data/transaction_data.zip


  
