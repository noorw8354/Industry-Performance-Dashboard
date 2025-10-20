# 🌍 HCP Journey Funnel Analytics & Performance Tracking

## 📊 Project Overview

This project was developed as part of my work at **Haleon**, focusing on **unifying multi-source healthcare data** to analyze and track key performance indicators (KPIs) such as **reach, conversion, and consent rates** across **Middle East and African (MEA)** markets.

The initiative aimed to connect different data sources to a single level of granularity, enabling **a complete view of the HCP (Healthcare Professional) journey** — from engagement to conversion — while monitoring **representative performance** at each stage.

By creating a streamlined **SQL-to-Power BI pipeline**, the process was automated end-to-end, ensuring agility, scalability, and data consistency across markets.

---

## 🧩 Problem Statement

HCP engagement data was fragmented across multiple platforms — CRM systems, communication tools, and consent management databases — each having its own structure and refresh cycle.  
This created challenges in:
- Bringing all datasets to a **common granularity** for accurate performance measurement  
- Tracking **HCP engagement funnel** across different stages  
- Managing **manual refreshes and modeling** within Power BI  
- Providing management with a **real-time view of rep effectiveness**

The solution required a **unified data model** and **automated pipeline** to connect these datasets seamlessly.

---

## 🧠 Approach

- **Developed a comprehensive SQL view** that integrates multiple data sources into a single, harmonized dataset.  
- Aligned data on a **consistent time and entity level** (HCP, rep, and engagement activity).  
- Computed funnel KPIs such as:
  - **Reach Rate**
  - **Conversion Rate**
  - **Consent Collection**
  - **Rep Activity Performance**
- Designed the SQL view to **feed directly into Power BI**, removing the need for heavy data modeling within the BI tool.  
- Enabled **daily automated data refreshes**, ensuring dashboards remain current without manual intervention.

---

## 📊 Key Metrics Tracked

| Metric | Description |
|---------|--------------|
| **Reach** | Number of HCPs engaged across digital and direct channels |
| **Conversion** | Percentage of engaged HCPs taking a defined action (e.g., registration, recommendation) |
| **Consent** | Number of HCPs who granted permission for digital communication |
| **Rep Performance** | HCP engagement effectiveness by representative and market |
| **Funnel Drop-off** | Points in the HCP journey where engagement weakens |

---

## 🛠️ Tools & Technologies

- **SQL (Databricks / BigQuery)** – for multi-source integration, transformations, and view creation  
- **Power BI** – for real-time visualization and performance dashboards  
- **Excel / Python (optional)** – for validation and automation scripts  
- **ETL Scheduling Tools** – to automate daily refreshes  

---

## 📈 Outcome / Impact

- Unified all major HCP-related data sources into a single, consistent analytical layer.  
- Reduced manual data modeling effort by integrating SQL directly with Power BI.  
- Enabled **real-time funnel visibility** and **rep performance tracking** for leadership teams.  
- Automated daily data updates — saving time and ensuring up-to-date insights.  
- Improved focus and decision-making through **connected, actionable analytics**.  

---

## 🔒 Confidentiality Note

Due to company data protection and confidentiality policies, raw datasets and exact KPIs are not shared.  
This repository highlights the **data architecture, methodology, and automation approach** used to optimize the HCP engagement funnel.

---

## 👤 Author

**Noor Wali**  
Expert Data Analyst – MEA | Haleon  
[LinkedIn](https://www.linkedin.com/in/noor-wali-9ba671175/) | [GitHub](https://github.com/noorw8354)

---

### 🔖 Tags
#Haleon #SQL #PowerBI #DataAnalytics #SalesForceAnalytics #HCPJourney  
#RepPerformance #FunnelOptimization #PerformanceTracking #DataDrivenDecisions #Automation #KPItracking
