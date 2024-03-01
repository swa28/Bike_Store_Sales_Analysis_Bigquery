# - Bike_Store_Sales_Analysis_Bigquery

## - We have been assigned to analyse the bike store sales using BigQuery.
## -  We have 9 relational tables having distinct primary keys and foreign keys. 


## Among the tables, 'orders' is a fact table where all other tables are dimensional and sub-dimensional. 

## First, we must create the dataset in the BigQuery project and upload all the tables.

### Now let's first explore all the tables.

-- brands

SELECT * 
FROM bike-store-sql-project.1.brands;

