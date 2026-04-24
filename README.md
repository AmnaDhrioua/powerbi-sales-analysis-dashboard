# powerbi-sales-analysis-dashboard

End-to-end Sales Analysis Dashboard built with Power BI including data cleaning, modeling, DAX measures, and interactive reporting.

---

## Project Overview

This project presents a complete Sales Analysis solution developed using Power BI.  
It follows the full Business Intelligence workflow, starting from raw data preparation to interactive dashboard development.

The objective is to analyze sales performance, uncover key business insights, and provide a dynamic decision-support tool.

---

## Business Objectives

- Monitor overall sales performance  
- Analyze profitability and revenue trends  
- Identify top-performing regions and product categories  
- Track KPIs and performance indicators  
- Support data-driven decision-making  

---

## Tools & Technologies

- Power BI Desktop  
- Power Query (Data Transformation)  
- DAX (Data Analysis Expressions)  
- Star Schema Data Modeling  

---

## Project Workflow

### 1. Data Preparation (Power Query)

- Imported raw sales dataset  
- Cleaned missing and inconsistent values  
- Removed duplicates  
- Standardized data formats  
- Normalized tables  
- Prepared data for modeling  

### 2. Data Modeling

- Created relationships between tables  
- Built a Star Schema model  
- Defined primary and foreign keys  
- Optimized model structure  

### 3. DAX Measures

Key measures created:

- Total Sales  
- Total Profit  
- Revenue Growth  
- Profit Margin  
- Sales by Category  
- Sales by Region  
- KPI performance indicators  

Example DAX measure:

```DAX
Total Sales = SUM(Sales[SalesAmount])
```

```DAX
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

---

### 4. Dashboard Design

- Added visualizations (bar charts, line charts, KPI cards, tables)  
- Implemented slicers and filters  
- Created a second report page  
- Built a custom navigation menu  
- Designed interactive tooltips  

---

## Dashboard Features

- Interactive filtering  
- Sales trend analysis  
- Regional performance analysis  
- Category performance tracking  
- KPI summary cards  
- Drill-down capability  
- Multi-page navigation  

---

## Repository Structure

```
powerbi-sales-analysis-dashboard/
│
├── dataset/
│   └── sales_data.csv
│
├── dashboard/
│   └── Sales_Analysis.pbix
│
├── screenshots/
│   ├── overview_page.png
│   └── details_page.png
│
└── README.md
```

---

## Key Insights Generated

- Identified top-performing regions  
- Analyzed seasonal sales trends  
- Measured profitability by product category  
- Evaluated revenue growth over time  

---

## Business Value

This dashboard enables stakeholders to:

- Monitor sales performance in real time  
- Detect underperforming segments  
- Improve strategic planning  
- Make data-driven decisions  

---

## Future Improvements

- Add time-intelligence forecasting  
- Integrate real-time data sources  
- Publish to Power BI Service  
- Implement Row-Level Security (RLS)  

---

## Author

Amna Dhrioua  
Aspiring Data Scientist | BI Enthusiast  
Tunisia
