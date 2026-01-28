Slooze Take-Home - Inventory, Purchase, Sales Analysis

This repo contains a Jupyter notebook solution for:
- Demand exploration + baseline forecasting view
- ABC classification
- EOQ (Economic Order Quantity)
- Reorder Point + Safety Stock
- Lead-time / supplier analysis notes
- Executive summary KPIs + recommendations

Requirements
- Python 3.10+ (3.11 recommended)

Run locally (Windows PowerShell)
cd slooze-inventory-analytics
python -m venv .venv
.\\.venv\\Scripts\\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
jupyter lab

Open notebook.ipynb in Jupyter.

Data
This notebook was originally built using Kaggle input paths. To run locally:
1) Put the CSVs into data\\
2) Update notebook file paths to data\\<file>.csv

Notes
- Tune EOQ/ROP assumptions: ordering_cost_per_po, annual_holding_rate, service_level
