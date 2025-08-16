# Supply Chain Correlation Heatmap

- **Email:** 24f3002795@ds.study.iitm.ac.in
- **Files**
  - `correlation.csv` — Pearson correlation matrix for:
    - Supplier_Lead_Time, Inventory_Levels, Order_Frequency, Delivery_Performance, Cost_Per_Unit
  - `heatmap.png` — Excel conditional-format heatmap (Red–White–Green), cropped square (400–512 px)

## How it was produced
1. Enabled Analysis ToolPak (File → Options → Add-ins → Analysis ToolPak).
2. Data → Data Analysis → Correlation on the 5 columns (labels in first row).
3. Applied 3-Color Scale: Red (-1), White (0), Green (1).
4. Exported correlation to CSV and captured heatmap screenshot.

