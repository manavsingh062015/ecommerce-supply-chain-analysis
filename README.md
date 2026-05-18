# ecommerce-supply-chain-analysis
Analyzing 100K+ real Olist orders to identify delay root causes and quantify margin loss using Python and SQL-style analysis.

# 🚚 E-Commerce Supply Chain Delay Analyzer

## Business Problem
Why are orders late, which product categories drive the most margin loss,
and what should operations teams do next week?

## Dataset
[Brazilian E-Commerce (Olist)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
— 100,000+ real orders across 2017–2018.

## Key Findings
- **6.7% of orders are delayed** despite conservative ETAs
- **Carrier delay (~8.7 days) is 3× higher** than seller delay (~2.8 days)
- **Top 5 categories drive ~41% of total margin loss**
- Health & Beauty and Watches & Gifts are highest-risk categories

## Tools Used
- Python (pandas, matplotlib, seaborn)
- Power BI (dashboard)
- SQL-style analysis (groupby, window functions via pandas)

## Project Structure
- `supply_chain_delay_analysis.ipynb` — Full analysis notebook
- `images/` — Power BI dashboard screenshots

## How to Run
1. Download the Olist dataset from Kaggle (link above)
2. Place all CSVs in the `data/` folder
3. Run the notebook top to bottom

## Recommendations
1. Renegotiate SLAs with underperforming carriers
2. Recalibrate delivery ETAs (currently over-estimated by ~11 days)
3. Apply expedited logistics to top 5 high-loss categories
