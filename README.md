# AtliQ Hardwares — Sales & Finance Analysis

## About AtliQ
AtliQ Hardwares is a consumer electronics hardware company that sells products such as desktops, laptops, gaming accessories, and peripherals across multiple global markets. It operates through several divisions — including PC, Peripherals & Accessories (P&A), and Networking & Storage (N&S) — and sells through a wide network of retail and e-commerce customers such as Amazon, Flipkart, BestBuy, and Costco, across 20+ countries.

This project analyzes AtliQ's sales and financial performance from 2019 to 2021, using Excel to build a set of interactive reports covering products, customers, markets, and profitability.

## Overview
This project is an end-to-end sales and finance analysis of **AtliQ Hardwares**, built in Excel using Power Query, Power Pivot, and DAX. It transforms raw transactional data into a set of interactive, filterable reports covering product performance, customer performance, market performance against targets, and full profit & loss (P&L) statements across fiscal years, quarters, and markets.

The goal was to simulate a real-world business intelligence workflow: taking raw sales data, building a clean data model, and producing decision-ready reports for sales, finance, and leadership teams.

## Business Problem
AtliQ Hardwares needed a way to answer key business questions:
- Which products and customers are driving growth, and which are underperforming?
- How is each market performing against its sales target?
- What does profitability (Gross Margin %) look like across markets, quarters, and years?
- Where should the business focus expansion or corrective action?

## Project Objectives

### Sales Analysis
- Track **new product performance** (2021 launches) and identify the **top 10 products** and **top & bottom 5 products** by quantity sold.
- Build a **Customer Performance Report** showing net sales by customer from 2019–2021, with year-over-year growth.
- Compare **market performance against sales targets** across 20+ countries to flag underperforming regions.

### Finance Analysis
- Build **P&L statements by Fiscal Year** and by **Quarter/Month**, tracking Net Sales, COGS, Gross Margin, and GM%.
- Build a **P&L statement by Market**, breaking down profitability by country.
- Analyze **Gross Margin % by quarter and subzone** (ANZ, India, NA, NE, ROA, SE) to spot regional margin trends.

## Key Insights
- **Revenue growth:** Net Sales grew from **$87.5M in 2019** to **$598.9M in 2021**, a **204.5%** increase from 2020 to 2021.
- **Margin pressure:** Despite strong revenue growth, overall GM% declined from **41.4% (2019)** to **36.4% (2021)**, indicating rising costs outpaced sales growth.
- **Market concentration:** India is the largest market ($161.3M in 2021 net sales), followed by USA ($87.8M) and South Korea ($49.0M) — together over 60% of total 2021 revenue.
- **Target shortfall:** Nearly every market missed its 2021 sales target, with an overall gap of **-$54.9M (-8.4%)**; Poland (-15.3%) and the USA (-10.4%) had the largest relative misses.
- **Division performance:** P&A was the strongest-growing division (+221.5% YoY), while N&S grew the slowest (+84.4% YoY).
- **New product traction:** New 2021 products generated **$176.2M**, led by AQ Qwerty ($22.0M) and AQ Trigger ($20.7M).
- **Regional margins:** ROA and SE consistently posted the highest GM% (~38–44%) across all three years, while NA and India saw the sharpest margin compression, especially India dropping from 42.4% (2019) to 32.0% (2021).

## Tools & Techniques
- **Microsoft Excel** — Power Query, Power Pivot, PivotTables, conditional formatting (heatmaps)
- **ETL (Extract, Transform, Load)** — cleaning and shaping raw sales/finance data
- **Data modeling** — building relationships between fact and dimension tables, including a custom date table with fiscal months/quarters
- **DAX** — calculated columns and measures for metrics like GM%, YoY comparisons, and fiscal-year logic

## Skills Demonstrated
**Technical**
- ETL methodology and Power Query transformations
- Fiscal date table creation with derived months/quarters
- Data model relationships via Power Pivot
- DAX for calculated columns and dynamic measures
- Building filterable, multi-dimensional reports (by region, market, division, customer)

**Analytical / Business**
- Translating raw data into business-relevant KPIs
- Designing user-centric, decision-ready reports
- Identifying growth drivers, risk areas, and margin trends
- Structuring a repeatable report-building workflow

## Repository Contents
| File | Description |
|---|---|
| `AtliQ_Sales_Finance_Analysis.xlsx` | Full Excel workbook with data model, Power Query transformations, and all reports |
| `Product Performance Report.pdf` | New products (2021), top 10 products, top & bottom 5 products by quantity |
| `Customer Performance Report.pdf` | Net sales by customer, 2019–2021, with YoY growth |
| `Market Performance vs Target.pdf` | Country-level net sales vs. 2021 targets |
| `P&L Statement by Fiscal Year.pdf` | Net Sales, COGS, Gross Margin, GM% by year (2019–2021) |
| `P&L Statement by Markets.pdf` | P&L breakdown by country/market for FY2021 |
| `P&L Statement by Months.pdf` | Monthly/quarterly P&L breakdown by fiscal year |
| `GM% by Quarters Subzone.pdf` | Gross margin % by quarter and subzone (2019–2021) |

## How to Use
1. Download `AtliQ_Sales_Finance_Analysis.xlsx`.
2. Open in Excel (Power Query/Power Pivot enabled).
3. Use the filter panels (region, market, division, customer, FY) on each report tab to explore the data interactively.
4. Refer to the individual PDF reports for a static, presentation-ready view of each analysis.

## Author
Margi Thakar — feel free to connect on www.linkedin.com/in/margi-thakar-433290356 or check out more projects on https://github.com/margi345/.
