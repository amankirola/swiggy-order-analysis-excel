# swiggy-order-analysis-excel
# Excel Project

A small data analysis project built entirely in **Microsoft Excel** in which I analyzed food ordering patterns, spending behaviour, and delivery trends.

---

## 📌 Objective

Analyze Swiggy order data to answer questions like:
- Which restaurants and areas get the most orders?
- What is the monthly spending trend?
- How often are coupons used?
- What's the Veg vs Non-Veg split?
- How frequently are deliveries on time vs delayed?

---

## Workbook Structure

| Sheet | Description |
|---|---|
| `Swiggy_Orders_Data` | Raw order data with data prep steps (date extraction, area correction, restaurant name cleaning) |
| `Restaurant Area Correction` | Lookup table to standardize area names |
| `Food Item Level Data` | Item-wise breakdown with Veg/Non-Veg classification |
| `Restaurant Level Analysis` | Order count & ranking per restaurant |
| `Area Level Analysis` | Orders by area using Pivot Tables |
| `Food Items Analysis` | Most ordered food items |
| `Monthly Expenditure` | Month-wise order count and spending |
| `KPIs` | Key metrics using PivotTable |
| `Dashboard` | Summary view with all key KPIs and visuals |

---

## Concepts Used

- `DATEVALUE()` — extracting clean dates from datetime strings
- `VLOOKUP()` / `XLOOKUP()` — area name standardization and lookups
- `COUNTIFS()` — conditional order counting
- `RANK.EQ()` — ranking restaurants by order count
- `IF()` — Veg/Non-Veg classification
- `IFERROR()` + `LEFT()` + `FIND()` — cleaning restaurant names
- **Pivot Tables** — area-wise and month-wise summaries
- **Charts** — visualizing order distribution and spending patterns

---

## How to Open

1. Download the `.xlsx` file
2. Open in **Microsoft Excel** (recommended) or Google Sheets
3. Start from the `Dashboard` sheet for the summary view

---

## Skills Practiced

- Data cleaning and preparation in Excel
- Building a structured analysis workflow from raw data to dashboard
- Using lookup functions, pivot tables, and charts together
