## Overview

This project builds an end-to-end analytics platform using Microsoft Fabric, SQL, dbt, and Power BI.

The goal is to transform raw retail transaction data into trusted analytical datasets and business dashboards.

## Technology Stack

- Microsoft Fabric
- SQL
- dbt Core
- Power BI
- GitHub

## Architecture

The platform follows a modern analytics architecture:
Raw Data → Lakehouse → Warehouse → dbt Transformations → Power BI

## Microsoft Fabric Workspace

A dedicated Microsoft Fabric workspace was created to host the retail analytics platform.

The workspace will contain:

- Lakehouse for raw data storage
- Warehouse for analytical modeling
- Power BI reports for business insights

Architecture layers:

Bronze:
Raw data stored in Lakehouse

Silver:
Cleaned and transformed warehouse tables

Gold:
Business-ready star schema models


## Bronze Layer - Lakehouse

The Bronze layer stores raw source data in Microsoft Fabric Lakehouse.

Purpose:

- Preserve original source data
- Provide historical data retention
- Create a reliable foundation for downstream transformations

Technology:
Microsoft Fabric Lakehouse

Object:
lh_retail_sales

The Bronze layer is implemented using Microsoft Fabric Lakehouse.

The purpose of this layer is to store raw source data with minimal transformation.

## Lakehouse

Name:

lh_retail_sales

Responsibilities:
- Store raw retail datasets
- Preserve source data history
- Provide a foundation for downstream transformations

Data Flow:
Source Files → Fabric Lakehouse → Warehouse → dbt Models → Power BI