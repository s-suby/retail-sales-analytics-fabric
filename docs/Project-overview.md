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