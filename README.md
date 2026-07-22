# 🚀 Automated Supply Chain Analytics Pipeline

An end-to-end automated supply chain analytics pipeline built using **n8n**, **Supabase PostgreSQL**, and **Quadratic AI**. The project automates the ingestion of supply chain CSV files from Gmail into a cloud-hosted PostgreSQL database, where Quadratic AI performs data analysis to generate KPI dashboards, customer performance reports, visualizations, and business insights through a low-code workflow.

---

# 📖 Overview

Supply chain teams often receive operational data as CSV files through email, requiring repetitive manual imports before analysis. This project demonstrates how workflow automation, cloud databases, and AI-assisted analytics can streamline this process.

Using **n8n**, incoming CSV files are automatically detected, extracted, and loaded into a **Supabase PostgreSQL** database. **Quadratic AI** then connects directly to the database to analyze the data, generate visualizations, calculate key supply chain KPIs, and produce actionable business insights using natural language prompts.

---

# 🎯 Project Objectives

- Automate supply chain data ingestion using a low-code workflow.
- Build a repeatable ETL pipeline with minimal manual intervention.
- Store structured supply chain data in a cloud-hosted PostgreSQL database.
- Generate KPI dashboards using AI-assisted analytics.
- Identify operational trends and customer performance insights.
- Demonstrate an end-to-end analytics workflow using modern automation tools.

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **n8n** | Workflow Automation |
| **Gmail Trigger** | Automated CSV Detection |
| **Supabase** | Cloud Platform |
| **PostgreSQL** | Cloud-hosted Relational Database |
| **Quadratic AI** | AI-assisted Analytics, Visualization & Business Insights |

---

# 🏗️ Solution Architecture

<p align="center">
  <img src="images/architecture.png" width="900">
</p>

---

# 🔄 Workflow Automation

The automated workflow performs the following steps:

1. Monitors Gmail for incoming supply chain CSV files.
2. Extracts CSV attachments automatically using **n8n**.
3. Loads structured data into a **Supabase PostgreSQL** database.
4. Connects **Quadratic AI** to the PostgreSQL database.
5. Generates KPI dashboards, customer performance reports, charts, and business insights using AI.

<p align="center">
  <img src="images/n8n-workflow.png" width="900">
</p>

---

# 📊 Data Processing Summary

During this implementation:

| Metric | Value |
|---------|------:|
| CSV Files Processed | **2** |
| Records Loaded | **166** |
| Dataset 1 | **57 Records** |
| Dataset 2 | **109 Records** |

The workflow automatically processed incoming CSV files and loaded **166 records** into a cloud-hosted PostgreSQL database, eliminating manual data loading and creating a centralized data source for AI-assisted analytics.

---

# 📈 Supply Chain KPIs

Quadratic AI generated the following operational KPIs from the stored supply chain data.

| KPI | Value |
|------|------:|
| Total Orders | **572** |
| Total Order Lines | **1,000** |
| Line Fill Rate | **62.30%** |
| Volume Fill Rate | **96.54%** |
| On-Time Delivery | **61.54%** |
| In-Full Delivery | **47.73%** |
| OTIF (On-Time In-Full) | **27.80%** |

<p align="center">
  <img src="images/overall-kpi-dashboard.png" width="900">
</p>

---

# 🌎 Customer Performance Analysis

The project compares fulfilment performance across high-value customers using three operational metrics:

- OTIF
- In-Full Delivery
- On-Time Delivery

---

## 🇺🇸 USA Customer Performance

<p align="center">
  <img src="images/usa-customer-performance.png" width="900">
</p>

### Key Findings

- **Best Market** generated the highest order value (**3.09M**) while achieving an OTIF of **40.00%**.
- **Lidl** and **Foodtown** recorded the lowest OTIF values (**16.67%**) despite generating over **2.29M** in order value.
- Most customers maintained relatively strong On-Time Delivery, but lower In-Full performance reduced overall OTIF.
- High-value customers present opportunities for improving fulfilment performance.

---

## 🇮🇳 India Customer Performance

<p align="center">
  <img src="images/india-customer-performance.png" width="900">
</p>

### Key Findings

- Within the analysed customer sample, OTIF ranged from **38.89%** to **61.54%**.
- **Rel Fresh** achieved the highest OTIF (**61.54%**).
- **Logic Stores** recorded the highest On-Time Delivery (**81.2%**).
- **Info Stores** achieved the highest In-Full Delivery (**75.0%**).
- Compared with the analysed USA customer sample, the Indian customer sample demonstrated stronger fulfilment performance.

---

# 🤖 AI-Assisted Analytics

Quadratic AI was connected directly to the PostgreSQL database and used natural language prompts to generate:

- Supply chain KPI dashboards
- Customer performance reports
- Regional comparisons
- Interactive charts
- Business insights
- Operational recommendations

This demonstrates how AI-assisted analytics can accelerate business reporting without requiring complex dashboard development.

---

# 💡 Business Insights

The analysis highlighted several opportunities to improve operational performance.

### OTIF Performance

The overall **OTIF** was **27.80%**, considerably lower than both:

- **On-Time Delivery (61.54%)**
- **In-Full Delivery (47.73%)**

This indicates that relatively few customer orders met both delivery conditions simultaneously.

---

### Inventory Fulfilment

The **Line Fill Rate (62.30%)** was substantially lower than the **Volume Fill Rate (96.54%)**, suggesting that while most requested product quantities were supplied, not all requested product lines were fulfilled completely.

---

### Customer Performance

Several high-value customers generated significant revenue while recording comparatively lower OTIF values, highlighting opportunities to improve fulfilment performance for strategic accounts.

---

### Regional Comparison

Within the analysed customer samples, India's top customers demonstrated stronger OTIF performance than the USA sample, suggesting operational differences that warrant further investigation.

---

# 📌 Business Recommendations

Based on the analysis, the following opportunities were identified:

- Investigate warehouse operations, inventory availability, and delivery scheduling to improve OTIF performance.
- Improve inventory planning and replenishment strategies to increase the Line Fill Rate.
- Prioritise fulfilment improvements for high-value customers to strengthen customer satisfaction and retention.
- Investigate regional operational practices to identify best practices that could be adopted across markets.
- Continue automated KPI monitoring using the workflow to support timely, data-driven operational decisions.

---

# 📂 Repository Structure

```
automated-supply-chain-analytics-pipeline
│
├── README.md
├── Screenshots/
│   ├── architecture.png
│   ├── N8N workflow.png
│   ├── overall-kpi-dashboard.png
│   ├── usa-customer-performance.png
│   └── india-customer-performance.png
│
├── workflow/
│   └── N8N workflow.json
│
└── data/
    └── README.md
```

---

# 🎯 Skills Demonstrated

- Workflow Automation
- Low-Code Development
- ETL Pipeline Development
- n8n
- Supabase
- PostgreSQL
- Cloud Databases
- Data Integration
- AI-Assisted Analytics
- Prompt Engineering
- Supply Chain Analytics
- Business Intelligence
- Data Visualization

---

# 🚀 Future Enhancements

- Incremental data loading
- Scheduled workflow execution
- Automated data validation
- AI-powered anomaly detection
- Power BI integration
- Automated reporting workflows

---

## 👨‍💻 Author

**Vikranthnivas Dhamodharan**

Master of Analytics | Massey University

Passionate about Data Analytics, Workflow Automation, Cloud Technologies, and AI-assisted Business Intelligence.

