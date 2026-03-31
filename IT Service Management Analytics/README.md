# Application Service Request Analytics Dashboard
### SQL Server → Power BI | Weekly Refresh | Operational Insights

##  Overview
This project analyses 5,000+ annual application service requests using SQL Server as the data source and Power BI as the reporting layer. The dashboard provides insights into ticket trends, SLA performance, agent workload, and recurring issues.

##  Data Architecture

Source: SQL Server
Model: Fact tables (Requests, SLA, Type Mapping) + Dimension tables (Category, Priority, Employee)
Refresh: Weekly scheduled refresh
Schema: Star‑schema with clean relationships

## 📊 Dashboard Features

Monthly Ticket Trend
Prioritywise Distribution
Categorywise Ticket Trend
Top 10 Users
Agentwise Analysis
Ticket Type Distribution
SLA & Backlog KPIs

## 📈 Key Insights

Problem category = 64.6% of all tickets
Timesheet Deletion is the top recurring issue
Ticket volume peaks May–August
High‑priority tickets follow the same pattern
Two agents handle majority of workload
Small group of users generate disproportionate tickets

## Recommendations

Automate repetitive categories
Introduce self‑service for common issues
Rebalance agent workload
Targeted user training
Capacity planning for peak months

## 🛠️ Tech Stack
SQL Server • Power BI Desktop • Power BI Service • DAX • Data Modelling

📄 Case Study
A full case study is included in the repository.
