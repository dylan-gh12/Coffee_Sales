**# Coffee Sales Dashboard (Excel Web Version)

This project is an interactive Excel-based sales dashboard created using the free web version of Excel and showcases a fictional coffee company's sales data. The dashboard visualizes trends, highlights key customers, and breaks down sales by country using Pivot Tables and Excel charts.

## Overview

The project includes:

- A line chart showing total sales volume by coffee type
- Two bar charts:
  - Top 5 customers by sales
  - Sales by country
- 3 interactive slicers to filter all visuals by selected criteria
- A timeline filter connected to the line chart for analyzing trends over time

> Note: Due to limitations in the free Excel Web version, the timeline can only be linked to the line chart, not to bar charts.

---

## Data Sources

The original workbook consists of three sheets:
- `Orders` – The main sales data, cleaned and enriched using Excel formulas
- `Customers` – Customer information (used for joining via XLOOKUP)
- `Products` – Product details including coffee types and categories

Using `XLOOKUP` and `INDEX/MATCH`, the `Orders` sheet was enhanced to include all necessary customer and product details to enable comprehensive Pivot Table analysis.

---

## How to Use

1. Open the Excel file in Excel (desktop or web).
2. Use the **slicers** to filter the visuals by criteria like customer, product, or region.
3. Adjust the **timeline** to explore how coffee sales changed over time.
4. View insights at a glance using the interactive visuals.

---

## Notes

- Designed for simplicity and usability, even in the limitations of Excel Web.
- Timeline filter is only linked to the line chart due to Excel Web constraints.
