# Retail Sales & Profitability Analysis

## Project Overview

This project analyzes retail sales and profitability using Microsoft Excel and Tableau. The objective is to evaluate product category performance, regional sales, sub-category profitability, and discount patterns to identify business trends and opportunities for improving profit margins.

## Business Objectives

- Analyze overall sales, profit, and profit margin.
- Identify the strongest and weakest-performing product categories.
- Compare sales and profitability across regions.
- Evaluate sub-category performance.
- Investigate relationships between discount levels and profit.
- Develop data-driven recommendations for business improvement.

## Tools & Technologies

- **Microsoft Excel:** Data cleaning, data validation, PivotTables, calculations, and preliminary analysis.
- **Tableau:** Interactive data visualization and dashboard development.

## Dataset Overview

- **Records:** 250
- **Data preparation:** Identified and addressed data-quality issues, including missing values, inconsistent discount formats, invalid quantities, and invalid unit prices.
- **Analysis areas:** Sales, profit, profit margin, product categories, sub-categories, regions, and discounts.

## Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Sales | 214,419.13 |
| Total Profit | 8,261.65 |
| Overall Profit Margin | 3.85% |
| Cleaned Units Sold | 1,151 |
| Dataset Records | 250 |

*Financial values are presented in the dataset's original currency units.*

## Business Insights

### 1. Product Category Profitability

Office Supplies was the strongest-performing category, generating 94,587.46 in sales and 3,935.36 in profit, with a profit margin of 4.16%.

Furniture generated 2,049.11 in profit, while Technology generated 2,277.18. Both categories recorded margins of 3.61%.

**Recommendation:** Investigate product-level costs, pricing, and discount patterns in Furniture and Technology to identify opportunities for improving profitability.

### 2. Regional Sales & Profitability

- **Highest sales:** East — 57,446.10.
- **Highest total profit:** Central — 2,624.50.
- **Highest profit margin:** South — 5.14%.
- **Lowest margin among identified regions:** East — 2.66%.

East generated the highest sales but had a lower profit margin than the other identified regions.

**Recommendation:** Investigate East's pricing, product costs, and discount patterns. Examine South's profitability drivers to identify practices that may improve results in other regions.

One record has an unknown region and a loss of 25.61. It is retained in the overall dataset but excluded from comparisons between identified geographical regions.

### 3. Sub-Category Profitability

- **Highest total profit:** Binders — 2,579.00.
- **Highest profit margin:** Phones — 5.77%.
- **Lowest profit margin:** Tables — 0.99%.
- **Accessories profit margin:** 1.69%.

**Recommendation:** Review the pricing, costs, and discount patterns of Tables and Accessories. Investigate the factors contributing to the profitability of Binders and Phones.

### 4. Discount Analysis

The 5% discount group generated the highest total profit at 2,017.76. The 20% discount group generated the lowest total profit among the numeric discount groups at 635.20.

The 15% discount group generated sales of 42,533.40 but only 663.16 in profit.

**Recommendation:** Review discount effectiveness alongside product costs, pricing, and sales volume. These results show an association between discount groups and profitability but do not establish that discounts alone caused the differences.

## Tableau Dashboard

The dashboard includes six visualizations covering:

1. Sales by Region
2. Profit by Product Category
3. Sales by Sub-Category
4. Profit Margin by Category
5. Sales vs. Profit by Sub-Category
6. Discount Distribution by Product Category

The dashboard provides a consolidated view of retail performance to support business analysis and decision-making.

## Data Cleaning & Preparation

The data preparation process included:

- Reviewing missing and invalid values.
- Standardizing inconsistent discount entries.
- Handling invalid quantity and unit price values.
- Standardizing region labels and categorizing the missing region as Unknown.
- Creating cleaned sales calculations.
- Validating totals through Excel PivotTables.

Missing discount values were retained as missing rather than automatically treated as zero.

## Business Recommendations

1. Focus on maintaining the strong profitability of Office Supplies.
2. Investigate East's comparatively low profit margin despite its high sales.
3. Review pricing and costs for lower-margin sub-categories such as Tables and Accessories.
4. Evaluate discount strategies using product-level profitability rather than sales alone.
5. Continue monitoring sales, profit, and margin through dashboards and periodic analysis.

## Conclusion

This project demonstrates how Excel and Tableau can be used to clean retail data, analyze business performance, and communicate findings through visualizations. The analysis highlights differences between revenue and profitability and identifies areas that warrant further investigation.

The findings can help businesses prioritize pricing reviews, evaluate promotional strategies, and make more informed decisions about product and regional performance.

## Skills Demonstrated

- Data Cleaning and Validation
- Microsoft Excel
- PivotTables and Calculated Metrics
- Tableau Dashboard Development
- Exploratory Data Analysis
- Profitability and Sales Analysis
- Business Insight Development
- Data-Driven Recommendations
