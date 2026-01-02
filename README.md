## Overview
This project designs a data-driven, SKU-level pricing strategy using cost, demand, inventory, competitor, advertising, and returns data.

The analysis converts multiple business datasets into structured pricing signals and applies a gated decision framework to generate realistic pricing recommendations.

## Repository Contents
- Pricing_analysis.ipynb – cost and margin guardrails  
- Historical_Sales.ipynb – demand and conversion analysis  
- Inventory_Health.ipynb – inventory and sell-through signals  
- competitor.ipynb – competitive pressure analysis  
- Ads_performance_&_returns.ipynb – validation layers  
- final.ipynb – final merging and analysis 


# folder structure
```
project/
│
├── dataset/                  # raw files
├── notebooks/                # EDA notebooks
|   ├── Pricing_analysis.ipynb
│   ├── competitor.ipynb
│   ├── Historical_Sales.ipynb   
│   ├── Inventory_Health.ipynb
│   ├── Ads_performance_&_returns.ipynb
│   ├── final.ipynb            
├── final_outputs/             # signal tables (IMPORTANT)
│   ├── pricing_signals.csv
│   ├── competitor_signals.csv
│   ├── sales_signals.csv   ← THIS ONE
│   ├── inventory_signals.csv
│   ├── ads_signals.csv
│   ├── returns_signals.csv
```
