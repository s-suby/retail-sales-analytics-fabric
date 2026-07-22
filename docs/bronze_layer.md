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