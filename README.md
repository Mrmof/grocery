# Grocery - PowerBI
Grocery inventory dataset
## Table of Content
- [Introduction](#introduction)
- [Project Objectives](#projects-objectives)
- [Description of Dataset](#description-of-dataset)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [KPIs](#kpis)
- [Research Questions](#research-questions)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
 

## Description
This project described and evaluated the inventory of a grocery store. It was sourced from Kaggle.com. It comprises of 17 fields (columns) and 572 obeservations (rows). It consisted of 5 unanswered questions meant to give data insights for future decision making.
## Data Cleaning

## Procedures
This analysis was done using powerBI. Each question was answered using Data Analysis Expression (DAX).
Firstly, a date table was created from the date received field. 
my date table = CALENDAR(MIN('Grocery_Inventory new v1'[Date_Received]), MAX('Grocery_Inventory new v1'[Date_Received]))
the table was then marked as a date table and merged on the data model view using a 1-to-* relationship.
Secondly, DAX table was created and various dax measures added.

## Questions and Findings
1. What is the average stock quantity available per product category?
   the average stock quantity was measured using
   Avg Stock Quantity = AVERAGE('Grocery_Inventory new v1'[Stock_Quantity])
<img width="875" height="485" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/b9e6e1d9-08af-4f49-acbb-c556b24d5773" />

3. Which suppliers contribute the most to total product inventory?
4. Which products have the longest shelf life before expiration, and how does that impact sales?
5. Which products are most likely to run out of stock based on last reorder levels? 
6. Can we predict seasonal demand for different product categories based on sales volume trends?
7. What are the optimal reorder levels for high-demand products to prevent stockouts? 

 
