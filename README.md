# Global-Superstore-Dashboard

"This repository contains a comprehensive data analysis and visualization dashboard for Global Superstore."

# Overview

This Power BI project provides an in-depth analysis of the Global Superstore dataset, highlighting sales transactions, shipping trends, and market performance. The interactive report includes various visualizations designed to offer actionable insights for stakeholders.


# Table of Contents

1. Introduction
2. Data Cleaning Steps
3. Visualization Segmentation
4. Sales Visualizations
5. Shipping Analysis
6. Tables

# 1. Introduction

To get started with the Power BI project:

1. Download the dataset from this link [https://docs.google.com/spreadsheets/d/1zNWOWH3T_KllALPDvWv-Jcqtwz4T9TpQ/edit?gid=1807457842#gid=1807457842].
2. Open the file using Power BI Desktop.
3. Explore the visualizations and tables to uncover insights into sales and shipping patterns.

# 2. Data Cleaning Steps

The dataset underwent basic data cleaning to ensure accuracy and consistency, including:

- Correcting column headers.
- Removing duplicate records.
- Handling null values.

These steps ensure the data is ready for analysis and visualization.

# 3. Visualization Segmentation

The report segments data by:

- Country: Analyze sales trends by nation.
- Region: Compare regional performance.
- Market: Identify key market contributors.

This segmentation helps stakeholders focus on specific geographic and market-based insights.

# 4. Sales Visualizations

Key sales visualizations include:

1. Sales by Region (Map): A geographic map showcasing sales distribution across regions.
2. Sales by City (Stacked Column Chart): A detailed analysis of city-level sales trends.
3. Sales by State (Map): A state-wide sales distribution view using map visualization.
4,Sales by Market (Stacked Bar Chart): Comparative sales performance for different markets.

Each chart helps stakeholders identify high-performing areas and sales trends.

# 5. Shipping Analysis

Shipping Percentage by Ship Mode
This analysis focuses on evaluating the percentage distribution of shipping costs across various ship modes. By leveraging a DAX formula, the report calculates how each shipping mode contributes to the total shipping costs, providing insights into cost efficiency and distribution.

The DAX formula used:DIVIDE(  
    SUM('Orders'[Shipping Cost]),  
    CALCULATE(SUM('Orders'[Shipping Cost]), ALL('Orders'[Ship Mode])))

Purpose: 
- This formula divides the shipping cost of a specific mode by the total shipping cost across all modes, giving a percentage breakdown for each mode.

Insights:
- Helps identify the most cost-effective shipping methods.
- Provides visibility into areas where shipping costs could be optimized.
- Supports stakeholders in refining logistics strategies.

Visual representations such as bar charts or pie charts are used to make these insights actionable and easy to interpret for decision-makers.



# 6. Tables

Tables complement each visualization, summarizing data points for quick reference and comparison.

# Project Outcome

The Power BI project successfully delivers actionable insights from the Global Superstore dataset, specifically in the areas of sales performance, shipping trends, and market analysis. The key outcomes are:

1. In-depth Sales Insights:

- Clear visualizations of sales trends across regions, cities, states, and markets.
- Geographic distribution of sales enables stakeholders to identify high-performing areas and potential market opportunities.
- Regional and market-level comparisons help in tailoring strategies for growth and resource allocation.

2. Shipping Cost Analysis:

- The shipping percentage by mode reveals the relative contribution of each ship mode to total shipping costs, helping stakeholders assess shipping efficiency and cost management strategies.
- Identifies opportunities for optimizing logistics and selecting cost-effective shipping methods.

3. Data-Driven Decision-Making:

- Interactive reports and visualizations empower stakeholders to make informed decisions based on real-time data.
- The clean, well-structured dataset and insightful visualizations enhance the decision-making process across different business areas (sales, logistics, and operations).

4. Improved Business Strategies:

- The project highlights key performance metrics that can guide business decisions in inventory management, customer targeting, and shipping optimizations.
- The insights from the shipping analysis, in particular, offer tangible opportunities for reducing costs and improving efficiency in logistics operations.
