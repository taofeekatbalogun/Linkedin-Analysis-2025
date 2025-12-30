# Linkedin-Analysis-2025

## Project Overview
This project is a **Power BI dashboard** built to track and analyze personal LinkedIn performance using a **KPI-first approach**.  
The goal is to understand **visibility, engagement, and audience growth**, and how these metrics relate to one another over time.

The dashboard is designed to **update automatically** as new LinkedIn data is added, requiring no changes to visuals or DAX logic.

---

## Objectives
This dashboard answers the following key questions:
- Am I visible enough on LinkedIn (Impressions)?
- Does visibility translate into interaction (Engagement Rate)?
- How is my audience growing over time (Followers)?
- Which months performed best across key KPIs?

---

## KPIs Tracked
The dashboard focuses on four core LinkedIn performance metrics:

### Impressions
- Total Impressions
- Monthly Impressions trend
- Used to measure overall visibility and reach

### Engagements
- Total Engagements
- Monthly Engagement trend
- Indicates how audiences interact with content

### Engagement Rate
- Engagements ÷ Impressions
- Evaluates whether impressions convert into interaction

### Followers
- Total Followers
- Monthly New Followers
- Tracks audience growth over time

Each KPI section includes:
- A summary KPI card
- A monthly bar chart
- A short insight text explaining performance

---

## Data Sources
Data was extracted directly from **LinkedIn Analytics**, including:
- Profile Analytics (Impressions & Engagements)
- Followers data
- Demographics summary

Data was exported in Excel/CSV format from LinkedIn and loaded into Power BI.

---

## Data Preparation
- Cleaned and transformed data using **Power Query**
- Built a dedicated **Date dimension table** to support time-based analysis
- Structured the model using a **star schema**:
  - Engagement (Fact)
  - Followers (Fact)
  - Date (Dimension)

---

## Key DAX Measures
Core measures used in the dashboard include:
- Total Impressions  
- Total Engagements  
- Engagement Rate  
- Total Followers  
- New Followers  

All measures are written to remain **scalable and reusable** as new data is added.

---

## How to Update the Dashboard
1. Replace the LinkedIn export files with updated versions
2. Open the Power BI file
3. Refresh the data

All KPIs, charts, and insights update automatically.

---

## Design Philosophy
This dashboard follows a **KPI-first design approach**, prioritizing:
- Clarity over clutter
- Business questions over visuals
- Fast insight consumption
- Recruiter-friendly storytelling

The structure is inspired by executive dashboards and personal branding analytics use cases.

---

## Tools Used
- Power BI
- DAX
- Power Query
- Excel (LinkedIn data exports)

---

## Author
**Taofeeqah Balogun**  
Data Analyst | Power BI | Data Analytics | Data Visualization



