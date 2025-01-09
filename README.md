# DMart-Sales-Analysis

## Project Overview
The DMart Sales Analysis Project aims to analyze and predict sales for a large retail chain, BigMart, using historical sales data collected from 2013. The dataset includes sales information for 1559 different products across 10 stores.

## Dataset
The dataset consists of sales data for the year 2013 and includes the following key elements:
- **Products**: 1559 different products with various attributes such as product ID, category, MRP, etc.
- **Stores**: 10 stores located in different cities, each with attributes such as store ID, location, type, and size.
- **Sales Data**: Sales figures for each product at each store.
- **Additional Attributes**: Various other attributes that could affect sales, such as store visibility, product weight, etc.

## Data Characteristics
- **Missing Values**: Some data entries may be incomplete due to technical glitches or non-reporting by some stores. The missing values are handled by taking the mean for Item Weight and the mode for Outlet Size in the test dataset.
- **Feature Types**: Includes numerical features (e.g., MRP, sales) and categorical features (e.g., product category, store type).
