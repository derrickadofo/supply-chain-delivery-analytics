# supply-chain-delivery-analytics
Supply chain analytics project analyzing e-commercedelivery performance, logistics delays, and operational efficiency using Python, SQL, and BI dashboards.

## Project Overview
This project analyzes delivery performance in a large e-commerce logistics network using Python and business intelligence workflows. The objective is to identify delay drivers, evaluate logistics reliability, and understand how delivery performance affects customer satisfaction.

## Business Questions
- What is the overall on-time delivery performance of the network?
- Which states and sellers contribute most to delivery delays?
- Which product categories are most delay-prone?
- How do delivery delays affect customer review scores?

## Key Results
- On-Time Delivery Rate: 92.09%
- Late Delivery Rate: 7.91%
- Average Delivery Time: 12.01 days
- Average Delay Time for Late Orders: 8.74 days
- Average Review Score: 4.08 / 5

## Key Insights

**1) The network is broadly reliable but delays are severe when they occur.**  
Overall on-time delivery is **92.09%**, indicating strong baseline performance. However, **7.91% of orders arrive late**, and when they do, the **average delay is 8.74 days**, suggesting concentrated operational bottlenecks rather than minor scheduling slips.

**2) Delivery risk is geographically concentrated.**  
Several states show late-delivery rates well above the network average (7.91%), including **AL (24.1%)**, **MA (20.4%)**, **SE (16.3%)**, **PI (15.5%)**, and **CE (15.3%)**. This pattern indicates regional logistics constraints (e.g., carrier capacity, infrastructure, or routing inefficiencies) and suggests the need for **region-specific SLA planning**.

**3) A small group of sellers drives disproportionate delay risk.**  
Seller-level analysis shows late-delivery rates exceeding **30%** for some sellers, with corresponding lower customer review scores (≈3.0). This indicates that **targeted seller performance management**—monitoring, service-level agreements, or fulfillment improvements—could materially improve overall delivery reliability.

**4) Product category effects exist but are secondary drivers.**  
Some categories (e.g., **audio**, **fashion beachwear**, **Christmas items**) show late rates around **11–13%**, above the network average but significantly less extreme than the seller or geographic effects. Category handling may require refinement, but **seller and regional performance remain the primary drivers** of delay risk.

**5) Delivery reliability strongly influences customer satisfaction.**  
Orders with **1-star reviews average 19.1 delivery days** and **3.73 delay days**, while **5-star reviews average 10.2 delivery days** with **0.13 delay days**. This shows a clear relationship between logistics performance and customer experience, highlighting delivery reliability as a **key driver of customer satisfaction**.

## Operational Recommendations

- Introduce **region-specific delivery planning** to address high-risk states.
- Implement **seller performance monitoring** to identify and correct chronic delay sources.
- Review fulfillment workflows for delay-prone product categories.
- Track delivery reliability as a **customer experience KPI**, not only an operational metric.

## Interactive Dashboard
Explore the dashboard here: [https://public.tableau.com/views/SupplyChainDeliveryPerformanceDashboard/SupplyChainDeliveryPerformanceAnalysis?:language=fr-FR&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]

## Dashboard Preview
<img width="1998" height="1276" alt="Supply Chain Delivery Performance Analysis" src="https://github.com/user-attachments/assets/f5fb1be5-25b3-440d-a052-9a8c8196fb8b" />


## Tools Used
- Python (Pandas,NumPy, Matplotlib)
- Tableau Public

## Repository Structure
- `notebooks/01_data_ingestion_cleaning.ipynb` — data ingestion, cleaning, and feature engineering
- `notebooks/02_exploratory_kpi_analysis.ipynb` — KPI analysis and insight generation
- `data_processed/` — cleaned data outputs and Tableau export tables
- `docs/exec_summary.md` — project summary and recommendations


## Skills Demonstrated
- Data cleaning and feature engineering using Python
- Exploratory data analysis with Pandas and NumPy
- Logistics KPI modeling and operational analytics
- Business insight generation and recommendation design
- Data visualization and dashboard creation using Tableau

### License
For educational and portfolio purposes.
