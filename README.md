# SSIS Data Flow Transformations

## Overview
This project demonstrates how SSIS can validate data, filter invalid rows, clean text fields, convert data types, and prepare dataset for loading into SQL Server. The package showcases core SSIS transformations such as Lookup, Derived Column, Conditional Split, Merge Join, Script Component, and other commonly used data flow elements.

## Featured in My YouTube Tutorial
This SSIS package is featured in my hands-on tutorial published on my YouTube channel, 
Coffee Break In 10, where I walk through how to build data transformation pipelines using components like Lookup, Derived Column, Aggregate, Conditional Split, and more. The tutorial shows how each transformation contributes to data quality, validation, and routing within an ETL workflow. It also includes actual debugging and error‑fixing sessions, showing how issues surface during execution and how to apply practical fixes.

Watch the tutorial: YouTube Channel - https://www.youtube.com/@CoffeeBreakIn10
- https://www.youtube.com/watch?v=VHyYoiiil5k&t=1s - SSIS Data Transformations: 3 Ways to Clean & Load Data (Part 1 — Data Flow Components)

## Technologies
- SQL Server
- SSIS (ETL)
- SSRS (Reporting)

## Data Flow Components
- Lookup
- Derived Column 
- Conditional Split
- Data Conversion
- Aggregate
- Multicast
- Merge Join
- Script Component
- Sort

## Folder Structure
- /src
-	/ssis        --> ETL packages (DTSX)
-	/sql         --> Stored procedures, schema, queries
- /data        --> Public or sanitized datasets
- /docs        --> diagrams, notes
- /assets      --> Screenshots

## Screenshots
Screenshots are available in `/assets`:
- SSIS Data Flow

## How to Run
1. Import the SSIS package into Visual Studio.
2. Update connection strings to point to your SQL Server instance.
3. Execute the stored procedures in `/src/sql`.
       -> Create_Table_Script.sql
4. Use the SampleCSVData.csv file located in /data as your dataset.

## Sanitization Notice
All connection strings, credentials, and related info have been removed. 
Only public or sample data is included.
This project does not contain any proprietary business logic. All transformations shown are generic ETL patterns.

