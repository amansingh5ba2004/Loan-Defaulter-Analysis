Global Terrorism Analysis: Enhanced Overview
Project Objective
This project delivers in-depth analysis of global terrorism trends by leveraging SQL for robust data processing and Power BI for dynamic data visualization. The goal is to transform raw terrorism incident data into actionable intelligence that supports forecasting, strategic planning, and risk mitigation.

Project Architecture
SQL Database (terrorism_analysis):

Comprehensive storage and manipulation of terrorism data.

Efficient data cleaning, normalization, and extraction via advanced SQL queries.

Power BI Reporting:

Interactive dashboards for pattern discovery and communication of insights to stakeholders.

Dataset Composition
The dataset comprehensively documents global terrorist incidents with each record including:

Event Metadata:

Event ID, Date (Year, Month, Day)

Location hierarchy: Country, Region, City

Incident Details:

Attack Type, Target, Weapon Used

Casualties (Killed, Wounded)

Motive and Analytical Summary

SQL Implementation & Data Engineering
Database Setup:

Created terrorism_analysis for centralized management.

Table & Data Loading:

Defined terrorism_data schema tailored for analytics.

Employed the SQL COPY command for efficient CSV data ingestion.

Data Cleansing:

Systematically checked for missing and anomalous values.

Removed incomplete or inconsistent records to maintain data integrity.

Standardized categorical fields (e.g., attack type, weapon) for consistency and improved analysis.

Analytical Query Examples:

Total number of attacks and global casualty counts.

Time series aggregation for both yearly and monthly incident analysis.

Extraction of prevalent attack types and common targets.

Spatial and temporal filtering to support geographic heatmaps.

Power BI Visualization Strategy
Power BI was used to craft visually compelling dashboards featuring:

Temporal Trends:

Line and area charts showing attack frequency and casualties over years and months for trend analysis and anomaly detection.

Geographic Insights:

Choropleth and heatmaps visualizing spatial attack concentrations by country and region.

Incident Profiling:

Treemaps and bar charts highlighting predominant attack types, weapon usage, and target profiles.

Impact Analysis:

Region-wise matrices of casualties, enabling root-cause and hotspot analysis.

Interactive Exploration:

Drill-down and filter capabilities to empower users to explore subsets (e.g., by region, period, or attack type).

Key Insights
Regional Hotspots: High incident counts in specific regions reflecting socio-political instability and active conflict zones.

Weapon and Attack Patterns: Certain weapon types (e.g., explosives, firearms) and attack styles (e.g., bombing, armed assault) were disproportionately used, correlating to higher casualty rates.

Temporal Shifts: Noticeable month-to-month and year-to-year volatility in terrorism activity, with identifiable clusters and seasonal trends.

Target Vulnerabilities: Civilian and infrastructure targets remain the most frequently affected, informing resource allocation for prevention.

Evolving Motives: Shifts in motive and tactics indicate adaptation by perpetrators over time.
