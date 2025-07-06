# My DSA Data Analysis Capstone Project

## Analysis of Amazon Tech Accessories Dataset: Insights from Pricing, Ratings & Revenue

### Objectives
This project aims to analyze a dataset of tech accessories (primarily charging cables and mobile accessories) listed on Amazon. The primary goals are:
+ To explore how pricing and discount strategies affect potential revenue.
+ To identify top-performing products based on rating, reviews, and sales potential.
+ To generate key performance indicators (KPIs) for decision-making.
+ To provide actionable insights using visualization and summary statistics

### Dataset Overview
+ Source: Provided Excel file (Amazon case study copy-1.xlsx)
+ Primary Sheet Used: amazon dataset
+ Total Records: ~600 products
+ Fields Included:
  + Product ID
  + Product Name
  + Category, Subcategory, Product Type
  + Discounted Price, Actual Price
  + Price Range Bucket (Low, Middle, High)
  + Discount Percentage
  + Rating and Rating Count
  + Review IDs
  + Potential Revenue

### Data Cleaning
Performed the following data cleaning operations:
+ Removed rows with missing values in key fields such as discount_percentage, Potential revenue, rating, and rating_count.
+ Standardized the price range bucket into "low", "middle", and "high" ranges.
+ Dropped irrelevant columns like Unnamed: 14–16.
+ Ensured numerical formatting for all financial and percentage fields

### KPIs Genrated
1. Total Products
2. Total Potential Revenue
3. Average Rating
4. % Products with Discount >50% or more
5. % Products Rated
6. Top 5 Products Revenue Share

### Key Insights
#### Discounting Drives Revenue
* High-range products with heavy discounts (>= 50%) generate strong revenue.
* Discounting appears to be an effective strategy to drive volume.
#### Middle-Price Range Dominance
+ Majority of products fall into the middle range (₹200 - ₹500), suggesting it is the most competitive and profitable segment.
#### Ratings Matter
+ Products with higher ratings (>= 4.0) and large review counts dominate the top revenue spots.
+ Customer satisfaction and social proof directly correlate with revenue potential.
#### Pareto Principle Observed
+ Top 5 products account for over 35% of total revenue.
+ A small number of listings are responsible for a disproportionate share of returns.

### Visualization
+ Discount % vs. Potential Revenue: Shows high-discount items often yield high revenue.
+ Rating vs. Rating Count: Reveals top-rated products have significant user engagement.
+ Price Range Distribution: Highlights the dominance of middle and high-range products.
+ Discount % Distribution: Skews toward 50%+ discounting, validating the price strategy.

### Diliverables
Cleaned Excel file with:
+ Cleaned Data
+ Top 5 Products
+ KPIs
+ Dashboard Charts

### Conclusion and Recommendation
+ Use high discounting selectively on premium products to maximize conversion.
+ Increase visibility and stock for the top 5 performing products.
+ Enhance product quality and marketing in the middle price range.
+ Identify low-rated, low-revenue products for possible delisting or improvement.

