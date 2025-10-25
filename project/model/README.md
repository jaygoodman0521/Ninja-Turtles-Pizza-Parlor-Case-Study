# Model Previews (Images)

This folder contains **exported PNG previews** of the core design artifacts to make the repo skimmable in seconds.  
**Source of truth** remains the PDFs in `/docs`.

## Files
- `erd.png` — Entity-Relationship Diagram (core schema)
- `swimlane_order_flow.png` — Order flow handoffs across actors
- `ui_menu_cart.png` — Prototype: browse menu + build cart
- `ui_checkout_status.png` — Prototype: checkout + order status
- `admin_inventory_purchasing.png` — Prototype: inventory levels, POs, receiving

## Update Instructions
1. Make edits in the original docs (`/docs/04_ER_Diagrams.pdf`, `/docs/03_Swimlanes.pdf`, UI deck).
2. Export updated pages as **PNG** at ~**1920×1080** (or 2× scale for clarity).
3. Keep filenames stable (see above).  
4. Verify the root `README.md` previews still render (they reference these filenames).

## Conventions
- Neutral background, readable line weights, legible labels at 100% zoom.
- No sensitive data; diagrams are illustrative only.
- Alt text is provided in the root README for accessibility.

**Reminder:** If previews and PDFs diverge, reviewers should trust the PDFs in `/docs`.

## Notes
- **Source of truth:** PDFs in `/docs`. Images in `/model` are exported previews.   
- **Contact:** Jacob Goodman · RIT — MIS (GIS Immersion) · [jkg9629@rit.edu] · [www.linkedin.com/in/jacob-goodman585]
