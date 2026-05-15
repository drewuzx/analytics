# Retail Sales Analytics Project Documentation

## 1\. Dataset Overview

The dataset contains 120000 rows and 17 columns.

Columns included in the dataset:

- transaction_id
- date_id
- transaction_date
- month
- customer_id
- customer_gender
- customer_age_group
- customer_segment
- product_id
- product_name
- category
- brand
- quantity
- unit_price
- discount_pct
- sales_amount
- payment_method
- sales_channel
- region_id
- region

**2\. Data Cleaning Process**

**Missing Values Check**

The dataset was checked for missing or null values using data validation techniques. No missing values were identified in the dataset.

**Duplicate Records Check**

The dataset was inspected for duplicate values, particularly in the customer_id and product_id columns. These duplicates were expected because multiple transactions can be associated with the same customer and product.

**Consistency Check**

The dataset was reviewed for formatting inconsistencies, particularly in the transaction_date column. The date format was standardized to ensure consistency and compatibility with Power BI time-based analysis.

## Data Transformation

## Additional transformations were performed to prepare the dataset for Power BI visualization and analytics. This included creating derived columns such as date_id, month, and region_id to support data modeling, filtering, and time-based analysis

## 3\. Dashboard Visualizations

| Visualization                         | Columns Used                      |
| ------------------------------------- | --------------------------------- |
| KPI Card                              | sales_amount                      |
| Sales Trend Line Chart                | transaction_date + sales_amount   |
| Sales by Category Bar Chart           | category + sales_amount           |
| Sales by Region Bar Chart             | region + sales_amount             |
| Sales by Customer Segment Donut Chart | customer_segment + sales_amount   |
| Sales by Customer Age Column Chart    | customer_age_group + sales_amount |

## 4\. Insights and Recommendations

• Electronics and high-demand categories can be prioritized for marketing.

• Regional sales trends may help optimize inventory allocation.

• Payment method analysis can improve customer purchasing convenience.

• Customer segmentation can support targeted promotions.

## 5\. Conclusion

The dataset was already clean and structured, allowing the project to focus primarily on visualization, dashboarding, and business insights using Power BI.
