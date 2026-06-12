# Retail Sales Analytics

## Project Overview

This project analyzes global retail sales data to identify the key drivers of profitability and uncover areas of financial underperformance.

Using Python for data cleaning and exploratory data analysis (EDA), and Power BI for dashboard development, the project investigates sales trends, category performance, discount strategies, and country-level profitability.

---

## Business Questions

1. Which product categories generate the highest sales and profits?
2. Which countries contribute the most and least profit?
3. How do discounts impact profitability?
4. Which subcategories are causing financial losses?
5. What actions can improve overall business performance?

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Power BI
- Git
- GitHub

---

## Data Cleaning

The following preprocessing steps were performed:

- Converted sales from text to numeric format
- Standardized mixed date formats
- Created shipping_days feature
- Checked for missing values
- Validated data types
- Exported cleaned dataset for Power BI

---

## Key Findings

### Category Performance

| Category | Sales | Profit Margin |
|-----------|--------|---------------|
| Technology | Highest | ~14% |
| Office Supplies | Moderate | ~13.7% |
| Furniture | High Sales but Lowest Margin | ~7% |

Furniture generates substantial revenue but significantly lower profitability.

---

### Discount Impact

A strong negative relationship exists between discount levels and profitability.

Key observations:

- Orders with no discount are highly profitable.
- Profitability declines rapidly above 20% discounts.
- Discounts above 50% frequently generate losses.
- Extreme discounts (70–85%) produce the largest losses.

---

### Problematic Subcategory

Tables was identified as the worst-performing subcategory.

- Total Profit: -64,083
- Average Discount: 29%
- Correlation between Discount and Profit: -0.68

---

### Country-Level Findings

Highest Profit Countries:

- United States
- China
- India

Lowest Profit Countries:

- Turkey
- Nigeria
- Netherlands

Turkey and Nigeria exhibit extremely high average discounts and severe negative profit margins.

---

## Recommendations

1. Reduce aggressive discounting policies.
2. Review pricing strategy for Tables.
3. Investigate loss-making markets such as Turkey and Nigeria.
4. Focus growth efforts on Technology products.
5. Implement discount thresholds to protect margins.

---

## Dashboard

The Power BI dashboard includes:

- Sales KPIs
- Profit KPIs
- Category Performance Analysis
- Country Performance Analysis
- Discount vs Profit Analysis

---

## Dashboard Preview

![Retail Sales Dashboard](images/Retail_Sales_Dashboard.png)

## Repository Structure

Retail-Sales-Analytics/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ └── retail_sales_analysis.ipynb
│
├── dashboard/
│
├── images/
│
└── README.md

---

## Author

Amir Hossein Ashrafi