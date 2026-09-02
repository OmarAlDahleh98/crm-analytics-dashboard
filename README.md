# CRM Analytics Dashboard

End-to-end CRM analytics portfolio project covering data cleaning, exploratory data analysis, dimensional modeling, DAX, and a professional Power BI dashboard.

## Project Overview

**Raw CRM Data → Python Data Cleaning → Exploratory Data Analysis → Star Schema → DAX Measures → Power BI Dashboard**

The project focuses on customer and lead analytics, conversion performance, revenue, sales activity, customer satisfaction, response time, and lead-score behavior.

## Business Objectives

- Monitor CRM and sales performance through executive KPIs.
- Analyze the lead funnel and conversion rate.
- Evaluate revenue and won-lead performance.
- Compare customer segments, industries, campaigns, and sales representatives.
- Analyze lead-score quality and conversion behavior.
- Monitor customer satisfaction and response time.
- Provide actionable insights for sales and customer-management decisions.

## Key KPIs

| KPI | Value |
|---|---:|
| Total Customers / Leads | 5,000 |
| Won Leads | 819 |
| Lost Leads | 433 |
| Conversion Rate | 16.4% |
| Total Revenue | $1,643,197 |
| Average Revenue | $328.64 |
| Average Revenue — Won Leads | $1,448.83 |
| Average Lead Score | 59.4 |
| Average Response Time | 11.2 hours |
| Average Customer Satisfaction | 7.37 / 10 |

## Technical Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power Query
- Power BI
- DAX
- Star Schema / Dimensional Modeling
- Jupyter Notebook / VS Code workflow

## Repository Structure

```text
crm-analytics-dashboard/
├── PowerBI/
│   └── CRM_Dashboard.pbix
├── Python/
│   ├── 01_CRM_Data_Cleaning.ipynb
│   ├── 02_CRM_EDA.ipynb
│   └── 03_CRM_Dashboard_Analysis.ipynb
├── Data/
│   ├── CRM_Cleaned_Public.csv
│   └── README.md
├── DAX/
│   └── DAX_Measures.dax
├── Documentation/
│   └── Project_Roadmap.md
└── README.md
```

## Data Preparation

The Python cleaning workflow covered data inspection and profiling, missing-value handling, duplicate detection and resolution, data-type correction, date validation, text and category standardization, invalid-value correction, logical validation, derived-field creation, and export of the cleaned dataset.

For public GitHub publication, direct customer identity/contact fields were removed from the published dataset.

## Data Modeling

The Power BI model uses a dimensional structure built around the CRM fact data and supporting dimensions, including customer, date, product, sales representative, campaign, funnel stages, and score bands.

## DAX

The repository contains the DAX measures extracted from the Power BI model using `INFO.MEASURES()`. The measures cover core KPIs, conversion analysis, revenue analysis, response-time analysis, customer satisfaction, lead-score analysis, and HTML-based custom visuals.

## Python Analysis

The notebooks document the analytical workflow used before and alongside the Power BI dashboard, including customer analysis, lead-funnel analysis, conversion analysis, revenue analysis, sales-representative performance, marketing-source performance, satisfaction, response time, segment/industry analysis, and business insights.

## Public Data Notice

The repository uses a public-safe version of the CRM dataset. Direct identity and contact columns such as names, email addresses, and phone numbers are excluded from the published CSV.

## Project Outcome

A portfolio-ready CRM analytics solution connecting data preparation, analytical reasoning, dimensional modeling, DAX, and business intelligence reporting in one end-to-end workflow.

## Author

**Omar Al-Dahleh**

Management Information Systems (MIS) | Data Analytics | Business Intelligence | Power BI
