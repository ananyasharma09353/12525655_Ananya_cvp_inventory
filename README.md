# Cadbury Dairy Milk - CVP & Inventory System
## Student Details: Lovely Professional University B.Com Hons
### Pricing Inputs: Price = Rs. 100, VC = Rs. 80, FC = Rs. 1,20,000
### Core Metrics: BEP = 6,000 units, MOS = 45.45%, DOL = 2.20x
### Sensitivity Range: +/-5%, +/-10%, +/-20% cost shifts
## Live System Dashboards
* 📊 [Task 1 - CVP Dashboard](https://ananyasharma09353.github.io/12525655_Ananya_cvp_inventory/cvp-dashboard/)
* 📦 [Task 2 - Inventory Management System](https://ananyasharma09353.github.io/12525655_Ananya_cvp_inventory/inventory-system/)
## Task 2: Inventory Management System Overview
Implemented a multi-SKU inventory decision-support system for the Cadbury Dairy Milk product line.
### Reorder Point (ROP) & Safety Stock
* Formula: ROP = (Daily Demand x Lead Time) + Safety Stock
* Safety Stock (SS) = Z x Standard Deviation x sqrt(Lead Time)
* Dynamic service level adjustment (90% to 99% Z-scores).
### Economic Order Quantity (EOQ)
* Formula: EOQ = sqrt((2 x Demand x Ordering Cost) / Holding Cost)
* Minimizes combined holding and ordering costs per SKU with dynamic trade-off charts.
### Inventory Valuation Methods
Provides comparative closing stock valuation and COGS reports under:
1. First-In, First-Out (FIFO)
2. Last-In, First-Out (LIFO)
3. Weighted Average Cost (WAC)
### ABC Pareto Classification
* Category A: Top 70% of total annual consumption value
* Category B: Next 20% of annual value
* Category C: Remaining 10% of annual value
### Stock Movement & CRUD Operations
* Transaction logger supports Stock-In (Purchases) and Stock-Out (Sales Issues).
* Maintains running balances and triggers real-time low-stock alerts when stock <= ROP.
### Live Task 2 Application Link
* **Interactive Inventory Dashboard:## Live Project Dashboards

* 📊 **Task 1 — CVP Dashboard:** https://ananyasharma09353.github.io/12525655_Ananya_cvp_inventory/cvp-dashboard/
* 📦 **Task 2 — Inventory Management System:** https://ananyasharma09353.github.io/12525655_Ananya_cvp_inventory/inventory-system/
