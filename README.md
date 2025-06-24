# DSA2040A_ETL_Midterm_Susan_501
# DSA2040A_ETL_Midterm_Susan_501

# ETL Lab – Sales Data Transformation

# Project Overview
This ETL lab demonstrates a complete Extract, Transform, Load (ETL) pipeline for sales data. The project reads raw and incremental CSV files, cleans and enriches the data, categorizes customers, and loads the transformed results into a database for analysis.

# ETL Phases

Extract: 
  Raw and incremental sales data are loaded from CSV files.

Transform:  
   Handle missing values and remove duplicates  
   Convert data types   
   Drop irrelevant columns and rows   
   Categorize customers into tiers 

  Load: 
  The cleaned and transformed data is loaded into a SQLite database . 

# Tools Used
- SQLite via sqlite3
- Jupyter Notebook / VS Code

# How to Run the Project
After creating a repository on Git hub, open vs code and clone  the repository.
Place your raw data in the data/ folder as raw_data.csv and incremental_data.csv.
Create 'etl_extract.ipynb' file where tou will write the codes for extraction
Then you create transformed folder which will include transformed_full.csv and transformed_incremental.csv
You will create another file etl_transform.ipynb where you will write the codes for transformation. 
Do the same process for loading. You can load the transformed data into SQLite or Parquet, for my case I used SQLite


