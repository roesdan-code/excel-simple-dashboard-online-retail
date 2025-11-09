# Retail Analytics — Excel Dashboard (UCI Online Retail)

**Excel-first portfolio**: a clean, interactive **Excel (Power Pivot)** dashboard and a client-facing **QA/report** workbook, built on the public **UCI “Online Retail.xlsx”** dataset.

## What’s inside
- **Executive KPIs**: Net Sales, Orders, Customers (identified), Repeat %, Return %, Free %, Non-Merch %, % Sales from Guest/Unknown
- **Products**: Top SKUs, price–volume scatter, return-heavy items
- **Customers**: Pareto (80/20), repeat funnel, AOV, orders/customer
- **Returns & Data Quality**: return rate by country/SKU + QA cards

> Built primarily in **Excel (Power Pivot)** with a small **Python** step for clean inputs and QA. This repo showcases the **Excel deliverables**.

## Files
- `dashboards/OnlineRetail_Dashboard_v1.xlsx` – 4-sheet Excel dashboard (interactive slicers/Timeline)
- `reports/OnlineRetail_Cleaning_Report_v1.xlsx` – multi-sheet QA/report (Executive summary, QA tables, Dictionary); including worksheet sample 25k for reference
- `docs/OnlineRetail_OnePager_Credited.(docx|html)` – one-page case study

## How to use
1. **Open the Excel files** directly (Excel 365 recommended).  
2. Use the slicers to filter by **Year/Month**, **Country**, and toggles for **Non-Merch** / **Wholesale**.  

## Data source & credits
**Dataset:** *Online Retail* (UK non-store retailer transactions, 2010-12-01 to 2011-12-09), UCI Machine Learning Repository.  
**Contributor:** Dr. Daqing Chen, School of Engineering, Middlesex University (London).  
**Accessed:** Oct 2025. Use: Public dataset for research/education; no affiliation implied.  
**Suggested citation:** Dua, D. & Graff, C. (2019). *UCI Machine Learning Repository*. University of California, Irvine. Dataset: *Online Retail*. Accessed Oct 2025.

## Notes
- The **Excel dashboard** and **QA workbook** are designed for stakeholders who prefer Excel.  
- A **Power BI** version with the same KPIs and pages is available on request.
- The **full raw data** is not re-hosted here; only a small sample is included.

## Contact
Roesdan Pradana — Excel dashboards, retail analytics, QA-ready data.  
Email: roesdan@gmail.com
