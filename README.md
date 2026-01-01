# AMAZON_SALES_EDA

**Project Overview**

This project performs Exploratory Data Analysis (EDA) on an Amazon e-commerce sales dataset to understand sales performance, customer purchasing behavior, product demand, promotional impact, and temporal trends.
The analysis focuses on data cleaning, feature engineering, visualization, and business insight generation to support data-driven decision making.

## Dataset
*Source: Kaggle — Amazon E-Commerce Sales Dataset
*Type: Transactional e-commerce sales data
*Time Period Covered: **March to June**

Granularity: Order-level transactions

## Tools & Technologies
*Python
*Pandas — data manipulation & cleaning
*Matplotlib & Seaborn — data visualization
*Jupyter Notebook

## Analysis Workflow
## 1.Data Understanding & Cleaning:
* Loaded and inspected raw sales data
* Handled missing values and incorrect data types
* Removed irrelevant and duplicate columns
* Created new time-based features (Month, Year)
* Generated binary flags (e.g., promotion applied)

## 2️.Exploratory Data Analysis (EDA)
**Univariate Analysis**
* Order status distribution
* Order amount distribution & outlier detection
* Quantity distribution
* Product category distribution

**Bivariate Analysis**
* Order amount vs order status
* Order amount vs promotion applied
* Product category distribution across top shipping states

**Time-Based Analysis**
* Monthly order volume trend
* Monthly revenue trend
**Note**: Time-based analysis is limited to the available months in the dataset and does not represent a full annual trend.

## 3.Key Insights
* Most orders are successfully shipped and delivered, indicating efficient fulfillment operations.
* Order amounts are right-skewed, with a small number of high-value orders contributing disproportionately to revenue.
* Customer behavior is dominated by single-item purchases.
* Set and Kurta categories consistently drive the highest order volumes across regions.
* Orders with promotions applied show a slightly higher median order value, though high-value purchases also occur without promotions.
* Regional analysis reveals state-level variation in product category demand.
* A sharp spike in orders and revenue occurs in April, followed by a gradual decline in subsequent months.

## 4.Business Recommendations
* Prioritize inventory and marketing for high-performing categories (Set, Kurta).
* Use targeted promotional campaigns during peak demand periods to maximize revenue.
* Optimize state-level inventory allocation based on regional demand patterns.
* Monitor cancellation behavior to improve customer conversion and experience.
* Extend analysis over a longer time horizon to better capture seasonality.
