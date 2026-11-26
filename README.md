# retail-sales-margin-dashboard
Interactive Tableau Public dashboard analyzing 51K+ retail orders ($12.64M sales) with a What-If discount simulator to prevent margin leakage.
# Retail Sales & Margin Optimization Dashboard

**[View Live Interactive Dashboard on Tableau Public]([Paste Your Tableau Public URL])**

## 1. Business Problem
While total retail revenue reached **$12.64M** across 51,290+ orders, overall net profit was compressed to **$1.47M (11.61% margin)** due to aggressive discounting and loss-making product lines. Leadership needed an interactive tool to pinpoint margin leakage and simulate pricing guardrails.

## 2. Tools & BA Skills Applied
* **BI & Analytics:** Tableau Public (What-If Parameters, Calculated Fields, Dual-Axis Trends, Interactive Slicers, Geographic Mapping)
* **Business Analysis:** Requirement Definition, KPI Design, Root Cause Analysis (RCA), Margin Simulation

## 3. Key Findings
* **20% Discount Tipping Point:** Orders with **0–20% discounts** generated **+$2.28M** in profit, whereas discounts **above 20%** caused **-$815K in net losses** (-$21K at 20–30% and -$794K at 30%+).
* **Product-Level Margin Leakage:** Technology sub-categories (**Copiers +$258K**, **Phones**) drove top margins, whereas high-volume **Tables (-$64K)** operated at a net loss.
* **Q4 Seasonality:** Sales spiked sharply every November–December, magnifying margin erosion wherever uncontrolled discounts were applied.

## 4. Business Recommendations
* **Enforce a 20% Discount Cap:** Require manager approval for discounts above 20% (What-If simulation shows capping discounts at 20% protects **$2.07M+** in net profit).
* **Reprice & Audit Tables:** Remove blanket promotional discounts on Tables and renegotiate shipping/supplier costs to restore positive unit economics.

![Dashboard Preview](dashboard_preview.png)

URL : https://public.tableau.com/app/profile/ramachandran.s8836/viz/RetailSalesMarginOptimizationDashboard/Dashboard1
