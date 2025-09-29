# Marketing Campaign Performance (PowerBIProject)
This project demonstrates the design and implementation of a *clean, professional Power BI dashboard* for monitoring marketing campaign performance across multiple channels, products, and time periods.  
The goal is to empower *data-driven optimization decisions* with interactive visuals and dynamic filtering.



## Objective
To build a *Marketing Campaign Performance Dashboard* that:
- Monitors key campaign metrics in real-time.
- Enables *dynamic filtering* by channel, product, category, and date.
- Supports *data-driven decision making* to improve ROI.



##  Data Preparation



### Load Data
Import the campaign dataset from your preferred source:
- *Supported Formats*: Excel, SQL Server, CSV, etc.


Ensure the dataset contains the following *key columns*:
| Column | Description |
|-------|-------------|
| Campaign ID | Unique identifier for each campaign |
| Campaign Date | Date of campaign execution |
| Marketing Channel | Channel used (Email, Social, etc.) |
| Product Name | Name of the promoted product |
| Category | Product category |
| Ad Spend (INR) | Total advertising spend |
| Impressions | Number of ad impressions |
| Clicks | Total clicks received |
| Conversions | Number of successful conversions |
| Revenue (INR) | Total revenue generated |
| ROI | Return on investment |




### Clean & Transform
Prepare the dataset for analysis by:
- *Removing duplicates*.
- Standardizing *date formats* (e.g., dd-mm-yyyy).
- Ensuring all *numeric columns* (Spend, Impressions, Clicks, etc.) are correctly typed.
- Replacing *nulls or zeros* where appropriate.




### Create Calculated Columns
Add custom columns for better insights:
- *Campaign Period* (start/end dates)
- *Click-Through Rate (CTR%)* = (Clicks / Impressions) × 100
- *Day of the Week* (from Campaign Date)
- *Conversion Rate (%)* = (Conversions / Clicks) × 100
- *Cost per Acquisition (CPA)* = (Ad Spend / Conversions)




### Create DAX Measures
Define key measures to drive KPIs:
- *Total Ad Spend*
- *Total Impressions*
- *Total Clicks*
- *Total Conversions*
- *Total Revenue*
- *Overall ROI*




## Dashboard Design




### Key Performance Indicators (KPIs)
Use *Card visuals* to display:
- Total Ad Spend
- Total Impressions
- Total Clicks
- Total Conversions
- Total Revenue
- Overall ROI (formatted as % with 2 decimals)

![Alt Text] (<img width="731" height="387" alt="KPI Report" src="https://github.com/user-attachments/assets/aee003e7-0751-46b5-a62d-d7eff1b2eb57" />)





### Visuals

| Visual | Chart Type | Purpose |
|------|-----------|--------|
| *Ad Spend by Channel* | Clustered Column | Compare spend across marketing channels |
| *Clicks vs Impressions* | Line + Column Combo | Track relationship between impressions & clicks |
| *Conversion Rate by Category* | Bar Chart | Evaluate conversion rates by product category |
| *Revenue by Product* | Column Chart | Identify top-performing products by revenue |
| *ROI by Product/Category* | Bar Chart | Compare ROI across products or categories |
| *Time-Based Trends* | Line Charts | View spend, conversions, ROI, and clicks over time |

![Alt Text] (<img width="731" height="394" alt="Visuals Report" src="https://github.com/user-attachments/assets/e1685c20-87a7-43e4-88a8-49173a7f0b58" />)




### Interactivity
Enhance user experience with *Slicers*:
- *Campaign Date* (date range selector)
- *Product Name*
- *Product Category*
- *Marketing Channel*

Ensure *cross-filtering* is enabled so clicking on any chart dynamically updates all visuals.

![Alt Text]  (<img width="741" height="391" alt="Time Based Trend " src="https://github.com/user-attachments/assets/d71510ae-2b2b-498a-90fb-e2c9e4609d8a" />)





## Final Dashboard
The final Power BI dashboard provides:
- A *clean, professional layout*.
- *Dynamic filtering* across campaigns, dates, products, and marketing channels.
- Instant insights into *spend, revenue, ROI, and conversion efficiency*.



![Alt Text] (<img width="735" height="377" alt="My Dashboard" src="https://github.com/user-attachments/assets/50c3f5ef-986b-4842-af07-83f278b46ebb" />)





## Tools & Technologies
- *Power BI Desktop & Service*
- Data Sources: Excel / SQL Server / CSV
- *DAX* for calculated measures and KPIs
- Data Cleaning in *Power Query*



