# SVI-Equity-Analysis-
An automated Power BI report and tool to track equity on the tract level and measure the program impact in the City of Portland. The Report highlights all the areas with their SVI scores and the program participation in that area. The Clean River Rewards is a discount program from the City of Portland to promote equity in utility bills.

**Reference: City of Portland – Equity Data Toolkit**
https://www.portland.gov/water/equity#toc-the-equity-data-toolkit

**Confidentiality Notice**
This project was completed using sensitive organizational data. All descriptions in this repository are intentionally high-level. No proprietary data, internal files, or screenshots are included.

**Goal**
The goal was to integrate multiple internal datasets into a single, interactive Power BI report that allows stakeholders to identify patterns, prioritize properties, and explore equity-related indicators efficiently.

Program Context: Clean River Rewards
Clean River Rewards is a city program designed to encourage property owners to adopt stormwater management practices. Participation gaps were observed across neighborhoods, particularly in areas facing higher social vulnerability.
The dashboard was built to help the organization:
  Focus outreach efforts on vulnerable communities
  Move beyond identifying where vulnerability exists to understanding what drives it
  Design targeted, equitable engagement strategies rather than one-size-fits-all outreach

**Problem Statement**
The organization relied on manual, fragmented reporting across multiple data sources, making it difficult to:
  Analyze properties consistently across equity and vulnerability metrics
  Identify high-priority cases efficiently
  Provide leadership with a clear, repeatable reporting structure
  Build an automated look-up tool to see the vulnerability health of a tract
The challenge was to design a scalable analytics solution that could consolidate data, improve interpretability, and reduce reporting friction.

**My Role**
I served as the primary analyst on this project and was responsible for:
  Data collection and compilation
  Data integration, cleaning, and modeling
  Dashboard design and metric definition
  Translating analytical outputs into decision-support visuals for non-technical stakeholders

**Data & Inputs** 
The report integrated multiple internal datasets, including:
  Property and taxlot-level records
  Customer or account-level attributes
  Clean River Rewards customer data 
  Equity-related indicators
  Social Vulnerability Index (SVI) metrics
All data relationships were modeled to support property-level and geographic analysis.

**Methodology**
Cleaned and standardized input data using SQL and Power BI Power Query
Designed a relational data model to connect the property, account, and equity tables
Created calculated measures to support equity scoring and prioritization logic (DAX)
Implemented interactive filters, slicers, and drill-down functionality
Designed visuals to highlight spatial patterns and equity-driven insights

**Tools & Technologies**
Power BI (data modeling, DAX measures, interactive dashboards)
SQL (joining, cleaning, data validation, preprocessing)
Analytical Design (equity-focused metric framing and prioritization logic)

**City-Level Impact & Equity Use Case**
A key strength of the dashboard is its ability to identify drivers of vulnerability, not just vulnerability scores. This directly informs how outreach is conducted within the Clean River Rewards program.

Examples of how insights are used:
  When socioeconomic factors drive vulnerability, outreach teams can prioritize financial     assistance, guidance, and documentation support
  When language barriers are a contributing factor, messaging can be adapted and delivered in appropriate languages
  When housing or access-related factors dominate, outreach can focus on eligibility clarification and program education
  This approach enables the city to move from generalized outreach to targeted, barrier-specific engagement, improving equity and program effectiveness.

**Outcomes & Impact**
Streamlined reporting workflows for internal teams
Improved visibility into equity and vulnerability patterns
Enabled faster, more consistent decision-making for leadership
Reduced reliance on ad-hoc manual analysis

**Limitations**
Due to tract-level analysis, some vulnerable customers in low-vulnerability areas might be underrepresented. To overcome this, we will need different measures of vulnerability other than the tract SVI score. 

**Skills Demonstrated**
Applied Power BI data modeling and dashboard design
Social Vulnerability Index analysis
Equity-driven decision support
Responsible handling of sensitive public-sector data
Translating analytics into real-world program action
