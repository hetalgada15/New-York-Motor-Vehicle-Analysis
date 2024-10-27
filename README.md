# NYC Motor Vehicle Collisions Analysis


## Project Overview

This project involves analyzing motor vehicle collision data from New York City using a variety of data processing and visualization tools. The dataset contains detailed records of collisions, and the objective is to profile, cleanse, model, and visualize this data to derive insights and answer key business questions.

## Dataset

- **Source**: [NYC Open Data - Motor Vehicle Collisions (Crashes)](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data)
- **Size**: 1.25 million rows
- **Description**: This dataset contains details about motor vehicle collisions in New York City, including date, time, location, and contributing factors.

## Project Steps

### 1. Perform Data Profiling
- **Tool**: Alteryx
- **Description**: Performed data profiling to understand the structure, quality, and statistical properties of the dataset. Identified and addressed data quality issues to ensure accurate analysis.

### 2. Load Data into Staging Tables
- **Tool**: Talend
- **Description**: Implemented an ETL pipeline to load and transform data from the source into staging tables, enabling efficient data processing.

### 3. Create a Preliminary Dimensional Model
- **Tool**: ER Studio
- **Description**: Created a preliminary dimensional model using snowflake schema design. Listed facts and dimensions, mapped stage table columns to the proposed dimensional model, and created a data model diagram.

### 4. Load Data from STG Tables to Dimensional Model & Perform Data Cleansing
- **Tool**: Talend
- **Description**: Loaded data from staging tables to the dimensional model and performed data cleansing. Documented cleansing tasks and results.

### 5. Query Integration Schema to Answer Business Questions
- **Tools**: SQL, Tableau, Power BI
- **Description**: Queried the integration schema to answer business questions. Created interactive dashboards to visualize data and support business-driven decisions.

## Business Questions Addressed

1. What are the most common contributing factors to motor vehicle collisions?
2. Which locations in NYC have the highest number of collisions?
3. What time of day do most collisions occur?
4. How have collision trends changed over time?

## Tools Used

- **Alteryx**: Data profiling and cleansing
- **Talend**: ETL pipeline for data loading and transformation
- **ER Studio**: Dimensional modeling
- **SQL**: Querying integration schema
- **Tableau & Power BI**: Data visualization and dashboard creation
