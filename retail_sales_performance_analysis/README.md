# Retail Sales Performance Analysis

## Project Overview

This project analyzes retail transaction data from July to December 2019 to evaluate sales performance, brand contribution, product demand, regional distribution, and customer purchasing behavior.

The analysis aims to identify sales trends and patterns that can support business evaluation and decision-making.

## Business Questions

1. How did sales performance change from July to December 2019?
2. Which brands contributed the most to sales quantity and Gross Merchandise Value (GMV)?
3. What patterns can be observed in product demand and pricing?
4. How was GMV distributed across provinces and cities?
5. How often did customers purchase, and how many returned in the following quarter?

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Findings

- **Sales Performance:** December recorded the highest monthly sales quantity at 13,507 units and the highest GMV at IDR 8.14 billion.
- **Brand Performance:** BRAND_P recorded the highest sales quantity, while BRAND_S generated the highest GMV.
- **Quarterly Performance:** Q4 recorded higher sales quantity and GMV than Q3.
- **Product Pricing:** Product prices were right-skewed, with most products having relatively low median prices and a smaller number of high-priced products.
- **Regional Performance:** DKI Jakarta recorded the highest provincial GMV at IDR 14.89 billion. South Jakarta ranked first among the top 10 cities, with GMV of IDR 5.25 billion.
- **Customer Behavior:** Most customers placed only one order during the observed period. The retention rate from Q3 to Q4 was 52.48%.
- **Customer Contribution:** The top 10 customers generated IDR 5.13 billion, representing 15.57% of total GMV.

## Business Recommendations

- Investigate the factors behind monthly sales increases and declines using additional business data.
- Evaluate brand performance using both sales quantity and GMV.
- Review product pricing and sales patterns to identify products that may require further investigation.
- Monitor repeat purchases and customer retention across periods.
- Maintain relationships with high-value customers while continuing to serve the broader customer base.
- Review regional sales performance to identify opportunities for further investigation.

## Limitations

- The dataset covers only July to December 2019.
- GMV represents transaction value and does not indicate profit.
- The available data does not establish the causes of sales changes.
- Customers without a recorded Q3 purchase cannot automatically be classified as new customers because their purchase history before July 2019 is unavailable.
