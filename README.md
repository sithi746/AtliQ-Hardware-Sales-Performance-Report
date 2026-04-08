# AtliQ Hardware Sales Analysis 

---

## 
**AtliQ Hardware Sales Dashboard** – Monitor sales performance across markets, customers, products, and divisions to uncover growth opportunities and performance gaps.  

---

##  Purpose
This dashboard transforms raw sales and target data into a **structured, actionable analytics tool**, enabling stakeholders to:  
- Track overall revenue performance  
- Compare actuals vs targets  
- Identify top-performing products and customers  
- Make data-driven strategic decisions  

---

## Tech Stack
- **Data Modeling & Transformation:** Excel Power Query, Power Pivot  
- **Analytics & Reporting:** DAX, Power BI / Excel  
- **Data Storage:** Fact & Dimension tables (Snowflake schema)  


---

## Data Source
| Table | Description |
|-------|------------|
| `fact_sales_monthly` | Transactional sales data |
| `ns_targets_2021` | Market-level sales targets |
| `dim_customer` | Customer info (platform, channel) |
| `dim_product` | Product hierarchy (division, segment, category) |
| `dim_market` | Market, sub-zone, region hierarchy |
| `dim_date` | Date, month, fiscal year |

---

##  Data Model
The dashboard uses a **Snowflake-schema** for multi-dimensional analysis:  

![Data Model](https://github.com/sithi746/AtliQ-Hardware-Sales-Performance-Report/blob/main/README.md)  
*Fact tables link to normalized dimensions for efficient querying and comparisons.*  

---

##  Features / Highlights

### Business Problem
- Disconnected data across multiple sources  
- Difficulty tracking sales, targets, and growth gaps  

### Goal of the Report
- Consolidate data for actionable insights  
- Track performance vs targets across markets, customers, and products  

### Report Walkthrough
- **Revenue KPI:** Total net sales & YoY growth  
- **Market & Customer Analysis:** Top-performing regions & clients  
- **Product & Division Insights:** Top/bottom products & division report
- **Target vs Actual:** performance gaps  

 

### Business Impact & Insights
- **Revenue:** $598.9M (+204.5% YoY)  
- **Top Markets:** India $161.3M, USA $87.8M  
- **Top Customers:** Amazon $82.1M, AtliQ e-Store $53M  
- **High-Growth Divisions:** PC +313.7%, P&A +221.5%  
- **Top Products:** AQ Electron 4 3600, AQ Smash 2  
- Recommendations: improve forecasting, scale high-performing products, rationalize underperformers, invest strategically in top divisions  

