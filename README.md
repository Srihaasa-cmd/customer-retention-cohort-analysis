# customer-retention-cohort-analysis
## Overview 
Analysed customer purchasing behaviour across 12 monthly cohorts 
to identify retention patterns and churn points in an e-commerce business.

## Problem Statement
The business was losing customers but didn't know at what point 
customers were dropping off or which group of customers were most loyal.

## What I have achieved 
Built cohort retention matrix tracking 286 customers across 12 monthly cohorts using Pandas pivot tables 
Visualised retention heatmap revealing 60% of customers churn after first purchase identifying critical drop-off points 
Identified Month 3 as loyalty milestone and recommended targeted win-back campaigns to reduce revenue loss.

## Key Findings
- 60% of customers churn after their very first purchase
- Month 3 is the critical loyalty milestone — customers who 
  return at Month 3 are significantly more likely to stay long term
- Early cohorts show stronger retention than recent cohorts 
  suggesting declining customer satisfaction over time
  
## Tools Used
- Python
- Pandas — cohort grouping and pivot tables
- Seaborn — retention heatmap
- Matplotlib — retention curve chart
- Jupyter Notebook
- 
## Files
- `Cohort_Analysis.ipynb` — main analysis notebook
- `ecommerce_data.csv` — dataset used
- `cohort_heatmap.png` — retention heatmap visualization
- `retention_curve.png` — average retention curve chart

## How to Run
1. Clone this repository
2. Open `Cohort_Analysis.ipynb` in Jupyter Notebook
3. Make sure `ecommerce_data.csv` is in the same folder
4. Run all cells top to bottom
5. 
## Dataset
Simulated e-commerce dataset — 1,000 orders, 286 unique customers, 2024

