# Enterprise Healthcare Analytics Dashboard

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=2E8B57&center=true&vCenter=true&width=900&lines=Enterprise+Healthcare+Analytics+Dashboard;Power+BI+%7C+DAX+%7C+Power+Query+%7C+Excel;Turning+Raw+Healthcare+Data+Into+Actionable+Insights;Executive+Reporting+for+Better+Decisions" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-005C99?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20Query-00A884?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
  <img src="https://img.shields.io/badge/Healthcare%20Analytics-2E8B57?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Business%20Intelligence-1565C0?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pages-4-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DAX%20Measures-6-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data%20Tables-15-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Visuals-10+-brightgreen?style=for-the-badge" />
</p>

---

## Project Overview

This project is an **enterprise healthcare analytics dashboard** designed to convert raw hospital data into **clear, interactive, and executive-ready insights**. It brings together patient data, billing data, insurance distribution, hospital performance, and diagnostic outcomes into one reporting experience.

The goal is simple. Help healthcare stakeholders move from scattered records to **faster decisions, better visibility, and stronger operational control**.

---

## Business Problem

Healthcare organizations deal with high volumes of daily data, but that data is often fragmented across files and systems. Without a centralized analytics layer, it becomes hard to track patient trends, monitor billing performance, compare insurance patterns, and identify operational bottlenecks.

This dashboard solves that problem by creating a single source of truth for healthcare reporting.

---

## Business Value

This dashboard is useful for hospital administrators, analysts, finance teams, and operations leaders because it helps them understand what is happening, why it is happening, and where action is needed.

It supports:

- patient volume monitoring
- revenue and billing visibility
- insurance analysis
- condition-level analysis
- test result review
- executive KPI tracking
- data-driven planning

---

## Dashboard Screens

### Page 1 - Medical Condition Analysis

<p align="center">
  <img src="Images/Medical_Condition.png" width="100%" />
</p>

This page focuses on how patients are distributed across medical conditions, hospitals, and geographies. It helps answer questions about which conditions drive the highest volume and which hospitals are handling the most patients.

### Page 2 - Insurance Distribution Analysis

<p align="center">
  <img src="Images/Insurance_Analysis.png" width="100%" />
</p>

This page shows how insurance providers contribute to healthcare coverage and billing patterns. It highlights provider mix and billing balance across the network.

### Page 3 - Test Result Analysis

<p align="center">
  <img src="Images/Test_Result.png" width="100%" />
</p>

This page evaluates diagnostic outcomes and helps identify normal versus abnormal cases. It is useful for clinical review and risk monitoring.

### Page 4 - Executive KPI Dashboard

This page summarizes the most important healthcare KPIs in one view for quick leadership review and decision-making.

---

## Key KPIs

| KPI | Business Meaning |
|---|---|
| Total Patients | Measures overall patient volume |
| Total Billing | Tracks total revenue activity |
| Average Billing | Shows average financial value per case |
| Total Admissions | Monitors operational throughput |
| Average Length of Stay | Indicates efficiency and care flow |
| Average Age | Helps understand patient demographics |

---

## Key Insights

The analysis shows that some medical conditions contribute more heavily to patient admissions and billing than others. That means resource planning should not be treated evenly across all care categories.

Insurance coverage is also an important driver of financial performance, since provider mix affects billing behavior and revenue visibility.

Most diagnostic reports are normal, but the abnormal cases are the ones that deserve attention because they can reveal quality, operational, or clinical issues.

Hospital-level differences in patient load and billing also suggest that performance is not uniform across the network, which makes comparison and monitoring important.

---

## Business Recommendations

The dashboard can be used to support practical decisions such as:

- prioritizing staffing and resources for high-volume medical conditions
- reviewing abnormal test patterns for risk detection
- comparing hospital billing differences to improve financial strategy
- analyzing insurance mix to understand revenue exposure
- using KPI trends for faster executive reporting
- identifying operational bottlenecks across hospitals

---

## Technology Stack

| Technology | Purpose |
|---|---|
| Power BI | Dashboard development and visualization |
| Power Query | ETL and data transformation |
| DAX | KPI and measure creation |
| Excel | Data preparation |
| Star Schema | Optimized data modeling |
| Business Intelligence | Executive reporting and analysis |

---

## Data Model

The project uses a **star schema** design to improve model performance, reduce complexity, and make reporting more scalable. This structure helps simplify relationships and makes DAX calculations more manageable.

---

## Why Star Schema Was Used

A star schema is a strong fit for this project because it supports:

- faster performance
- cleaner relationships
- simpler reporting logic
- easier scaling
- better maintainability

---

## Dashboard Design Philosophy

The dashboard follows a clean, professional, healthcare-oriented design style. The visual language is kept simple so users can focus on the story instead of getting distracted by unnecessary decoration.

The design priorities are:

- clarity
- readability
- executive friendliness
- interactive exploration
- business storytelling

---

## Features

The dashboard includes:

- interactive report pages
- KPI cards for executive summary
- slicers for filtering
- geographic mapping
- condition-level comparison
- diagnostic analysis
- root-cause style exploration
- cross-filtering across visuals

---

## Project Structure

```text
Enterprise Healthcare Analytics Dashboard
│
├── Images
│   ├── Cover.png
│   ├── Medical_Condition.png
│   ├── Insurance_Analysis.png
│   ├── Test_Result.png
│   └── StarSchema.png
│
├── Data
│   └── Healthcare source files
│
├── Power BI Report
│   └── Healthcare Dashboard.pbix
│
└── README.md
