# Superstore Sales Dashboard - Power BI

**Tools**: Power BI, DAX, Power Query, Excel

### 🎯 Business Problem
Demonstrated ability to transform raw sales data into actionable business insights using interactive dashboards with KPI tracking.

### ✅ Solution
Built an interactive Power BI dashboard with drill-down capabilities, dynamic slicers, and custom DAX measures to analyze regional and time-based sales performance.

### 📊 Key Results
- **Total Revenue**: 2.65K analyzed across multiple regions
- **Total Profit**: 103.04 with 3.9% profit margin tracked
- **Top Insight**: South region drives highest sales volume
- **Technical Skills**: DAX measures, time-series analysis, KPI cards, slicers

### 🛠️ Technical Implementation
**DAX Measures:**
```dax
Profit Margin % = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Sales]), 0)
Total Revenue = SUM(Sales[Sales]) 
Total Profit = SUM(Sales[Profit])
