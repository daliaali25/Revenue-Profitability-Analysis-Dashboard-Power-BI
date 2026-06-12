# Revenue & Profitability Financial Analysis — Power BI

> An executive-level financial intelligence dashboard monitoring $118.7M in revenue across time, geography, product lines, and market segments. Built for leadership teams that need one clean view of financial health — not a spreadsheet.

---

## Key Metrics

| KPI | Value |
|-----|-------|
| Total Revenue | $118.73M |
| Total COGS | $101.83M |
| Profit Margin | 14% avg |

---

## Dashboard Views

### Main Financial Performance View

![Revenue Analysis Main Dashboard](Images/revenue%20dashboard%20power%201.jpg)

The default view shows core financial trends with filters collapsed, optimizing screen space for the data itself.

| Visual | Purpose |
|--------|---------|
| Revenue, Profit & COGS by Quarter (multi-line chart) | Tracks the relationship between cost spikes, revenue growth, and margin across quarters — e.g., Q3-2013: $4.48M revenue vs. $3.72M COGS |
| Revenue, COGS & Profit by Country (100% stacked bar) | Instant comparison of net profit contribution across US, Canada, France, Germany, and Mexico |
| Revenue by Product & Segment | Performance across Paseo, VTT, Velo, and other lines, broken down by corporate, government, enterprise, midmarket, and small business |

---

### Interactive Slicer Panel

![Revenue Analysis Slicer Panel Open](Images/revenue%20dashboard%20power%202.jpg)

A collapsible filter panel built with Power BI Bookmarks and Selection Pane for clean, distraction-free exploration.

- **Slide-out filter pane:** Multi-select slicers for Year, Month, Country, Product, and Segment
- **Global reset button:** One click clears all active filters and returns the dashboard to its aggregate state

---

## Technical Implementation

**Data & Modeling**
- Platform: Power BI Desktop / Power BI Service
- DAX measures for all financial aggregations

**Core DAX measure:**
```DAX
Profit Margin % = DIVIDE([Total Profit], [Total Revenue])
```

**UI/UX**
- Dynamic object visibility for the collapsible slicer panel
- Shadow container cards, customized tooltips
- Corporate crimson accent palette with dark backgrounds for executive readability

---

## Insights this dashboard surfaces

- Which quarters show margin compression despite revenue growth
- Which countries contribute disproportionate profit relative to their revenue share
- Which product-segment combinations are most and least profitable
- How COGS tracks against revenue over time — and where the gap narrows, and a cohesive corporate color palette to maximize user adoption and avoid visual clutter.
