# Sales & Profit Performance Dashboard 📊

An interactive Tableau dashboard analyzing revenue, profit, and channel performance across Indian markets from 2016–2021.

## 🔍 Overview

This dashboard consolidates revenue and profitability data, enabling stakeholders to filter by **year** and **month** and instantly see how sales, profit margins, top customers, and sales channels perform over time.

**Snapshot:**
- **Total Revenue:** 986.57M
- **Total Profit:** 24.66M
- **Top Market:** Delhi NCR (520.72M revenue)
- **Top Channel:** Brick & Mortar (744.47M) vs E-Commerce (240.34M)
- **Top Customer:** Electricalsara Stores (413.9M sales, 9.3M profit)

## ✨ Features

- **Year & Month filters** (2016–2021, Jan–Dec) for dynamic time-based analysis
- **Revenue by Markets** — horizontal bar chart ranking markets by sales amount
- **Profit by Markets** — bar chart of profit margin % per market
- **Profit Trend** — combo chart showing monthly sales amount and profit margin trend
- **Customer Table** — detailed breakdown of sales amount, profit margin %, and profit by customer
- **Sales by Channel** — pie chart comparing E-Commerce vs Brick & Mortar revenue

## 🛠️ Tools Used

- **Tableau** — dashboard design & visualization
- **Excel / CSV** — source data preparation

## 📁 Repository Structure

```
├── README.md
├── dashboard.twbx          # Tableau packaged workbook (add your file here)
└── data/
    └── sales_data.csv      # source dataset (add your file here)
```

## 📈 Key Insights

- Delhi NCR leads revenue generation by a wide margin (520.72M), more than 3x the next closest market, Mumbai.
- Bhopal, Nagpur, and Bengaluru show relatively strong profit margins (3.90%, 2.57%, and above) despite lower revenue.
- Profit trend is volatile month-to-month, swinging between double-digit margin gains (12.06% in May) and losses (-5.92% in January).
- Brick & Mortar remains the dominant sales channel, generating roughly 3x the revenue of E-Commerce.
- Electricalsara Stores is by far the largest customer by both sales amount and profit contribution.
