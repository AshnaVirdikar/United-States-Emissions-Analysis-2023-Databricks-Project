# United-States-Emissions-Analysis-2023-Databricks-Project
Analyzed United States emissions data (2023) sourced from the EPA, built entirely using Databricks to demonstrate end-to-end capabilities in Databricks:
Overview

This project analyzes United States emissions data (2023) sourced from the EPA, built entirely using Databricks to demonstrate end-to-end capabilities in:

Data Engineering (ETL pipelines)
SQL Analytics
Dashboarding
AI-powered querying using Databricks Genie

The goal was to simulate a real-world analytics workflow, transforming raw environmental data into actionable business insights.

🛠️ Tech Stack
Databricks (Lakehouse Platform)
PySpark (ETL & Data Processing)
SQL (Analytics & Aggregations)
Delta Lake (Storage Layer)
Databricks SQL Dashboarding
Databricks Genie (AI-driven insights)

💡 Key Insights
Emissions are highly concentrated in a few states (~51%)
Urban areas show lower per capita emissions, likely due to efficiency
Certain counties contribute disproportionately → policy targeting opportunity

🎯 Business Relevance
This project mirrors real-world use cases in:
Sustainability analytics
Policy decision-making
Operational efficiency tracking

📌 What This Project Demonstrates
End-to-end Databricks proficiency
Strong SQL + PySpark integration
Ability to convert raw data → business insights
Experience with modern data stack (Lakehouse + AI)

Data Pipeline Architecture
🔹 1. Data Ingestion (Bronze Layer)
Imported EPA emissions dataset (CSV format)
Stored raw data in Delta Lake tables
Ensured schema consistency and basic validation

🔹 2. Data Transformation (Silver Layer)
Cleaned and standardized data using PySpark
Handled missing/null values
Created derived fields:
Emissions per capita
State-level aggregations
Removed duplicates and ensured data quality

🔹 3. Aggregation & Modeling (Gold Layer)
Built analytical tables using Databricks SQL
Key metrics:
Total emissions
Avg emissions per person
Population distribution
Top contributing states

📊 Dashboard Highlights

The dashboard provides a multi-dimensional view of emissions across the U.S. in 2023.

🔹 Key KPIs (North Star KPIs)
Total US Emissions: 562.46M
Avg Emissions per Person: 1.77
Total Population: 318.6M
Top 10 States Contribution: 50.9%

🔹 Visual Insights
Geospatial Map: Emissions distribution across locations
Scatter Plot: Emissions vs Population
Insight: Higher population areas tend to have lower per capita emissions
Top Contributing States (Donut Chart):
~51% emissions concentrated in top 10 states
Top Counties (Bar Chart):
Identifies high-emission regions for targeted interventions

🤖 Databricks Genie (AI Layer)
Enabled natural language querying on the dataset
Example: “Which states contribute most to emissions?”
“What is the trend between population and emissions per capita?”

This demonstrates how business users can extract insights without writing SQL.
