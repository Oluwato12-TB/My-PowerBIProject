# Marketing Campaign Performance (PowerBIProject)
This project demonstrates the design and implementation of a *clean, professional Power BI dashboard* for monitoring marketing campaign performance across multiple channels, products, and time periods.  
The goal is to empower *data-driven optimization decisions* with interactive visuals and dynamic filtering.

## Objective
To build a *Marketing Campaign Performance Dashboard* that:
- Monitors key campaign metrics in real-time.
- Enables *dynamic filtering* by channel, product, category, and date.
- Supports *data-driven decision making* to improve ROI.

## 📂 Data Preparation

### ⿡ Load Data
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


### ⿢ Clean & Transform
Prepare the dataset for analysis by:
- *Removing duplicates*.
- Standardizing *date formats* (e.g., dd-mm-yyyy).
- Ensuring all *numeric columns* (Spend, Impressions, Clicks, etc.) are correctly typed.
- Replacing *nulls or zeros* where appropriate.


### ⿣ Create Calculated Columns
Add custom columns for better insights:
- *Campaign Period* (start/end dates)
- *Click-Through Rate (CTR%)* = (Clicks / Impressions) × 100
- *Day of the Week* (from Campaign Date)
- *Conversion Rate (%)* = (Conversions / Clicks) × 100
- *Cost per Acquisition (CPA)* = (Ad Spend / Conversions)


### ⿤ Create DAX Measures
Define key measures to drive KPIs:
- *Total Ad Spend*
- *Total Impressions*
- *Total Clicks*
- *Total Conversions*
- *Total Revenue*
- *Overall ROI*


## 📈 Dashboard Design


### 🔑 Key Performance Indicators (KPIs)
Use *Card visuals* to display:
- Total Ad Spend
- Total Impressions
- Total Clicks
- Total Conversions
- Total Revenue
- Overall ROI (formatted as % with 2 decimals)


