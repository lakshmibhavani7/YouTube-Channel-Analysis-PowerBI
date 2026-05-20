# YouTube Channel Performance Dashboard

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat&logo=microsoft&logoColor=white)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat&logo=microsoft&logoColor=white)](https://powerbi.microsoft.com/)

---

## Project Overview

Built a 3-page interactive Power BI dashboard analyzing global YouTube channel performance across uploads, views, subscribers, and channel type demographics.

- Total uploads analyzed: **9M+**
- Maximum uploads by channel: **301K**
- Average views tracked: **169.33M**
- Minimum view rank: **1**
- Channel types analyzed: **14**
- Top category by subscribers: **Entertainment (6.26bn)**
- Second category by subscribers: **Music (5.20bn)**

> This project was completed as a Capstone Project under the Advanced Certification in Data Science and AI — IIT Roorkee and Intellipaat.

---

## Tools and Technologies

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard design and report publishing |
| Power Query (M Language) | Data cleaning and ETL process |
| DAX (Data Analysis Expressions) | Custom metrics and calculated columns |

---

## Dataset

- Name: Global YouTube Statistics
- Content: Channel name, type, upload count, video views, subscriber counts, and rank data
- Files: Global YouTube Statistics.csv (raw) and Cleaned Global YouTube Statistics.csv (processed)

---

## Folder Structure

- Cleaned Global YouTube Statistics.csv — Processed dataset
- Global YouTube Statistics.csv — Raw dataset
- Lakshmi PowerBI Project Report.pbix — Power BI dashboard file
- Lakshmi PowerBI Project Report.pdf — Static PDF export of dashboard
- Capstone Project Document.pdf — Project documentation
- README.md — Project description

---

## Key Steps

**1. Data Cleaning (Power Query)**
- Cleaned headers and enforced correct data types
- Handled missing and inconsistent values
- Created calculated columns for time based analysis

**2. DAX Calculations**
- Created Views per Subscriber calculated column
- Built measures for Average Views, Maximum Uploads, and Minimum View Ranks
- Developed channel type performance aggregations

**3. Dashboard Design (3 Pages)**

Page 1 — Upload and Performance Overview
- KPI cards for Total Uploads (9M), Maximum Uploads (301K), Minimum View Ranks (1), Average Views (169.33M)
- Line chart showing top channels that crossed 2 lakh uploads
- Channel views by subscriber table across all channel types

Page 2 — Category Rankings
- Rank wise category analysis showing Entertainment (287 channels) and Music (202 channels) as top categories
- Interactive navigation buttons between pages

Page 3 — Subscriber and Channel Type Analysis
- Bubble chart showing subscribers by category — Entertainment (6.26bn) and Music (5.20bn) as leaders
- Radar chart showing channel type rank distribution across 14 categories

---

## Key Insights

- Entertainment is the highest engagement category with 149,081 views per subscriber
- Entertainment leads in total subscribers (6.26bn across 287 channels)
- Music is second with 5.20bn subscribers across 202 channels
- News channels dominate upload counts but have lower subscriber engagement
- Views per subscriber ratio reveals which categories offer highest audience loyalty

---

## Business Impact

- Helps content creators identify high performing categories for channel growth
- Supports strategic decisions on content type and upload frequency
- Reveals which channel types generate highest subscriber engagement
- Enables data driven content strategy planning based on global trends

---

## How to View

- Download the Lakshmi PowerBI Project Report.pbix file and open in Power BI Desktop
- View the static Lakshmi PowerBI Project Report.pdf for a quick overview without Power BI

---

## Author

**Lakshmi Bhavani Reddy**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshmibhavanireddy37/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/lakshmibhavani7)
