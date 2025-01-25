# Sales Analysis and Insights

## Overview
This project provides a comprehensive analysis of sales data from a retail dataset. The dataset used for this analysis is sourced from [Kaggle](https://www.kaggle.com/datasets/ankitbansal06/retail-orders). Using Python for data preprocessing and SQL for advanced queries, the insights focus on revenue, sales growth, and performance trends across products, regions, and time periods. Below is a summary of key findings and methodologies.

## Key Insights

### 1. **Top 10 Revenue-Generating Products**
- SQL Query: Identified the top 10 products by revenue using aggregated sales data.
- **Insight**: These products contributed approximately **X%** of total revenue.

### 2. **Best-Selling Products by Region**
- SQL Query: Extracted the top 5 products for each region by sales.
- **Insight**:
  - Region A: Product 1, Product 2...
  - Region B: Product 3, Product 4...

### 3. **Month-over-Month Sales Growth (2022 vs. 2023)**
- SQL Query: Compared monthly sales growth for two years.
- **Insight**: Sales grew by **Y%** in 2023 compared to 2022, with the highest growth in **Month**.

### 4. **Peak Sales Month by Product Category**
- SQL Query: Determined the month with the highest sales for each category.
- **Insight**: Category A peaked in **Month-Year**, while Category B peaked in **Month-Year**.

### 5. **Sub-Category with Highest Growth**
- SQL Query: Identified the sub-category with the largest increase in sales and profits between 2022 and 2023.
- **Insight**: Sub-category **X** experienced a **Z%** increase in sales.

## Data Preparation Steps
- Handled missing values and standardized column names.
- Computed new fields, such as:
  - **Discount**: Derived from `list_price` and `discount_percent`.
  - **Sale Price**: Calculated as `list_price - discount`.
  - **Profit**: Derived from `sale_price - cost_price`.
- Cleaned data saved to `Orders_cleaned_file.csv`.

## Methodology
- SQL queries executed on a cleaned dataset for precise insights.
- Visualization tools used for trends and growth representation.

## Future Enhancements
- **Advanced Visualization**: Incorporate dashboards for better data representation.
- **Prediction Models**: Forecasting sales growth and identifying future top-selling products.
- **Detailed Metrics**: Breakdowns by customer demographics or order channels.

---
Feel free to explore the codebase and datasets for more details. Contributions are welcome!

