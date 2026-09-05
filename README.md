# Mobile_sales_analysis
# 📱 Mobile Sales Dashboard – Power BI

An interactive Power BI dashboard built to analyze mobile phone sales data — covering total sales, transactions, quantity sold, average pricing, ratings, payment methods, and regional/time-based trends.

## 📊 Dashboard Overview

The report contains **3 pages**:

### 1. Sales Dashboard (Main Page)
- **KPIs:** Total Sales, Transactions, Total Quantity, Average Price
- **Total Sales by City** – Geo map showing sales distribution across Indian cities
- **Total Sales by Month** – Line chart trend across the year
- **Ratings by Rating Status** – Good / Average / Poor breakdown
- **Transactions by Payment Method** – Pie chart (UPI, Debit Card, Credit Card, Cash)
- **Total Sales by Mobile Model** – Bar chart (iPhone SE, OnePlus Nord, Galaxy Note 20, etc.)
- **Total Sales by Day Name** – Weekly sales pattern
- **Brand-wise Summary Table** – Total Sales & Transactions by Brand (Apple, Samsung, OnePlus, Vivo, Xiaomi)

### 2. MTD Report
- Month-To-Date KPIs: Total Sales, Transactions, Total Quantity, Average Price
- **MTD Trend** – Day-wise cumulative sales chart by Year, Quarter, Month & Day

### 3. Same Period Last Year
- Year-over-year comparison table (Quarter-wise Total Sales vs Same Period Last Year)
- Yearly comparison bar chart
- Quarter-wise comparison chart
- Month-wise comparison chart

## 🎛️ Filters / Slicers
- Mobile Model
- Payment Method
- Brand
- Year, Quarter, Month, Day
- Month buttons (January – December) for quick navigation

## 🛠️ Tools & Tech Used
- **Power BI Desktop** – Report building & DAX calculations
- **Power Query** – Data cleaning & transformation
- **DAX** – Measures for MTD, Same Period Last Year, Average Price, etc.
- **Bing Maps** – City-level geo visualization

## 📁 Repository Contents
| File | Description |
|------|--------------|
| `power bi.pbix` | Power BI report file |
| `Screenshots/` | Dashboard preview images |
| `README.md` | Project documentation |


## 🚀 How to Use
1. Clone this repository
   ```bash
   git clone https://github.com//Anjalisatdeve/Mobile_sales_analysis.git
   ```
2. Open `power bi.pbix` in **Power BI Desktop**
3. Refresh the data source (if connected to your own dataset)
4. Explore the dashboard using the slicers and filters

## 📈 Key Insights
- UPI is the most preferred payment method (~26% of transactions)
- Apple leads in total sales among all brands
- Sales show a seasonal dip around August–September and a rise towards year-end



