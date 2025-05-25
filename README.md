# Order IQ
### A smarter way to predict stock requirements

---

## Project Overview
**Order IQ** is a pilot initiative to evaluate how effectively machine learning models can forecast grocery order quantities based on historical sales data. The goal is to support smarter, data-driven stock decisions for the upcoming weeks.

---

## Scope of Work

### Data Analysis
- Analyze the provided dataset, which includes:
  - Store-level weekly sales data per SKU
  - Historical order quantities per SKU
  - Timestamps and SKU metadata
  - Inventory on hand
  - Ordering cadence

### Model Development
- Build a predictive model (e.g., **XGBoost**, **LightGBM**, or similar) to forecast:
  - **Next week's SKU-level order quantities**
  - **The following week's SKU-level order quantities**

### Output Format
- Deliver predictions in the following tabular format:

