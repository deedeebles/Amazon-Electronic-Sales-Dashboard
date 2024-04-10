# Visualisation and Analysis of Electronic Sales Data Using Tableau

## Summary

This project showcases an extensive analysis of an electronic sales dataset, which was originally obtained from an Amazon R&D department and derived from Walmart outlets. The dataset, titled "Electronic Dataset," encapsulates a wealth of information regarding the sales of various electronic products. Key data points include product types, quantities ordered, prices, and the cities where the sales occurred. The analysis was conducted using Tableau, a powerful tool for creating interactive and shareable dashboards.

## Overview of the Dataset and Initial Setup

The dataset was imported into Tableau as a text file, allowing for a comprehensive overview of the available data. This included detailed information on field names, data types, physical tables, and remote field names. An initial display showcased the structure of the dataset, providing a clear picture of the columns and rows that form the foundation of the analysis.

## Analysis Tasks and Findings

## Task 1: Top and Bottom Product Analysis

A parameter named ‘Top and Bottom N’ was created to filter and display either the top or bottom ten products based on the quantity ordered.
Calculated fields were utilized to rank products and apply conditional filtering, revealing insights into product popularity and sales performance.

## Task 2: Sales Analysis

A sales parameter was defined to distinguish between total and average sales, enriching the analysis with a dynamic perspective on sales performance.
The purchase address column was split to extract city names, which were then geographically categorized to enable spatial analysis of sales across different cities.

## Task 3: Weekly Performance Analysis

Sales data was aggregated by week using the ISO date format, allowing for the observation of sales trends and patterns over time.
A line graph visualized the weekly performance, comparing total and average sales, thus offering a temporal dimension to the sales analysis.

## Task 4: Warranty End Date Calculation

A calculated field named ‘Warranty End Date’ was introduced to estimate the warranty expiration date for each product, adding a layer of post-sale information valuable for customer service and inventory management.

## Task 5: Interactive Dashboard Creation

An interactive dashboard was designed to consolidate the insights from the various tasks into a coherent and interactive visual platform.
The dashboard enables users to delve into the specifics of top and bottom selling products, analyze sales by city and over time, and assess warranty periods, enhancing the understanding of sales dynamics and operational efficiency.

## Conclusion
The analysis of the Electronic Dataset through Tableau unveiled critical insights into sales trends, product popularity, geographic sales distribution, and warranty management. Through this interactive dashboard, strategic planning, marketing, and customer service enhancements can be explored.
