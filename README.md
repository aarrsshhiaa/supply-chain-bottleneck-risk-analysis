# Supply Chain Bottleneck & Delivery Risk Analysis

## Overview

This project analyzes supply chain performance across shipping modes, markets, regions, and delivery outcomes using the DataCo Smart Supply Chain dataset.

The objective is to identify delivery bottlenecks, evaluate their operational and financial impact, and provide actionable insights that can support supply chain and logistics decision-making.

The project combines **SQL Server** for data validation and analytical analysis with **Power BI** for interactive visualization and KPI reporting.

---

## Business Problem

Supply chain performance cannot be evaluated using sales alone. Delays, shipping performance, regional bottlenecks, and profitability all influence operational efficiency.

This project focuses on questions such as:

* Which shipping modes experience the highest delivery delays?
* Which markets and regions have weaker delivery performance?
* Where are high order volumes combined with elevated delivery risk?
* How does delivery performance vary across product and operational segments?
* What is the relationship between logistics performance and financial outcomes?
* Which areas should be prioritized for further operational investigation?

---

## Dashboard

The Power BI dashboard provides an interactive view of supply chain performance through multiple analytical perspectives.

### Delivery Performance

Key metrics and analysis include:

* On-time delivery performance
* Late-delivery rate
* Shipping-mode performance
* Order volume
* Regional and market-level performance
* Delivery trends

### Bottleneck Analysis

The dashboard evaluates operational bottlenecks across:

* Shipping modes
* Markets
* Regions
* Product categories
* Order volume
* Delivery performance

High-volume areas with relatively poor delivery performance can be investigated as potential operational bottlenecks.

### Financial Analysis

The project also evaluates:

* Total sales
* Profit
* Profit margin
* Financial contribution across markets and operational segments

Combining financial and logistics metrics helps identify areas where operational issues may have a larger business impact.

---

## Key Insights

The analysis highlights several important patterns within the supply chain:

* Delivery performance varies significantly across shipping modes.
* Late deliveries represent a substantial operational issue within the dataset.
* Regional and market-level delivery performance is not uniform.
* High order volume and poor delivery performance can occur simultaneously, creating areas that require closer operational attention.
* Financial performance provides additional context when evaluating supply-chain priorities.

---

## Business Recommendations

Based on the analysis, potential areas for operational improvement include:

1. Investigating shipping modes with consistently weaker delivery performance.
2. Monitoring high-volume regions with elevated late-delivery rates.
3. Tracking delivery KPIs at regional and category levels rather than relying only on overall averages.
4. Combining operational KPIs with sales and profitability when prioritizing improvement initiatives.
5. Establishing regular monitoring of delivery performance to identify emerging bottlenecks.

---

## SQL Analysis

SQL Server was used for data validation and analytical exploration.

The SQL analysis includes:

* Dataset sanity checks
* Date-range validation
* Revenue calculation
* Profit analysis
* Profit-margin calculation
* Order-volume analysis
* Late-delivery analysis
* Late-delivery percentage

The SQL scripts are available in the `sql/` directory.

---

## Power BI Dashboard

The Power BI dashboard contains interactive visualizations for:

* Supply chain KPIs
* Delivery performance
* Shipping-mode analysis
* Regional analysis
* Market performance
* Financial performance
* Bottleneck identification

The Power BI source file is available in the `dashboard/` directory.

---

## Technology Stack

| Technology             | Purpose                                      |
| ---------------------- | -------------------------------------------- |
| **Power BI**           | Interactive dashboard and data visualization |
| **DAX**                | KPI and analytical calculations              |
| **SQL Server / T-SQL** | Data validation and analysis                 |
| **GitHub**             | Project documentation and version control    |

---

## Dataset

The project uses the **DataCo Smart Supply Chain for Big Data Analysis** dataset.

The dataset contains information relating to:

* Orders
* Products
* Customers
* Markets
* Regions
* Shipping modes
* Delivery performance
* Sales
* Profitability

The analysis is performed using transactional supply-chain data to understand operational and financial performance.

---

## Analytical Workflow

```text
DataCo Supply Chain Dataset
            ↓
      Data Validation
            ↓
       SQL Analysis
            ↓
     KPI Development
            ↓
      Power BI Model
            ↓
   Interactive Dashboard
            ↓
  Bottleneck Identification
            ↓
    Business Insights
```

---

## Repository Structure

```text
supply-chain-bottleneck-risk-analysis/
│
├── dashboard/
│   ├── Supply_Chain_Bottleneck_Risk.pbix
│   └── Supply_Chain_Bottleneck_Risk.pdf
│
├── screenshots/
│   ├── dashboard_1.png
│   ├── dashboard_2.png
│   └── dashboard_3.png
│
├── sql/
│   └── data_validation_and_exploration.sql
│
└── README.md
```

---

## Project Status

**Completed**

This project demonstrates an end-to-end supply chain analytics workflow using SQL Server and Power BI, with a focus on delivery performance, operational bottlenecks, and financial analysis.
