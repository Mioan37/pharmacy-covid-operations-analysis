# Pharmacy COVID-19 Operations Analysis  
## Demand Shifts, Stock Pressure & Supplier Delays in a Small Local Pharmacy

## Project Overview

This portfolio project analyses how a small local pharmacy in Samos, Greece could have experienced operational changes during the COVID-19 period.

The project focuses on selected OTC and COVID-related product categories and services, including protective products, vitamins, cough and cold products, COVID self-tests and pharmacy COVID testing services.

The goal is to demonstrate how healthcare-oriented data analysis can be used to identify demand spikes, stock pressure, supplier delays and category-level revenue changes during a period of sudden healthcare demand.

---

## Business Problem

During the COVID-19 period, pharmacies experienced major changes in customer demand, product availability and supplier reliability.

A small local pharmacy needed to answer questions such as:

- Which product categories experienced the strongest demand increase?
- Which products created the highest stock pressure?
- Did supplier delays increase during high-demand periods?
- Which categories became more important for revenue?
- How could the pharmacy improve inventory planning during future health-crisis periods?

This project models those questions using synthetic pharmacy operations data.

---

## Main Business Question

**How did COVID-19 affect demand, revenue, stock availability and supplier delays for selected OTC and COVID-related pharmacy categories in a small local pharmacy?**

---

## Key Questions Answered

This analysis aims to answer the following questions:

1. **Which categories showed the largest demand increase after early 2020?**

2. **How did revenue change before, during and after the main COVID period?**

3. **Which categories experienced the most out-of-stock incidents?**

4. **Did supplier delays increase during periods of high demand?**

5. **Which products or services required closer inventory monitoring?**

6. **What operational lessons could help a pharmacy prepare for future demand shocks?**

---

## Dataset Description

The dataset contains weekly records from **2019 to 2022** for selected pharmacy categories.

The analysis focuses on OTC and COVID-related categories rather than the full turnover of the pharmacy.

### Categories Included

The dataset includes 13 selected OTC, prescription-support and COVID-related categories:

- Adult productive cough syrup
- Adult dry cough syrup
- Children's productive cough syrup
- Children's dry cough syrup
- Cough lozenges
- Antibiotic prescriptions
- Vitamins and supplements
- Simple masks
- KN95/FFP2 masks
- Antiseptic / alcohol products
- Hand gloves
- COVID self-tests
- Pharmacy COVID test service
  
### Dataset Fields

The dataset includes operational and commercial fields such as:

- Week_Start
- Year, derived from Week_Start for yearly analysis
- Product category
- Units sold
- Revenue
- Stock level
- Out-of-stock incidents
- Supplier delay days
- Service volume, where applicable

---

## Important Disclaimer

This project uses **synthetic and anonymized data** created for portfolio purposes.

All figures in the dataset, including sales, stock levels, service volumes, supplier delays and revenue amounts, are indicative only.

They do not represent real pharmacy financial records, patient data or confidential business information.

The model is designed to reflect realistic pharmacy demand patterns during the COVID-19 period while protecting sensitive personal and business information.

---

## Files Included

| File | Description |
|---|---|
| `pharmacy_covid_project_realistic.xlsx` | Formatted Excel workbook with dataset, summaries and analysis-ready tables |
| `pharmacy_covid_dataset_realistic.csv` | Raw dataset for Power BI, Excel or Python analysis |
| `README.md` | Full project documentation and business explanation |

---

## Tools Used

- Microsoft Excel
- Power BI
- Data cleaning
- KPI design
- Trend analysis
- Business analysis
- Healthcare operations analysis
- Inventory and stock pressure analysis

---

## Suggested Power BI Dashboard Pages

### 1. Executive Summary

Purpose: Give a quick overview of the main operational changes during the COVID period.

Suggested visuals:

- Total revenue by year
- Total units sold by year
- Out-of-stock incidents by year
- Average supplier delay by year
- Top categories by revenue
- Key insight cards

---

### 2. Sales Trend Before vs During COVID

Purpose: Compare demand before and during the COVID period.

Suggested visuals:

- Weekly units sold trend
- Revenue trend by year
- Category-level demand over time
- Pre-COVID vs COVID period comparison

Business focus:

- Identify which categories increased sharply after early 2020
- Compare normal pharmacy demand with health-crisis demand

---

### 3. Revenue by Category

Purpose: Understand which categories became most commercially important.

Suggested visuals:

- Revenue by category
- Revenue share by year
- Category ranking table
- Year-over-year revenue change

Business focus:

- Identify revenue-driving categories
- Understand how product mix changed during COVID

---

### 4. Stock Pressure & Out-of-Stock Analysis

Purpose: Identify where demand created inventory pressure.

