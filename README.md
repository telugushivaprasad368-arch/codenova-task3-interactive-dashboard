# Interactive Sales Analytics Dashboard

### CodeNova Data Science Internship - Task 3

An interactive, no-build dashboard for exploring retail sales by date, region, category, and sales channel.

## Features

- Dynamic date-range filtering with minimum and maximum date inputs.
- Region, category, and channel dropdown filters.
- KPI cards for revenue, profit, margin, orders, units, and AOV.
- Interactive revenue-by-category bars, monthly revenue trend, and regional mix.
- Friendly empty-state feedback when no records match the filters.
- Responsive layout with no paid tools, API keys, or deployment dependencies.

## Run it

Open `dashboard.html` through a simple local web server so the CSV can be loaded:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000/dashboard.html` from this folder. It is also ready for GitHub Pages.

## Data

The dashboard uses the reproducible synthetic retail dataset from Task 1. The data is included as `data/synthetic_retail_sales.csv`; it is clearly synthetic because no source dataset was supplied with the assignment.

