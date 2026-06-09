# Customer Churn Analysis & Retention Strategy
### MySQL · Python · Statistics · Power BI

![Python](https://img.shields.io/badge/Python-3.x-blue)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)

## Overview
Analyzed churn behaviour of 7,043 telecom customers to identify
key drivers of churn and built an interactive Power BI dashboard
for the retention team.

## Key Findings
- Month-to-month contracts churn at 41% vs 3% for two-year contracts
- New customers (0-12 months) have highest churn risk at 47%
- $1.67M in annual revenue at risk from churned customers
- Chi-square test confirms contract type drives churn (p < 0.0001)
- Electronic check users churn 8% more than automatic payment users

## Tools
| Tool | Purpose |
|------|---------|
| MySQL | Database, KPI queries, window functions |
| Python | Cleaning, EDA, feature engineering |
| Scipy | Chi-square hypothesis testing |
| Matplotlib & Seaborn | 12 visualizations |
| Power BI | 2-page interactive dashboard |

## Dashboard Preview
![Page 1](outputs/powerbi/22_powerbi_executive.png)
![Page 2](outputs/powerbi/23_powerbi_churn_drivers.png)

## Dataset
IBM Telco Customer Churn | 7,043 rows | 21 features
kaggle.com/datasets/blastchar/telco-customer-churn

## Author
**Krish Kalpish Patel** | [LinkedIn](https://www.linkedin.com/in/krish-patel-3a1507373)
