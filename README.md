# YouTube-Channel-Analysis-PowerBI
Interactive dashboard on global YouTube channel performance using data visualization (Power BI).

📊 YouTube Data Analysis & Business Intelligence Dashboard 📈

Project Summary: A comprehensive, interactive dashboard developed in Power BI to analyze global YouTube channel performance, including uploads, view ranks, subscriber growth, and channel type demographics. This project demonstrates proficiency in data transformation (Power Query), DAX calculations, and impactful data storytelling.

Key Technologies: 🖥️ Power BI Desktop, ⚙️ Power Query (M Language), 🧮 DAX (Data Analysis Expressions)
Primary Dataset: 🌐 Global YouTube Channel Data (including uploads, views, subscribers, and ranks)
Purpose: 🎯 Deliver actionable insights on channel performance and content strategy.
Status: ✅ Complete (Includes PBIX file and Exported Report)

**1. Project Overview 🌟**

This project served as a capstone to deliver a production-ready Business Intelligence solution. The primary goal was to transform raw YouTube metrics into a set of interactive visualizations that answer critical business questions about success factors on the platform. The solution emphasizes dashboard design best practices, robust data cleansing, and the creation of custom performance metrics using DAX.

**2. Key Features 🔑**

➡️ Interactive Dashboards: Implemented cross-filtering and drill-through capabilities across multiple pages for dynamic analysis. 🖱️

➡️ Custom DAX Metrics: Calculated essential KPIs such as Average Views, Minimum View Ranks, and metrics for Channel Views by Subscriber Ratio. 🧮

➡️ Data Cleansing Pipeline: Used Power Query to handle data quality issues, including cleansing and transforming time-series data to calculate rolling averages (e.g., Average Views for the Last 30 Days). 🧼

➡️ Visual Storytelling: Designed the report with clear visual hierarchy, consistent color palettes, and appropriate visual types (e.g., Card visuals for KPIs, Bar charts for channel comparisons). 🎨

**3. Business Questions Answered 💡**

The dashboard provides answers to key strategic questions:

Performance Extremes: What are the maximum uploads and minimum view ranks across the dataset?
Channel Performance: How do views and subscriber counts correlate across different channel types (e.g., News vs. Entertainment)?
Growth Trends: What are the average views for the most recent period, showing immediate performance?
Upload Leaderboard: Which specific channels have the highest total uploads?

**4. Technical Implementation 💻**

   Technologies Used

   👉 Platform: 🖥️ Power BI Desktop
   
   👉 Data Modeling: Star Schema / Normalized Data Model (as applicable)
   
   👉 Data Transformation: Power Query (Extract, Transform, Load processes)

 Dataset

  Name: Top Global YouTubers Data.

  Characteristics: Structured data containing metrics like channel name, type, upload count, video views, subscriber counts, and historical rank data.

Methodology

  ✅ Data Acquisition: Connected Power BI to the raw data source.
  
  ✅ Data Transformation (Power Query): Applied necessary steps to clean headers, enforce data types, and create calculated columns for time-based analysis. 🧼
  
  ✅ Data Modeling: Defined relationships between tables (if multiple tables were used) and managed data cardinality.
  
  ✅ DAX Calculations: Wrote complex measures to aggregate, filter, and calculate custom metrics.
  
  ✅ Report Design: Developed three primary report pages, ensuring responsiveness and user experience. 📊

**5. Key Insights & Findings 📖**

  🌟 Top Channel Types: Identified the channel types that generated the highest total views per subscriber, suggesting which categories offer the highest audience engagement.

  🌟 Upload vs. Views: Analyzed the relationship between upload frequency and video performance metrics.

  🌟 KPI Performance: Presented core metrics (Max Uploads: 301K, Min View Rank: 1) prominently for immediate business assessment.

**6. How to View ⚙️**

  👉 Option 1: Live Demo (Recommended):

   Click the "Launch Dashboard Demo" button on the GitHub Pages link (once enabled) to view a static gallery of the key visuals.

  👉 Option 2: Download the PBIX:

   Download the Lakshmi_PowerBI_Project_Report.pbix file from this repository and open it using Power BI Desktop to interact with the full dashboard.

  👉 Option 3: View Static PDF:

   Refer to the Lakshmi_PowerBI_Project_Report.pdf file in this repository for a static view of the final report pages.

**7. File Structure 📂**

.
├── Lakshmi_PowerBI_Project_Report.pbix  # The main Power BI project file (full report & logic)
├── Lakshmi_PowerBI_Project_Report.pdf  # Static PDF export of the final report
├── README.md                            # Project documentation (This file)
└── index.html                           # Live GitHub Pages demo launcher



**8. Future Enhancements ✨**

  💡 Web Embedding: Embed the final report using Power BI Service into a public webpage or portfolio site for instant viewing. 🌐

  💡 Advanced DAX: Implement time intelligence functions (Year-over-Year growth, Moving Averages) to provide deeper trend analysis.

  💡 Row-Level Security (RLS): Apply RLS if the data were to be deployed to ensure different users see only relevant regional or channel data.

**9. Author ✍️**

Lakshmi Bhavani Reddy

lakshmibhavani071200@gmail.com | https://www.linkedin.com/in/lakshmibhavanireddy37/


This project demonstrates the practical application of Business Intelligence tools in data storytelling, showcasing end-to-end data analysis workflow from data ingestion and modeling to delivering actionable business insights.
