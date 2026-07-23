# Bronze Layer - AdventureWorks

## Source System

AdventureWorks2022 SQL Server Database


## Extraction Method

SQL Server tables exported to CSV files.

## Destination

Microsoft Fabric Lakehouse

Lakehouse Name:

lh_retail_sales


## Raw Tables

| Source Table | File Name | Business Purpose |
|---|---|---|
| Sales.Customer | Customer.csv | Customer master data |
| Production.Product | Product.csv | Product details |
| Production.ProductCategory | ProductCategory.csv | Product hierarchy |
| Production.ProductSubcategory | ProductSubcategory.csv | Product grouping |
| Sales.SalesOrderHeader | SalesOrderHeader.csv | Sales transactions |
| Sales.SalesOrderDetail | SalesOrderDetail.csv | Sales line items |
| Person.Address | Address.csv | Customer location |

## Fabric Bronze Layer

Lakehouse:

lh_retail_sales


Storage Location:

Files


Loaded Objects:

- Customer.csv
- Product.csv
- ProductCategory.csv
- ProductSubcategory.csv
- SalesOrderHeader.csv
- SalesOrderDetail.csv
- Address.csv


## Bronze Tables Created

The following Delta tables were created in Microsoft Fabric:

| Bronze Table | Source File |
|---|---|
| bronze_customer | Customer.csv |
| bronze_product | Product.csv |
| bronze_product_category | ProductCategory.csv |
| bronze_product_subcategory | ProductSubcategory.csv |
| bronze_sales_order_header | SalesOrderHeader.csv |
| bronze_sales_order_detail | SalesOrderDetail.csv |
| bronze_address | Address.csv |

Processing:

CSV files were loaded into Microsoft Fabric Lakehouse as Delta tables using Fabric Notebook (PySpark).