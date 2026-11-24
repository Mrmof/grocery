# Grocery - PowerBI

## Table of Content
- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Description of Dataset](#description-of-dataset)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [KPIs](#kpis)
- [Research Questions](#research-questions)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
 
## Introduction
This project described and evaluated the inventory of a grocery store.

## Project Objectives
This project is intended to provide insights into the inventory of a grocery store, as a means to influence future decision-making.

## Description of Dataset
The dataset was sourced from Kaggle.com. It comprises of 17 fields (columns) and 572 obeservations (rows). It consisted of 5 unanswered questions meant to give data insights for future decision making.

##Tools
This project was carried out using PowerBi as the analytic tool.

## Data Cleaning
Data cleaning was done using power-query. It involved the removal of irrelevant columns, replacement of missing values and setup of columns to their appropriate data-types.

## KPIs
Average Sales Volume
Total Number of Suppliers
Max Date Recieved
Total Stock Quantity
Total Sales Volume
my date table *CALENDAR(MIN('Grocery_Inventory new v1'[Date_Received]), MAX('Grocery_Inventory new v1'[Date_Received]))*

## Research Questions
1. What is the average stock quantity available per product category?
2. Which suppliers contribute the most to total product inventory?
3. Which products have the longest shelf life before expiration, and how does that impact sales?
4. Which products are most likely to run out of stock based on last reorder levels? 
5. Can we predict seasonal demand for different product categories based on sales volume trends?
6. What are the optimal reorder levels for high-demand products to prevent stockouts? 

## Key Findings
1. The average stock quantity ranges from 50.86 to 62.23 (Grains & Pulses - Seafood).
   
2. Katz, Twitterwire, Meevee, Quatz and Feedfire contributed the most to product inventory.
   
3. The products with the longest shelf-life are Garlic, Banana, Rice Flour.

4. The following products are most likely to run out of stock based on last reorder level.
   Rice flour, coconut, raw sugar, evapourated milk amongst others.

5. The seasonal demand for different product categories is expected to be between 528 and -259. This indicates that a drop in demand would reduce sales by 259. 

6. The optimal reorder level is 50% of the current reorder level. 

## Recommendations
- Reorder quantity should be increased by 50% of the current reorder level.

## Conclusion
