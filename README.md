# Supplier Risk Analysis Dashboard for Procurement Decision Support

## Objective
This project analyzes supplier-related risk and performance indicators to support procurement decision-making. The goal is to help identify risk patterns, compare supplier performance across categories, and provide a clearer basis for supplier monitoring and review.

In practical supply chain operations, supplier issues can affect delivery reliability, service continuity, and operational stability. This project uses data analysis and dashboard reporting to highlight supplier risk patterns that may matter for procurement teams.

##Context
Procurement decisions should not rely on one metric only. A supplier may appear acceptable on one dimension but still create risk if incidents are frequent, delivery performance is weak, or financial stability is low.

This project uses supplier data to examine:
- how supplier records are distributed across risk categories
- whether higher-risk suppliers show weaker performance indicators
- whether supplier quality differs by operational and financial dimensions
- how supplier evaluation changes over time

## Dashboard Purpose
The dashboard is designed to support a simple but practical procurement review process:
- understand the supplier base by risk category
- compare average performance across risk groups
- identify signals of weaker supplier performance
- support more structured supplier monitoring

## Key insights
### 1. Supplier Records by Risk Category
This chart shows how supplier records are distributed across different risk categories.

**What it helps reveal:**  
It provides an overview of how much of the supplier data falls into each risk group. This helps indicate whether the supplier base is concentrated in lower-risk or higher-risk categories.

If a large share of supplier records appears in higher-risk categories, procurement teams may need stronger monitoring or more frequent performance reviews.

This visual can help determine whether procurement should focus more attention on supplier screening, supplier development, or risk-based review priorities.

---

### 2. Average Incidents by Risk Category
This chart compares the average number of incidents across supplier risk groups.

**What it helps reveal:**  
It shows whether higher-risk suppliers tend to be associated with more operational incidents.

Incident frequency is important because repeated supplier issues can disrupt operations, create delays, or reduce service reliability.
If higher-risk suppliers consistently show more incidents, procurement teams may prioritize those suppliers for review, corrective action, or tighter monitoring.

---

### 3. Average Delivery Performance by Risk Category
This chart compares delivery performance between risk groups.

It helps show whether suppliers in riskier categories also perform worse in delivery-related execution. 
Delivery performance is critical in supply chain operations because weak delivery reliability can affect order fulfillment, inventory planning, and service continuity.
 
This visual can support decisions such as closer review of weak suppliers, stronger supplier performance tracking, or reconsideration of suppliers with weaker delivery capability.

---

### 4. Average Financial Stability by Risk Category
This chart compares financial stability across supplier risk groups.


It shows whether supplier risk is also reflected in weaker financial condition. 
A supplier with weak financial stability may create longer-term supply risk even if short-term operational performance appears acceptable. 
Procurement teams can use this visual to support more balanced supplier evaluation, where financial condition is considered alongside operational criteria.

---

### 5. Average MCDM Score by Year
This chart shows how the average MCDM score changes over time.
It provides a time-based view of supplier evaluation trends.  
A time trend helps show whether supplier assessment is improving, worsening, or remaining stable across years.
This can support periodic supplier review by showing whether the overall supplier base appears to be improving or whether further supplier improvement actions may be needed.

## Key Business Insights
- Higher-risk categories should not be interpreted only as labels; they should be examined together with delivery, incident, and financial indicators.
- Delivery performance and incident frequency are especially important because they directly affect operational reliability in the supply chain.
- Financial stability adds a longer-term risk perspective, which is useful when evaluating supplier resilience rather than short-term performance only.
- Viewing supplier data through multiple indicators gives procurement teams a more practical decision basis than using one metric in isolation.
- A dashboard structure makes supplier review easier by turning raw records into a more decision-oriented monitoring tool.

## Practical Relevance
This project is relevant to procurement and supply chain roles because it demonstrates how data can be used to:
- monitor supplier risk
- compare operational and financial performance
- identify weaker supplier segments
- support more structured supplier review and decision-making

## Files
- `supplier_risk_analysis.ipynb` – Python notebook for data cleaning, analysis, and visualization
- `supplier_risk.csv` – source dataset
- `supplier_risk_dashboard.pbix` – Power BI dashboard file
- `dashboard_overview.png` – dashboard preview image

## Dashboard Preview
![Dashboard Preview](dashboard_overview.png)

## Tools Used
- Python
- Pandas
- Matplotlib
- Power BI
