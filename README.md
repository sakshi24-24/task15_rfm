# 📊 Task 15 – Customer Segmentation (RFM Analysis)

## 🧾 Overview
This project performs **RFM (Recency, Frequency, Monetary) Analysis** on the Online Retail dataset to segment customers based on purchasing behavior and generate actionable business insights.

---

## 🛠 Tools Used
- Python (Google Colab)
- pandas, numpy
- matplotlib

---

## 🔎 Approach

### Data Preparation
- Removed missing CustomerID and canceled invoices  
- Filtered negative quantities  
- Converted InvoiceDate to datetime  
- Created `TotalAmount = Quantity × UnitPrice`

### RFM Calculation
- **Recency:** Days since last purchase  
- **Frequency:** Number of unique invoices  
- **Monetary:** Total spend per customer  

### Segmentation
- Applied quantile-based scoring (1–4 scale)
- Created customer segments:
  - Champions
  - Loyal Customers
  - At Risk
  - Regular Customers

---

## 📊 Key Insights
- Revenue is concentrated in high-RFM segments.
- “At Risk” customers represent reactivation opportunities.
- Some high-frequency customers show upsell potential.
- Low recency signals early churn behavior.

---

## 📁 Deliverables
- `task15_rfm.ipynb`
- `rfm_segments.csv`
- `segment_actions.txt`

---

## 🎯 Outcome
This project demonstrates practical customer segmentation, churn identification, and data-driven marketing strategy using real transactional data.
