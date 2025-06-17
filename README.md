# Amazon's Product Report
Prepared by: Emeka Kingsley
Date: May 26, 2025

## Executive Summary
This report presents an in-depth analysis of an Amazon product data-set to uncover trends in product ratings, sales performance, and revenue distribution across categories. The goal is to provide data-driven insights into customer engagement and product performance using Power BI dashboards and visuals.

## Dataset Used:
https://www.kaggle.com/datasets/asaniczka/amazon-products-dataset-2023-1-4m-products Dataset

## Project Overview
Purpose: To understand patterns in product sales, extract insights, and visualize key performance indicators (KPIs).

## Business Questions Explored:
What are the top-rated products?

What is the total revenue generated?

Are there notable differences between best sellers and non-best sellers?

Which product category generated the highest revenue?

What are the top best-selling products?

### Approach:
This was an exploratory project designed to assess product performance and gain insights using ratings, sales volume, and revenue as key metrics.

## Data Summary
### Data Source:
Amazon dataset from Kaggle.
### Tables Used:
Category Table
Products Table
### Data Preparation:
Utilized ~70% of records.

Performed data cleaning in Power Query.

Renamed column headers.

Handled 7% missing values in the Price column using column average.

Eliminated duplicates manually.

Joined both tables using category_id as the primary key.

Created new calculated columns and DAX measures to support insights.

## Report Pages and Visuals
I.Total Revenue

Visual: Card

Insight: Total revenue generated across the data-set was $4.65 billion.

ii. Amount of Product Sold
Visual: Card
Insight: 203 million products were sold in total.
iii. Top Rated Products
Visual: Stacked Column Chart
Insight: The HD Roku Streaming Device had the highest average rating of 4.7.
iv. Review-to-Sales Ratio by Product Title
Visual: Stacked Bar Chart
Insight: Highlights customer engagement relative to sales performance.
v. Average Ratings by Best Seller Status
Visual: Clustered Column Chart
Insight: Compared customer satisfaction across best sellers vs. non-best sellers.
vi. Total Revenue by Product Category
Visual: Line Chart
Insight: "Kitchen and Dining" category generated the highest revenue (~$267 million).
vii. Top 10 Best Selling Products
Visual: Clustered Bar Chart
Insight: Neutrogena Cleansing Fragrance was the best-selling product.
viii. Best Seller Filter
Visual: Slicer
Used to toggle views between best sellers and non-best sellers.

