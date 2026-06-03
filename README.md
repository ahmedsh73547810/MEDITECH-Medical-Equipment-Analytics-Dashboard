# 📊 Sales Performance Dashboard — Power BI

A multi-page interactive Power BI report providing end-to-end visibility into sales performance, target achievement, product trends, and cluster-level analysis. Built with a **Modern Executive Dark Sidebar** theme for a clean, professional look.

---

## 📸 Report Pages

| Page | Description |
|------|-------------|
| **Landing Page** | Branded entry point with navigation to all report sections |
| **Overview** | High-level KPIs, sales trends, and monthly/yearly performance tables |
| **Target Analysis** | Comparison of actual vs. target sales by rep and cluster |
| **Product Analysis** | Top & bottom products by sales, price trends over time |
| **Cluster Analysis** | Sales and target achievement broken down by cluster with trend lines |

---

## ✨ Features

- **KPI Cards** — Instant snapshot of key metrics across pages
- **Dynamic Slicers** — Filter by year, month, rep, cluster, and more
- **Page Navigator** — Seamless navigation bar on every page
- **Sales vs. Target Charts** — Clustered column charts comparing actuals against targets at rep and cluster level
- **Product Rankings** — Top 5 and Bottom 5 products by net sales
- **Price Trend Line Chart** — Track pricing changes over years
- **Treemap** — Visual breakdown of cluster sales and target achievement
- **Performance Tables** — Tabular sales data summarised by year and by month
- **Custom Theme** — Modern Executive Dark Sidebar applied throughout

---

## 🗂️ Report Structure

```
Final.pbix
├── Landing Page          # Navigation hub
├── Over View             # KPIs · Line chart · Column chart · Tables (by year & month)
├── Target Analysis       # Cards · Column charts (by rep & cluster) · Slicers
├── Product Analysis      # Bar charts (Top/Bottom 5) · Price trend · Slicer
└── Cluster Analysis      # Column chart · Line chart · Treemap · Slicers
```

---

## 🛠️ Built With

- **Power BI Desktop** (Report version 5.72, Theme: CY26SU04)
- **Custom Theme:** Modern Executive Dark Sidebar
- **Data Model:** Embedded dataset (Power BI Service linked)

---

## 🚀 Getting Started

1. **Clone or download** this repository.
2. Open `Final.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. If the report is connected to a live dataset, sign in with your Power BI account and refresh the data.
4. Use the slicers on each page to filter by time period, sales rep, or cluster.

> **Note:** The file uses a remote Power BI dataset (`DatasetId: 57ea6ee6-2282-4b3f-a677-e1941d02031b`). You may need to update the data source connection to point to your own dataset.

---

## 📐 Canvas Size

All pages are built on a **1280 × 720** canvas, optimised for widescreen display and full-screen presentation mode.

---

## 📁 File

| File | Description |
|------|-------------|
| `Final.pbix` | Power BI report file (includes layout, theme, and static resources) |

---

## 📬 Contact

For questions or contributions, feel free to open an issue or submit a pull request.
