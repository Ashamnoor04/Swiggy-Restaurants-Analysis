# Swiggy-Restaurants-Analysis
#📊 Swiggy Restaurant Analysis: A Business Intelligence Project 🚀
#Project by Ashamnoor Singh
#📌 Project Overview
This project is an end-to-end Business Intelligence solution designed to analyze the Swiggy restaurant dataset. The primary objective is to transform raw, unstructured data into actionable strategic insights. By leveraging MySQL for data processing and Power BI for visualization, this project identifies key market trends, benchmarks restaurant performance across various cities, and uncovers opportunities for business growth in the competitive food delivery ecosystem.

💻 Technology Stack
Database: 💾 MySQL Server

Database Management: 🧰 MySQL Workbench

Business Intelligence & Visualization: 📈 Microsoft Power BI

⚙️ Methodology & Data Flow
The project followed a structured, database-centric BI workflow:

➡️ Data Ingestion: A large CSV dataset (~8000 rows) was loaded into a MySQL database using the LOAD DATA LOCAL INFILE command, skillfully navigating and resolving initial security and configuration challenges.

✨ Data Cleaning & Transformation (SQL): All data cleaning was performed directly within MySQL. This included handling null values, removing whitespace with TRIM(), and standardizing data types to ensure analytical integrity.

🔍 Exploratory Data Analysis (SQL): A comprehensive analysis was conducted using a suite of SQL queries, from basic aggregations to advanced queries using CASE statements and CTEs, to extract key business metrics.

🎨 Dashboarding (Power BI): The cleaned data was connected to Power BI to build an interactive, multi-faceted dashboard designed for strategic decision-making.

Data Flow:
Raw CSV File ➡️ MySQL Workbench (Ingestion) ➡️ MySQL DB (Cleaning & Analysis) ➡️ Power BI (Visualization)

🖼️ The Interactive Dashboard
The final output is a dynamic, single-page dashboard designed for a business leader. It provides a high-level executive summary and allows for deep-dive analysis into specific markets using interactive slicers.



<img width="1920" height="1019" alt="Power BI Desktop 13-10-2025 1_10_21" src="https://github.com/user-attachments/assets/b0353c5e-4219-4d74-8f7b-d73ca10bf1e7" />

💡 Key Business Insights from the Analysis
1. 🏆 Significant Disparity in Market Quality
The analysis revealed a clear difference in average restaurant ratings across major cities. Southern cities like Chennai (avg. rating 3.78) and Bangalore (3.76) lead in quality, while markets like Delhi (3.53) show a clear opportunity for quality improvement initiatives.

2. 💰 Price Does Not Directly Correlate with Higher Satisfaction
A critical insight: "Premium" priced restaurants (avg. rating 3.79) are only marginally higher-rated than "Mid-Range" (3.64) and "Budget" (3.60) options. This indicates that customers find high value in affordable restaurants, presenting a key marketing opportunity to highlight "Top-Rated Budget Eats."

3. 🍜 Market Concentration in Core Cuisines
The market is heavily saturated with Indian and Chinese cuisine listings. While this shows strong demand, it also points to intense competition, creating an opportunity for Swiggy to promote and differentiate emerging or niche cuisines on its platform.

✨ SQL Analysis Highlights
All analytical queries used to generate these insights are available in the analysis_queries.sql file in this repository. The analysis includes:

Geographic distribution analysis 🗺️

Performance benchmarking by city and price category 🏙️

Cuisine popularity and saturation analysis 🍝
