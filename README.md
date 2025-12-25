
*Inventory Restocking System*
The Inventory Restocking System is a C‑based application designed to help businesses automatically monitor stock levels, calculate restocking quantities, and reduce the chances of both overstocking and stockouts.
It is ideal for small to medium‑sized shops, supermarkets, warehouses, and other inventory‑driven operations.

*Problem Statement*
Every business that sells products, whether in retail stores, warehouses, or online platforms, needs to keep track of its inventory.
Too much stock increases storage costs and can lead to wastage, especially for perishable goods. 
Too little stock leads to lost sales and customer dissatisfaction. Managing this balance manually is difficult, time‑consuming, and prone to errors.

*The Inventory Restocking System solves this problem by:*

- Automatically monitoring stock levels
- Comparing current quantities with minimum thresholds
- Suggesting or generating restock quantities when items run low
 This helps businesses maintain the right amount of inventory at the right time.

*Features*
Accepts the number of inventory items from the user and processes each one is sequence.
Store and manage detaols for each item:
- Item name
- Current stock
- Minimum/threshold level
- Target/reorder quantity
Automatically calculate how much to restock based on:
- Current stock
- Minimum level
- Target stock level
  Restock Amount = Required level - Current Stock
Prints a clear message for each item
- if current stock is below threshold
- if current stock is at or above threshold
Displays a final message: "Restocking check complete" after processing all items.
*Tech Stack*
Language: C
Concepts Used:
- Arrays / structures
- Functions and modular programming
- Conditional logic and loops

*The Inventory Restocking System can be applied in:*
- Retail shops and supermarkets.
- E‑commerce warehouses.
- Hospitals and pharmacies (for medicines and supplies).
- Manufacturing units (for raw materials and components).

*By automating restock calculations and alerts, the system:*
- Reduces losses due to stockouts and overstocking.
- Improves customer satisfaction by keeping products available.
- Saves employee time spent on manual stock checks.


*Future Enhancements*
- Support for more complex item attributes (IDs, categories, prices).
- File storage or database integration to persist inventory data.
- Simple analytics such as total items below threshold or restock cost estimation.
- Graphical or web‑based interface on top of the existing logic.

