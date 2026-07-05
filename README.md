# QVI Retail Customer Segmentation & Sales Analysis

## Project Overview
End-to-end exploratory data analysis on QVI's transaction and customer loyalty data to understand purchasing behavior, customer segments, brand performance, and pack size preferences.

## Business Problem
Retailers need deep insights into customer segments to optimize stocking, promotions, and loyalty programs. This analysis identifies which segments drive sales and opportunities for targeted interventions.

## Project Objectives
- Clean and merge transaction + customer behavior datasets
- Perform feature engineering (extract pack size & brand)
- Analyze sales and customer distribution by Lifestage & Premium status
- Identify top-performing brands and pack sizes
- Provide actionable business recommendations

## Dataset Information
- **QVI_transaction_data.xlsx**: Transaction records (PROD_NAME, TOT_SALES, etc.)
- **QVI_purchase_behaviour.csv**: Customer loyalty & demographic info (LIFESTAGE, PREMIUM_CUSTOMER)

## Tools & Technologies
- Python (pandas, numpy)
- Visualization: Matplotlib, Seaborn
- Jupyter Notebook

## Data Cleaning & Preparation
- Handled duplicates
- Merged on `LYLTY_CARD_NBR`
- Extracted `PACK_SIZE` and `BRAND` using regex
- Verified no missing values post-cleaning

## Key Insights
- **Mainstream** customers drive the most sales and have the highest customer count.
- **Older Singles/Couples** lead in sales by lifestage; Retirees have high customer volume.
- **Kettle** is the top-selling brand.
- **175g** pack size is the most popular.
- Premium customers, though fewer, offer higher margins.

(Include 3-5 of your best plots here with descriptions or link to screenshots folder.)

## Recommendations
- Focus retention and promotions on Mainstream customers.
- Stock more Kettle products and 175g packs.
- Target Older families with family packs & value deals.
- Explore premium/limited editions for the Premium segment.
- Investigate barriers for New Families.

## How to Run the Project
1. Clone the repo: `git clone https://github.com/wangarikamau/QVI-Retail-Customer-Segmentation-Analysis.git`
2. Open `qvi_customer_analysis.ipynb` in Jupyter.
3. Run cells sequentially.

## Potential Extensions
- Customer lifetime value modeling
- Predictive analytics for next purchase
- A/B testing framework for promotions
- Dashboard (Power BI/Tableau) version

## Author
June Wangari Kamau  
Health Data Analyst | Python & Power BI Enthusiast  
