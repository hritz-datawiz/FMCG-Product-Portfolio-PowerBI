# FMCG Product Portfolio Analysis – Power BI Case Study

## Project Context
This project focuses on analyzing a large FMCG-style product portfolio using Power BI.  
The objective is to evaluate products not only on absolute performance (Sales, Profit) but also on **consistency, stability, and sustainability over time**.

In real-world product portfolios, high sales or high profit alone is insufficient for long-term decision-making. Products must demonstrate **repeatable performance** with acceptable volatility to justify scaling investments.

---

## Business Objective
To classify products into strategic buckets such as:
- **Scale** – Products with stable and sustainable performance
- **Fix** – Products with demand but structural profitability or volatility issues
- **Monitor** – Products with potential but insufficient evidence
- **Exit** – Products destroying value or lacking acceptance

---

## Analytical Philosophy
This project intentionally follows a **statistics-first approach**:
- Understand data distributions before defining thresholds
- Use portfolio-level behavior to define what is “normal”
- Avoid arbitrary rules in favor of data-driven boundaries

---

## Tools & Techniques
- Power BI Desktop
- Power Query (data cleaning & shaping)
- DAX (measures, calculated columns)
- Dimensional Modeling (Star Schema)
- Statistical concepts:  
  - Coefficient of Variation (CV)  
  - Distribution analysis  
  - Sigma-based reasoning (planned)

---

## Dataset
Source: Global Superstore dataset (Kaggle)  
The dataset simulates a multi-market FMCG-like retail environment with:
- Orders
- Products
- Customers
- Sales, Profit, Quantity
