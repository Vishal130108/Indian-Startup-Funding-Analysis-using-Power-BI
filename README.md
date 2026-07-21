**Indian Startup Funding Analysis using Power BI**

**1. Project Overview**
   
The Indian Startup Funding Analysis Dashboard is an interactive Business Intelligence solution developed using Microsoft Power BI to analyze startup funding trends across India.

The project demonstrates an end-to-end Business Intelligence workflow, including data preparation, Power Query transformations, DAX-based business metrics, interactive dashboard development, and analytical storytelling.

The dashboard enables users to explore startup funding patterns across industries, investors, cities, and business categories while identifying funding trends over time. It provides stakeholders with a centralized view of the Indian startup ecosystem to support data-driven decision-making.

**2. Data Sources**
   
Dataset Information
Item	Details
Dataset Name	Indian Startup Funding Dataset
Source	GitHub Open Dataset Repository
Repository	AI-ML-projects
Original File	startup_funding.csv
Domain	Startup Ecosystem / Business Analytics
Geographic Coverage	India
File Format	CSV

**3. Project Objectives**
   
Analyze total startup funding across India.
Identify the highest-funded startups.
Analyze funding trends over multiple years.
Compare funding across different business categories.
Identify leading investors in the Indian startup ecosystem.
Analyze startup distribution across Indian cities.
Develop an interactive Power BI dashboard for business users.
Support investment analysis through data-driven insights.

**4. Attribute (Column / Feature) Details**

| Attribute Name | Data Type | Description |
|---------------|-----------|-------------|
| Startup Name | Text | Name of the startup |
| Business Category / Industry Vertical | Text | Startup industry or business sector |
| City | Text | Startup headquarters location |
| Investors | Text | Investor(s) who funded the startup |
| Funding Amount (USD) | Decimal | Funding received by the startup |
| Funding Date | Date | Date of investment |
| Investment Type | Text | Type of funding round |

**5. Tools & Technologies**
   
Microsoft Excel – Initial data exploration and validation.
Power Query – Data cleaning and transformation.
Microsoft Power BI Desktop – Data modeling, DAX calculations, interactive dashboard development, slicers, and business reporting.
DAX (Data Analysis Expressions) – Business metric calculations.
Data Modeling – Single-table data model for efficient data analysis and reporting.
Interactive Visualizations – Business reporting and storytelling.

**6. Data Pre-Processing (Power Query)**

Tasks Performed
Imported startup funding dataset into Power BI.
Validated data types for all columns.
Removed duplicate records where applicable.
Handled missing values and standardized data formats.
Renamed columns using business-friendly naming conventions.
Created calculated fields where required.
Organized the dataset for efficient reporting.
Optimized the data model for improved dashboard performance.

**7. Data Modelling and DAX (Power BI)**

Data Model

The project utilized a single-table data model, eliminating the need for relationships between multiple tables. The dataset was structured and optimized through Power Query to support efficient analysis and reporting within Power BI.

Since all required attributes were available in a single table, no additional data modeling or relationship creation was necessary.

DAX Measures Created

The following business measures were developed using DAX:

Total Funding (USD)
Total Startups
Total Investors
Total Cities
Average Funding per Startup

These measures were used to generate key performance indicators (KPIs) and support interactive dashboard visualizations.

**8. Analysis and Visualizations (Power BI)**

Interactive Dashboard Features

The dashboard was designed with interactive capabilities to enable users to explore startup funding data dynamically.

Business Category Slicer – Enables users to filter the entire dashboard based on startup business categories.
Cross-filtering & Cross-highlighting – Selecting a data point in one visual automatically updates related visuals across the dashboard.
Interactive Map Analysis – Users can explore startup funding geographically across Indian cities.
Dynamic KPI Cards – KPI values update automatically based on user selections and applied filters.
Responsive Visualizations – All charts respond dynamically to slicer selections, providing contextual insights.

**Line Chart**

Startup Funding Trend Over Time

Analyzes yearly funding trends to identify growth and fluctuations in startup investments.

**Map Visualization**

City-wise Startup Funding

Displays the geographical distribution of startup funding across Indian cities.

**Bar Chart**

