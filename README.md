# customer-shopping-behaviour
This end-to-end analytics project analyzes 3,900 customer transactions to uncover insights into purchasing behavior, customer segmentation, discount impact, and revenue drivers.

### The objective was to help a retail company answer the strategic question:
How can consumer shopping data be leveraged to improve customer engagement, optimize marketing strategies, and increase revenue?

## The project integrates:
-  Data Cleaning & Feature Engineering (Python)
-  Structured Business Analysis (PostgreSQL)
-  Interactive Visualization (Power BI)
-  Strategic Business Recommendations

## Business Problem

A leading retail company observed changes in:
-  Purchasing patterns
-  Discount usage behavior
-  Product preferences
-  Subscription trends
-  Online vs Offline engagement

Management needed a data-driven solution to:
-  Identify key revenue drivers
-  Improve customer loyalty
-  Optimize discount strategy
-  Enhance targeted marketing campaigns

## Dataset Overview
-  Total Transactions: 3,900
-  Total Columns: 18
-  Missing Values: 37 (Review Rating column)
-  Key Data Features
-  Customer Information
-  Age
-  Gender
-  Location
-  Subscription Status
-  Purchase Information
-  Item Purchased
-  Category
-  Purchase Amount
-  Season
-  Size
-  Color
-  Behavioral Data
-  Discount Applied
-  Promo Code Used
-  Previous Purchases
-  Frequency of Purchases
-  Review Rating
-  Shipping Type

## Phase 1: Data Preparation (Python)
### Data Cleaning
-  Handled missing values using median imputation by category
-  Standardized column names to snake_case
-  Removed redundant columns (promo_code_used)

### Feature Engineering
-  Created age_group using binning
-  Derived purchase_frequency_days
-  Verified data consistency across discount variables

### Database Integration
-  Connected to PostgreSQL
-  Loaded cleaned dataset into relational database
-  Structured data for advanced SQL querying

## Phase 2: Business Analysis (SQL)

-  Performed structured analysis to answer strategic questions:
-  Revenue Insights
  -  Revenue by Gender
  -  Revenue by Age Group
  -  Revenue by Gender
  -  Subscriber vs Non-Subscriber revenue comparison  

-  Customer Segmentation
  -  Classified customers as:
    -  New
    -  Returning
    -  Loyal
  -  Identified repeat buyers and subscription likelihood
-  Discount Analysis
  -  High-spending discount users
  -  Discount-dependent products
  -  Impact of discounts on purchase amount
-  Product Performance
  -  Top 5 products by review rating
  -  Top 3 products per category
  -  Category-level performance trends
-  Operational Insights
  -  Shipping type comparison (Standard vs Express)
  -  Subscription behavior analysis

## Phase 3: Power BI Dashboard
An interactive dashboard was developed to provide stakeholders with:
-  Revenue breakdown by demographics
-  Product performance insights
-  Discount impact visualization
-  Subscription vs non-subscription analysis
-  Customer segmentation summary
Key Features
-  Dynamic filtering
-  Drill-down capability
-  KPI tracking
-  Business-focused storytelling

## Key Insights
-  Subscribers generate higher average revenue.
-  Loyal customers significantly contribute to total sales.
-  Certain products are heavily discount-dependent.
-  Express shipping users show higher average purchase value.
-  Specific age groups drive the majority of revenue.

## Business Recommendations
-  Promote subscription benefits to increase retention.
-  Launch loyalty programs for repeat buyers.
-  Optimize discount policies to balance margin and volume.
-  Highlight top-rated products in marketing campaigns.
-  Target high-revenue age groups with personalized offers.

## Technical Skills Demonstrated
-  Data Cleaning & Transformation (Pandas)
-  Feature Engineering
-  SQL Query Optimization
-  Customer Segmentation Logic
-  Business KPI Development
-  Data Modeling Concepts
-  Interactive Dashboard Design
-  Analytical Storytelling

## Business Impact
This project enables the company to:
-  Improve customer engagement strategies
-  Identify profitable customer segments
-  Optimize discount-driven revenue
-  Make informed product and marketing decisions

## Project Structure
 ### Customer-Shopping-Behavior-Analysis
 - Python Scripts
 - SQL Queries
 - Power BI Dashboard (.pbix)
 - Business Report
 - Presentation Slides

 ## Author

Tarun Yadav
Data Analyst | Business Intelligence Enthusiast

 India
 Focus Areas: Customer Analytics | Retail Intelligence | Data-Driven Strategy

