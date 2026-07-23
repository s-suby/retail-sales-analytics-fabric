# dbt Core Setup and Microsoft Fabric Integration

## Project Overview

This project demonstrates an end-to-end analytics engineering solution using:

- Microsoft Fabric Lakehouse
- dbt Core
- Microsoft Fabric dbt Adapter
- Advanced SQL transformations
- Power BI semantic modelling and reporting

The objective is to transform raw AdventureWorks data into analytics-ready data models following modern data engineering practices.

---

# Why dbt Was Selected

dbt (data build tool) was selected as the transformation framework because it enables:

- SQL-based transformations
- Version-controlled analytics code
- Automated testing
- Documentation generation
- Data lineage tracking
- Modular data modelling

Instead of creating unmanaged SQL scripts, dbt provides an engineering framework for building reliable analytical datasets.

---

# dbt Architecture

The solution architecture:

Developer
|
|
VS Code
|
|
dbt Core
|
|
Fabric Adapter
|
|
Microsoft Fabric Lakehouse
|
|
AdventureWorks Data


---

# Development Environment

Operating System:

Windows 10


Code Editor:

Visual Studio Code

Programming Environment:

Python Virtual Environment


Transformation Framework:

dbt Core


Data Platform:

Microsoft Fabric Lakehouse


---

# Python Virtual Environment

A dedicated Python virtual environment was created to isolate project dependencies.

Benefits:

- Prevents conflicts with system Python packages
- Ensures reproducibility
- Allows controlled package versions

 