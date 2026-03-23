# End-to-End Procurement and Shipment Tracking Analysis


## Project Overview
This project analyzes procurement and shipment data for 10,324 orders, covering the full lifecycle from purchase requisition (PQ) to delivery. It tracks vendors, purchase orders (POs), shipments, delivery timelines, and associated costs to provide insights into supply chain and vendor performance.


## Dataset
- **Total Records:** 10,324  
- **Columns:** 33  

- **Key Columns:** Project Code, PQ #, PO / SO #, ASN/DN #, Country, Vendor, Shipment Mode, Scheduled & Delivered Dates, Product Group, Line Item Quantity, Line Item Value, Freight & Insurance Cost.  

- **Data Types:**  
  - `datetime64` – Delivery & scheduled dates  
  - `float64` – Costs and prices  
  - `int64` – Quantities  
  - `object` – Textual information  

## Objectives
- Track end-to-end procurement and delivery lifecycle.  
- Analyze vendor performance and delivery efficiency.  
- Evaluate costs including line item value, freight, and insurance.  
- Identify trends in product categories, dosages, and shipment modes.

## Tools & Libraries
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib / Seaborn (optional for visualization)