Suggested visuals:

- Out-of-stock incidents by category
- Out-of-stock incidents by year
- Units sold vs stock level
- High-risk category table

Business focus:

- Find products that required closer stock monitoring
- Identify categories at risk of lost sales due to stock shortages

---

### 5. Supplier Delay Trend

Purpose: Analyse whether supplier reliability changed during high-demand periods.

Suggested visuals:

- Average supplier delay by year
- Supplier delay by category
- Supplier delay trend over time
- Supplier delay vs out-of-stock incidents

Business focus:

- Understand how external supply issues affected pharmacy operations
- Identify categories most exposed to supplier delays

---

### 6. Demand Spike Analysis

Purpose: Detect unusual demand increases linked to the COVID period.

Suggested visuals:

- Demand spike weeks
- Category-level peak demand
- Units sold before vs during COVID
- Fast-moving COVID-related items

Business focus:

- Identify sudden demand changes
- Support better future stock planning

---

## Key KPIs

The following KPIs were designed for this project:

| KPI | Purpose |
|---|---|
| Total Revenue | Measures commercial performance across selected categories |
| Units Sold | Tracks product demand over time |
| Revenue by Category | Shows which categories contributed most to sales |
| Out-of-Stock Incidents | Measures stock pressure and availability issues |
| Average Supplier Delay | Tracks supplier reliability |
| Demand Growth % | Compares demand before and during COVID |
| Top Revenue Category | Identifies the strongest commercial category |
| High-Risk Stock Category | Highlights categories with frequent stock issues |

---

## Example Insights

Based on the modelled dataset, the project can generate insights such as:

- Protective products such as masks, antiseptics and gloves show a clear demand increase after early 2020.

- COVID self-tests and pharmacy COVID testing services become important during the main COVID period.

- Vitamins and supplements maintain elevated demand during the COVID years, suggesting increased customer focus on prevention and immune support.

- Out-of-stock incidents become more visible in fast-moving COVID-related categories.

- Supplier delays increase during high-demand periods, especially for products linked to protection, testing and infection control.

- Some categories show strong short-term demand spikes, while others show more stable long-term revenue growth.

---

## Business Recommendations

Based on the analysis, a small pharmacy could consider the following actions:

### 1. Improve stock monitoring for high-demand categories

Products such as masks, antiseptics, gloves and self-tests should be monitored more frequently during periods of increased public health demand.

### 2. Set minimum stock thresholds

Fast-moving categories should have minimum stock levels to reduce the risk of out-of-stock incidents.

### 3. Track supplier reliability

Supplier delay trends should be reviewed regularly, especially during peak demand periods.

### 4. Use category-level demand forecasting

Historical weekly sales patterns can help estimate future demand for seasonal or crisis-related products.

### 5. Separate normal demand from crisis demand

COVID-related demand spikes should be analysed separately from normal pharmacy sales to avoid misleading long-term forecasts.

### 6. Prepare a crisis inventory plan

The pharmacy could create a predefined list of critical products to prioritise during future healthcare disruptions.

---

## Skills Demonstrated

This project demonstrates the following skills:

- Healthcare-oriented data analysis
- Pharmacy operations understanding
- Inventory and stock pressure analysis
- Trend analysis
- KPI design
- Excel data preparation
- Power BI dashboard planning
- Business storytelling
- Operational decision support
- Data-driven recommendations

---

## Why This Project Matters

This project connects pharmacy experience with business and data analysis.

It shows how operational data can help a pharmacy understand demand changes, stock risk, supplier issues and revenue shifts during an unusual healthcare event.

The project is especially relevant for roles in:

- Healthcare operations
- Pharmacy operations
- Business analysis
- Data analysis
- Inventory planning
- Commercial operations
- Power BI reporting

---

## Limitations

This project does not use real patient data, real prescription data or confidential business records.

The dataset is synthetic and focused only on selected OTC and COVID-related categories.

It does not represent the full financial performance of a pharmacy.

The purpose is to demonstrate analytical thinking, business storytelling and healthcare operations insight using realistic but anonymized portfolio data.

---

## Future Improvements

Possible future improvements include:

- Adding seasonal comparison between winter and summer demand
- Adding gross profit and margin analysis
- Adding supplier-level performance analysis
- Adding reorder point calculations
- Creating Power BI drill-through pages by category
- Adding forecast scenarios for future demand spikes
- Comparing pharmacy product demand with public COVID case trends

---

## Conclusion

This project demonstrates how a small pharmacy could use operational data to understand the impact of COVID-19 on selected product categories and services.

By analysing revenue, demand, stock pressure and supplier delays, the project highlights how data can support better inventory planning, operational decisions and healthcare service readiness during periods of sudden demand change.
