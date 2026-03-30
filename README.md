# Banking Risk Analysis Pipeline 

**SQL → Python → Pandas → Power BI**  
*End-to-end data analysis to assess lending risk using customer financial data*

## 🎯 Project Overview

Built a **complete banking risk analysis pipeline** that ingests customer financial data (Excel → MySQL → Python → Power BI) to identify lending risk patterns and optimize credit decisions.

**Key Business Problem:** Minimize financial losses while lending money to customers by analyzing their financial health indicators.

## 🛠 Tech Stack

```
Excel (.xlsx) → MySQL → Python (pandas, matplotlib) → Power BI (.pbix)
```

##  Pipeline Architecture

```mermaid
flowchart LR
    A[Customer Banking Data<br/>CSV / Excel] --> B[MySQL]
    B --> C[Python ETL]
    C --> D[Data Cleaning & EDA]
    D --> E[Power BI Dashboard]
    E --> F[Lending Risk Insights]
```

##  Features

- **Data Ingestion:** Excel → MySQL using `mysql-connector-python`
- **ETL Pipeline:** Clean, transform, analyze banking data with pandas
- **Exploratory Analysis:** Histograms of income, savings, credit balances
- **Interactive Dashboards:** Power BI visualizations for stakeholder review
- **Risk Indicators:** High-risk customer profiles (low savings + high credit)

## 📁 Repository Structure

```
banking-risk-analysis/
├── data/
│   └── Banking.csv
├── notebooks/
│   └── DA_Banking_Project_EDA.ipynb
├── reports/
│   └── banking_dashboard.pbix
├── README.md
└── requirements.txt
```

##  Quick Start

1. **Setup MySQL** 
2. **Install dependencies:**
   ```bash
   pip install mysql-connector-python pandas matplotlib
   ```
3. **Run analysis:** Open `notebooks/DA_Banking_Project_EDA.ipynb`
4. **View dashboard:** Open `reports/banking_dashboard.pbix` in Power BI

## 📈 Key Insights

- **80% customers** have credit card balances > $5K
- **High-risk segment:** Low savings + high credit utilization
- **Pipeline processes** 10K+ records in <30 seconds

##  Learning Outcomes

- End-to-end data pipeline (Excel → Dashboard)
- MySQL integration with Python
- Pandas for financial data cleaning
- Power BI for stakeholder reporting

## 🎓 Skills Demonstrated

**Data Engineering:** MySQL ETL, Python scripting  
**Data Analysis:** Pandas EDA, statistical analysis  
**Visualization:** Matplotlib + Power BI dashboards  
**Business Impact:** Risk assessment for lending decisions  

***

**👩‍💻 Built by Anmisha M** |
**📧** Contact me | **🔗** [LinkedIn](https://linkedin.com/in/anmisham) | **🌐** [GitHub](https://github.com/anmisha)

***
