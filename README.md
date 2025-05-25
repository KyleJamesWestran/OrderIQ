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

| SKU_ID   | Forecasted_Quantity_Next_Week | Forecasted_Quantity_Week_After |
|----------|-------------------------------|---------------------------------|
| 100234   | 48                            | 52                              |
| 100235   | 15                            | 18                              |
| 100236   | 102                           | 97                              |
| 100237   | 76                            | 80                              |
| 100238   | 33                            | 35                              |

### Final Deliverable
- A brief report covering:
  - Modeling approach and key assumptions
  - Features used in the model
  - Accuracy metrics (e.g., **MAPE**, **RMSE**)
  - Limitations and recommendations for improvement

---

## Goal
Help stores make **smarter stock decisions** using machine learning-powered demand forecasting.