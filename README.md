# E-Commerce Sales Analysis | Furniture Store

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/annna-martynova/sales-analysis/blob/main/your_notebook.ipynb)
[![Tableau Dashboard](https://img.shields.io/badge/Tableau-View%20Dashboard-blue?logo=tableau)](https://public.tableau.com/app/profile/anna.martynova/viz/E-CommerceSales_17797349252600/E-CommerceSales#1)

## About
Analysis of an online furniture store's sales performance over 
November 2020 – January 2021. Data extracted from Google BigQuery, 
processed in Python, and visualized in Tableau Public.

Covers geography, traffic channels, device behavior, product trends, 
user segmentation, and statistical testing of group differences.

## Tools
SQL (BigQuery), Python (Pandas, SciPy, Matplotlib), Tableau Public

## Dataset
E-commerce transactional data — November 2020 to January 2021

## Key Findings

**Geography**
- Americas generate the highest revenue by continent
- Strong positive correlation between Americas and Asia (0.71); 
  moderate with Europe (0.67)
- USA is the leading country, generating ~50% of total revenue 
  per category and has the highest number of registered users

**Traffic & Channels**
- Organic Search is the most popular traffic channel
- Direct, Organic, and Paid Search show strong positive correlations — 
  their performance trends move closely together
- Social and Undefined channels show weaker synchronization 
  and may require further investigation

**Devices**
- Desktop dominates across all segments — consistent with the 
  product type, as furniture purchases typically require more 
  time and screen space to evaluate

**Seasonality**
- Clear weekly seasonality across all segments
- Highest revenue on Tuesdays, lowest on Saturdays
- Notable peaks on December 8 and January 6
- Unexpected revenue drop between December 20 and January 1
- No sales recorded January 29–31

**Product Categories**
- Sofas & Armchairs is the most profitable category among top 5 countries

## Statistical Testing
Group differences validated using Mann-Whitney, Kruskal-Wallis, 
and Z-tests across continents, traffic channels, and user segments.

## Dashboard
[View on Tableau Public →](https://public.tableau.com/app/profile/anna.martynova/viz/E-CommerceSales_17797349252600/E-CommerceSales#1)
