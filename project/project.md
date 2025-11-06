Root README.md
# Ninja Turtles Pizza Parlor — Online & Mobile Ordering (Case Study)

> End-to-end data + process design for a pizza e-commerce workflow—**use cases, swimlanes, ERD, and UI prototype** aligned to inventory, vendors, purchasing (POs), and ERP-ready reporting.

**Course:** RIT MGIS 320 — Database Systems & Design  
**Role:** Data Modeler / Business Analyst (team)

---

## Overview
This case study models an online/mobile ordering system from **customers → carts → orders → payment → fulfillment**, with the operational backbone for **inventory**, **vendor management**, and **purchase orders**. The repo packages the exact artifacts you’d hand to engineering or an ERP integration team.

- **Artifacts:** Work Breakdown Structure (WBS), Use Cases, Swimlanes, ER Diagrams, UI Prototype Deck (PDFs)
- **Ops & ERP:** Item/Vendor masters, reorder logic, receiving + cost reconciliation
- **Data Quality:** Naming conventions, keys/FKs, status enums, audit fields

## Data Model Highlights
- Entities: `Customer`, `Address`, `Order`, `OrderItem`, `Payment`, `MenuItem`, `Coupon`,  
  `InventoryItem`, `Vendor`, `PurchaseOrder`, `POItem`
- **Keys & junctions** for many-to-many relationships; **status enums** for reporting fidelity
- **Audit columns** (`created_at`, `updated_at`); **RI** through foreign keys

## Process Highlights
- **Use Cases:** Place Order, Manage Inventory, Purchase Inventory (PO→Receive), Handle Refund
- **Swimlanes:** clear handoffs across *Customer*, *Web App*, *Kitchen*, *Inventory*, *Vendors*
- **Asynchronous flows:** auth/capture, fulfillment, receiving

## ERP & Operations Alignment
- Reorder points + vendor lead times at item/vendor level  
- POs tie to receiving and cost reconciliation for clean month-end close  
- Normalized masters for reliable analytics and integrations

---

## How to Review
1. Skim the **ERD** and **Swimlane** previews above.  
2. Open `/docs/04_ER_Diagrams.pdf` for schema details.  
3. Flip `/docs/model` to see the user journey + admin ops.  
4. Use `/docs/02_Use_Cases.pdf` and `/docs/03_Swimlanes.pdf` for process specifics.

---

## My Role & Contributions
- Led **ERD design**; drafted core **use cases**; standardized keys & status enums  
- Documented **data quality rules** and reconciliation steps  
- Compiled **UI prototype deck** and hand-off notes

---

## Notes
- **Source of truth:** PDFs in `/docs`. Images in `/model` are exported previews.    
- **Contact:** Jacob Goodman · RIT — MIS (GIS Immersion) · [jkg9629@rit.edu] · [www.linkedin.com/in/jacob-goodman585]
