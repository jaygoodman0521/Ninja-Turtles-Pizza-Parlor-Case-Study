# Ninja-Turtles-Pizza-Parlor-Case-Study
End-to-end case study designing an online/mobile pizza ordering system—use cases, swimlanes, ERD, and UI prototype aligned to ERP &amp; inventory.


**Overview**

Ninja Turtles Pizza Parlor is a compact, real-world case study in database systems & design. It models an online/mobile pizza ordering business from customer order flow to inventory and vendor purchasing—and packages the full set of artifacts you’d hand to engineering or an ERP integration team: Use Cases, Swimlanes, ER Diagrams, WBS, and a UI prototype deck.

Scope: customers → carts → orders → payment → fulfillment

Ops & ERP: inventory levels, reorder points, vendor lead times, purchase orders, receiving & reconciliation

Artifacts: WBS, Use Cases, Swimlanes, ERD, UI Deck (PDFs)

Course: MGIS 320 — Database Systems & Design (RIT)


**Why this project?**

Hiring managers and engineers need clean, reviewable design before build. This repo shows how I translate business requirements into:

Process clarity (use cases, swimlanes, handoffs)

Data fidelity (normalized ERD, keys, junctions, status enums, audit columns)

Operational alignment (inventory + purchasing modeled for ERP and trustworthy reporting)


**Quick preview**

Use Cases: Place Order, Manage Inventory, Purchase Inventory (PO → Receive), Handle Refund

Swimlanes: clear handoffs across Customer, Web App, Kitchen, Inventory, Vendors

ERD: Customer, Address, Order, OrderItem, Payment, MenuItem, Coupon, InventoryItem, Vendor, PurchaseOrder, POItem

Controls: referential integrity, naming conventions, validation & reconciliation checklists


**Outcomes**

ERP-ready schema with vendor & item masters, reorder logic, receiving & cost reconciliation

Trustworthy reporting across orders, payments, inventory, and purchasing

Reusable patterns for loyalty, reviews, delivery dispatch, and promotions


**Repo structure**
/docs
  01_WBS.pdf
  02_Use_Cases.pdf
  03_Swimlanes.pdf
  04_ER_Diagrams.pdf
/docs/model
  05_UI_Prototype_Deck.pdf
/assets
  erd.png              # ERD preview
  swimlane_order.png   # Swimlane preview
  ui_checkout.png      # UI preview
README.md              # This case study


**How to review (90-second tour)**

Open /assets/erd.png and /assets/swimlane_order.png for the big picture.

Skim /docs/04_ER_Diagrams.pdf (entities, keys, junctions, status).

Flip /docs/05_UI_Prototype_Deck.pdf to see the user journey and admin/inventory views.


**My role & contributions**

**Inventory Management & 3rd Party Vedor Portal**: Led ERD design; drafted core use cases; standardized keys & designed 3rd party vendor portal for mobile app and website.

Documented data quality rules and reconciliation steps

Compiled UI prototype deck and hand-off notes for implementation

Contact: Jacob Goodman · RIT — MIS (GIS Immersion) · [jkg9629@rit.edu] · [www.linkedin.com/in/jacob-goodman585]
