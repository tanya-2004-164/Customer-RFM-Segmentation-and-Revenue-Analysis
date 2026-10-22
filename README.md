# Customer RFM Segmentation & Revenue Analysis

##  Project Overview

This project analyzes customer purchasing behavior using **RFM (Recency, Frequency, Monetary) Segmentation** to identify valuable customers, loyal buyers, at-risk customers, and inactive customers.

The objective is to help businesses understand customer value, analyze revenue contribution, and develop targeted customer retention strategies using Python, SQL, and Excel.

##  Business Objectives

- Segment customers based on purchasing behavior.
- Identify high-value and loyal customers.
- Analyze revenue contribution across customer segments.
- Identify at-risk and inactive customers.
- Generate actionable insights to improve customer retention.

##  Tools & Technologies

- **Python:** Data cleaning, preprocessing, RFM calculations, and segmentation.
- **Pandas:** Data manipulation and analysis.
- **SQL (SQLite):** Customer segmentation queries and revenue analysis.
- **Excel:** Summary analysis and data visualization.
- **Google Colab:** Python development environment.

##  Dataset

The project uses the **Online Retail II** dataset, which contains transactional data from an online retail business.

Key fields include:

- Invoice
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

## ⚙️ Project Workflow

1. **Data Cleaning:** Handled missing values, converted data types, and filtered invalid transactions and cancelled invoices.
2. **Feature Engineering:** Calculated transaction revenue using Quantity × Price.
3. **RFM Analysis:** Calculated Recency, Frequency, and Monetary values for each customer.
4. **Customer Scoring:** Assigned scores from 1 to 5 for each RFM metric.
5. **Customer Segmentation:** Classified customers into six groups.
6. **SQL Analysis:** Used SQLite queries to analyze segment size, revenue contribution, and top-spending customers.
7. **Excel Visualization:** Created a bar chart to compare revenue across customer segments.

##  Customer Segments

| Segment | Business Interpretation |
|---|---|
| Champions | Recent, frequent, high-value customers |
| Loyal Customers | Customers with strong purchase frequency |
| Potential Loyalists | Customers with potential to become loyal |
| Recent Customers | Customers who purchased recently |
| At Risk | Previously engaged customers who may need re-engagement |
| Hibernating | Inactive customers with low purchase frequency |

##  Key Findings

Based on the customer segmentation analysis:

- **4,313 customers** were included in the final RFM analysis.
- **Champions:** 907 customers, contributing approximately 5.77 million in revenue.
- **At Risk:** 699 customers, contributing approximately 1.10 million in revenue.
- **Hibernating:** 1,026 customers, making this the largest customer segment by count.
- Champions represent an important group for loyalty programs and customer retention initiatives.

*Note: Revenue figures are expressed in the dataset's original currency units.*

##  Business Recommendations

- **Champions:** Reward high-value customers with loyalty benefits and exclusive offers.
- **Loyal Customers:** Encourage repeat purchases through personalized recommendations.
- **Potential Loyalists:** Use targeted offers to increase purchase frequency.
- **At Risk:** Launch re-engagement campaigns to encourage customers to return.
- **Hibernating:** Test win-back campaigns and targeted discounts.

## Project Files

- `Online_Retail_II.csv` — Source transaction dataset.
- `RFM_Customer_Segments.csv` — Customer-level RFM scores and segment labels.
- `RFM_Segment_Summary.csv` — Aggregated customer and revenue metrics.
- `SQL_Segment_Analysis.csv` — SQL-based segment analysis results.
- `SQL_Top_100_Customers.csv` — Top customer analysis exported from SQL.
- `README.md` — Project documentation.

##  How to Run

1. Open the project notebook in Google Colab.
2. Upload the Online Retail II dataset.
3. Run the Python data-cleaning and RFM analysis cells.
4. Load the generated customer segmentation CSV into SQLite.
5. Execute SQL queries for customer and revenue analysis.
6. Open the exported CSV files in Excel to explore the results.

##  Future Improvements

- Build an interactive Power BI dashboard.
- Add customer-level revenue and segment comparisons.
- Automate the RFM analysis pipeline.
- Evaluate additional segmentation strategies.

##  Author

**Tanya Solanki**

Data Analytics | Python | SQL | Excel | Customer Segmentation

This project demonstrates practical skills in data cleaning, customer analytics, SQL querying, business insights, and data visualization.
