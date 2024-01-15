# Amazon-Sales-Analysis

## Overview

The goal of this project is to build an end-to-end ETL (Extract, Transform, Load) data flow using the powerful combination of Snowpark and Snowflake. It will handle Amazon’s mobile sales order data from three region (India/USA/France), starting from its loading stage from a local machine to a Snowflake internal stage. Then dive into the crucial process of data curation using Snowpark Data Frame API, where I have transformed and cleansed the data to ensure its quality and accuracy. Finally, exploring the concept of dimensional modelling, a popular approach for organising data into meaningful structures that facilitate analytical querying and reporting.

I have created simple dashboard using snowsight dashboard along with filters to provide loaded data insight.

## End To End Data Flow Diagram

This end to end data flow diagram depict the mobile sales data where data files are available in 3 different formats.

India Sales Order Data — CSV Format
USA Sales Order Data — Parquet File Format
France Sales Order Data — JSON File Format

## Tech Stack

### **SnowFlake Data Engineering Technologies:** 

  -- SnowFlake

  -- SnowPark

**Language:** Python

**Framework or Library:** Pandas, SnowPark

**Database:** Snow SQL

## Architecture

![Architecture](https://raw.githubusercontent.com/worldOfTheWeb/Amazon-Sales-Analysis-SWF/main/Amazon_sales_analysis.webp)

![SnowFlake Dashboard](https://github.com/worldOfTheWeb/Amazon-Sales-Analysis-SWF/blob/main/Dashboard_Screen.png)
