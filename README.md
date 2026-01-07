# Vendor Performance Analysis

## Project Overview
This project analyzes vendor performance using transactional, inventory, and pricing data to uncover insights related to profitability, inventory efficiency, purchasing behavior, and vendor contribution.  
The objective is to apply **exploratory data analysis (EDA)** and **statistical techniques** to support data-driven business decisions and actionable recommendations.


---

## Business Objectives
- Evaluate vendor performance using sales, purchases, inventory, and pricing data
- Identify high- and low-performing vendors based on revenue and profit margins
- Analyze inventory turnover and detect slow-moving stock
- Assess the impact of bulk purchasing on cost efficiency
- Provide actionable recommendations to improve profitability and operational efficiency

---

## Dataset Summary
The analysis is based on **six large, interrelated datasets**:

- **begin_inventory** – Opening inventory levels by product and vendor  
- **end_inventory** – Closing inventory balances  
- **sales** – Sales transactions and revenue data  
- **purchases** – Purchase quantities and transaction details  
- **purchase_prices** – Unit cost and pricing information  
- **vendor_invoice** – Vendor billing and invoice-level data  

These datasets enable comprehensive analysis of inventory movement, pricing, vendor contribution, and profitability.

> **Note:**  
> Raw datasets are not included in this repository as the original files are large in size.

---

## Project Structure

'''

vendor-performance-analysis/

  data/
  
    README.md
  data_ingestion/
  
    data_ingestion.ipynb
  scripts/
  
    inventory_db.sql
    vendor_summary_data.sql
  eda/
  
    exploratory_analysis_sql.ipynb
    exploratory_analysis_python.ipynb
  reports/
  
    Vendor_Performance_Analysis_Report.docx
  
  README.md
  
'''





---

## Key Analytical Steps
- Data validation and filtering to remove loss-making and inconsistent records
- Summary statistics and distribution analysis
- Outlier detection using variance and standard deviation
- Correlation analysis between pricing, sales, inventory, and profitability
- Vendor segmentation based on sales contribution and profit margins
- Statistical hypothesis testing to validate margin differences

---

## Key Insights
- Several vendors exhibit **high profit margins but low sales volumes**, indicating pricing or market reach inefficiencies
- The **top 10 vendors account for ~66% of total purchases**, creating supply chain dependency risks
- **Bulk purchasing reduces unit costs by approximately 72%**, improving cost efficiency
- **Slow-moving inventory accounts for ~$2.71M** in tied-up capital
- High stock turnover does not necessarily translate into higher profitability

---

## Statistical Validation
A hypothesis test comparing profit margins between top-performing and low-performing vendors confirms a **statistically significant difference**, indicating distinct profitability models across vendor groups.

---

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib)
- **SQL
- **Jupyter Notebook**
- **Statistical analysis & hypothesis testing**
- **Data visualization**

---

## Final Recommendations
- Re-evaluate pricing strategies for low-sales, high-margin vendors to increase volume
- Diversify vendor partnerships to reduce over-dependence
- Leverage bulk purchasing while optimizing inventory levels
- Address slow-moving inventory through improved demand planning and clearance strategies
- Strengthen marketing and distribution efforts for underperforming vendors

---