Top 10 Funded Startups

Highlights startups receiving the highest investment.

**Column Chart**

Top Industries by Funding

Compares funding received across major business sectors.

**Treemap**

Funding by Business Category

Visualizes funding distribution across different startup categories.

**Bar Chart**

Top Investors

Identifies investors contributing the highest funding amounts.

Interactive Features
Business Category Slicer
Cross-filtering across visuals
Interactive dashboard navigation
Dynamic data exploration

<img width="980" height="561" alt="image" src="https://github.com/user-attachments/assets/9cb93d3b-5cf9-47d3-ab43-9e688c2f5cad" />


**9. Insights & Conclusions (SMART Analysis)**

KPI Insights
Total Funding (USD)

The dashboard indicates a cumulative startup funding of USD 28.75 Billion, reflecting significant investment activity within the Indian startup ecosystem.

Startup Funding Trend

Funding levels fluctuate across the observed years, with notable peaks indicating periods of increased investor confidence and market expansion.

City-wise Funding

Startup funding is highly concentrated in major metropolitan cities, highlighting established startup ecosystems and stronger investor presence.

Top Funded Startups

A limited number of startups account for a substantial share of the total funding, demonstrating investor preference for high-growth organizations.

Business Category Analysis

Technology-driven sectors such as E-Commerce, FinTech, and AI & SaaS attract a significant proportion of total investments, indicating evolving market demand and innovation-driven growth.

Investor Analysis

A relatively small group of investors contributes a major portion of startup funding, reflecting concentrated investment activity within the ecosystem.

**Descriptive Analysis**

Total startup funding exceeded USD 28 Billion.
Funding is concentrated among selected startups and industries.
Investment activity is primarily centered in major Indian cities.

**Diagnostic Analysis**

Mature startup ecosystems attract greater investor participation.
Technology-focused industries receive comparatively higher funding.
Geographic concentration reflects stronger infrastructure and business ecosystems.

**Predictive Analysis**

Emerging technology sectors are expected to continue attracting increased investments.
Startup hubs are likely to remain the preferred investment destinations.
Growing investor participation may further diversify funding across industries.

**Prescriptive Analysis**

Investors should diversify investments into emerging startup sectors with high growth potential.
Policymakers should encourage startup development beyond metropolitan cities.
Entrepreneurs should leverage investment trends to align business strategies with market demand.
Continuous monitoring of funding trends can support informed investment decisions.

**10. Key Findings (with Metrics)**

| **Metric** | **Key Finding** |
|------------|-----------------|
| **Total Funding (USD)** | USD **28.75 Billion** was invested in Indian startups. |
| **Total Startups** | Approximately **2K startups** received funding. |
| **Total Investors** | Around **2K investors** participated in funding rounds. |
| **Total Cities** | The dataset covers **58 Indian cities**. |
| **Average Funding per Startup** | Average funding per startup is **USD 17.59 Million**. |
| **Highest Funding Year** | **2017** recorded the highest startup funding. |
| **Top Funded Startup** | **Flipkart** secured the highest funding (USD **4.0 Billion**). |
| **Leading Industry** | **E-Commerce** received the highest industry funding (USD **7.0 Billion**). |
| **Top Business Category** | **Others** accounted for the largest share of funding (USD **13.86 Billion**). |
| **Leading Investor** | **WestBridge Capital** emerged as the leading investor. |
| **Geographical Insight** | Startup funding is primarily concentrated in major metropolitan cities, particularly **Bengaluru**. |


**11. Conclusion**

The Indian Startup Funding Analysis Dashboard demonstrates how Power BI can transform raw startup investment data into actionable business intelligence. Through comprehensive data preparation, DAX-based business metrics, interactive visualizations, and analytical storytelling, the dashboard provides valuable insights into funding trends, investor behavior, business categories, and geographical investment patterns.

The dashboard combines interactive visualizations, KPI cards, slicers, and dynamic filtering to provide stakeholders with a comprehensive view of the Indian startup ecosystem. By enabling users to analyze funding trends, investor participation, business categories, and city-wise investments interactively, the solution supports informed decision-making and effective business intelligence reporting.

