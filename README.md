# Revenue & Profitability Financial Analysis (Power BI)

An executive-level Power BI dashboard engineered to monitor, analyze, and optimize corporate financial health. This intelligence solution provides a deep dive into revenue streams, profit margins, and Cost of Goods Sold (COGS) across various dimensions including time, geography, product lines, and market segments.

---

## 📊 Business Case & Key Financial Metrics

The dashboard is designed with a modern financial layout, using a clean corporate crimson accent color. It focuses on three primary High-Level KPIs to give executives an immediate health check of the business:

- Total Revenue: $118.73M (Gross Sales volume generated).
- Profit Margin %: Stable average of 14% across core operations.
- Total COGS: $101.83M (Total Cost of Goods Sold, tracking direct manufacturing or acquisition costs).

---

## 🖥️ Dashboard Architecture & Visual Features

The report utilizes an advanced UI/UX layout featuring an interactive collapsible Slicer Panel that optimizes screen real estate while offering deep, customized filtering capabilities.

### 1. Main Financial Performance View
This view displays core time-series trends and global performance distributions when filters are collapsed.

![Revenue Analysis Main Dashboard](images/revenue%20dashboard%20power%201.jpg)

- Revenue, Profit, and COGS by Year Quarter (Multi-Line Chart): A continuous time-series chart mapping the close relationship between cost spikes, revenue growth, and net profit margins across quarters (e.g., Q3-2013 tracking $4.48M Revenue vs. $3.72M COGS).
- Revenue, COGS, and Profit by Country (100% Stacked Bar Chart): Compares performance across international markets including the United States, Canada, France, Germany, and Mexico, instantly highlighting which regions yield the highest net profit component.
- Revenue, COGS, and Profit by Product & Segment: Evaluates product-level performance across key lines (Paseo, VTT, Velo, etc.) and breaks down target demographics across corporate, government, enterprise, midmarket, and small business sectors.

---

### 2. Advanced Interactive UI Elements (Slicer Panel Open)
By implementing customized Power BI Bookmarks and Selection Panes, users can seamlessly trigger a slide-out navigation menu for clean data exploration.

![Revenue Analysis Slicer Panel Open](images/revenue%20dashboard%20power%202.jpg)

- Collapsible Filter Pane: Clicking the filter icon triggers a smooth, slide-out navigation panel containing multi-select slicers for Year, Month Name, Country, Product, and Segment for granular cross-filtering.
- Global Reset Action: Includes a custom RESET button mapped with a bookmark action that instantly clears all selected parameters and returns the entire dashboard to its default aggregate state.

---

## 🛠️ Technical Implementation & Analytics Specs

- Technology Stack: Power BI Desktop / Power BI Service.
- Advanced DAX Formulas: Implemented explicit measures for financial aggregations and complex calculated ratios like dynamic profit margin percentages:
  $$\text{Profit Margin \%} = \frac{\text{Profit}}{\text{Revenue}}$$
- UI/UX Best Practices: Leveraged dynamic object visibility, shadow container cards, customized tooltips, and a cohesive corporate color palette to maximize user adoption and avoid visual clutter.