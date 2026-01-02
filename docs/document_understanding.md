# Data Understanding & Modeling Decisions

## Dataset Overview
The Global Superstore dataset represents transactional sales data across multiple markets, regions, and product categories. Each row represents a line item in an order.

---

## Key Measures Explained
- **Sales**: Revenue generated from product sales
- **Quantity**: Number of units sold
- **Profit**: Net profit after cost
- Sales and Quantity are intentionally treated separately, as:
  - High revenue does not always imply high unit movement
  - Quantity helps identify volume-driven vs price-driven products

---

## Data Cleaning Decisions
The following columns were removed after evaluation:
- **Row ID** – Surrogate row identifier, no analytical value
- **Duplicate or system-generated fields** – Not relevant for business analysis

The following were retained:
- **Customer ID** – Useful for future repeatability or customer concentration analysis
- **Product ID / Product Name** – Core grain of portfolio analysis
- **Date fields** – Required for temporal stability analysis

---

## Dimensional Modeling
A star schema approach is used:
- **Fact Table**: Global Superstore (Sales transactions)
- **Dimensions**:
  - Dim_Product
  - Dim_Date
  - Dim_Geography

Static aggregations (Total Sales, Total Profit, CVs) are computed at the **product level** to enable portfolio-wide comparisons.

