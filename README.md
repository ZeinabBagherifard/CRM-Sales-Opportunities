# CRM Sales Opportunities Analysis

This project analyzes the **CRM Sales Opportunities** dataset from Maven Analytics. The dataset represents B2B sales pipeline activity for a fictitious company that sells computer hardware.

## Dataset

Source page: https://mavenanalytics.io/data-playground/crm-sales-opportunities

Original source listed by Maven Analytics: data.world

License listed by Maven Analytics: Public Domain

The dataset contains multiple CSV files:

- `sales_pipeline.csv`: sales opportunities and deal outcomes
- `accounts.csv`: company/account information
- `products.csv`: product information and sales prices
- `sales_teams.csv`: sales agents, managers, and regional offices
- `data_dictionary.csv`: field descriptions

## Business Questions

This project focuses on the following questions:

1. How is each sales team performing compared to the rest?
2. Are any sales agents lagging behind?
3. Are there any quarter-over-quarter trends?
4. Do any products have better win rates?

## Setup

Before running the notebook, install the required Python packages.

From the project folder, run:

```bash
pip install -r requirements.txt
```

## Run the analysis

Open `crm_sales_opportunities_cleaning.ipynb` in Jupyter Notebook or JupyterLab, then run all cells to reproduce the data cleaning, analysis, and visualizations.

## What this repo contains

- `crm_sales_opportunities_cleaning.ipynb`: the main analysis notebook
- `sales_pipeline.csv`, `accounts.csv`, `products.csv`, `sales_teams.csv`: source data files
- `data_dictionary.csv`: field descriptions
- `master_df_cleaned.csv`: cleaned master dataset 
