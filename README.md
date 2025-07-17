# Pharmaceutics-Inventory-Analysis-
 
### To design a dynamic Pharma Inventory Management System in Excel that can intelligently track inventory status, forecast restocking needs, and ensure compliance by monitoring expiry timelines. The goal was to simulate a real-world inventory management solution for pharmaceutical products, suitable for both supply chain professionals and data analysts.

#### Key Features
- Reorder Point (ROP) Calculation
Automatically computes the optimal reorder point using:
ROP = (Average Daily Usage × Lead Time) + 20% Safety Stock
This ensures timely procurement before stockouts, even during unexpected demand spikes or delays.

- Status Classification System
Each batch is tagged as one of:

- Safe — stock is adequate, not expiring soon

- Restock Needed — current stock is below calculated ROP

- Expiring Soon — expiry date within 30 days

- Expired — expiry date already passed
Logic is driven by a formula combining stock levels and expiry timelines.

#### KPI Dashboard
Interactive dashboard displaying:

- Total expired batches

- Count of batches below reorder point

- Number of safe vs expiring batches

- Average days to expiry

- Top 10 batches requiring immediate restock

- Region-wise distribution of ROP breaches

#### Regional Breakdown with Slicers
Users can filter all visuals by region (North, South, East, West) to view localized performance.

- Advanced Visuals

- Bar chart: Stock vs ROP for top-selling medicines

- Pie chart: Inventory health status (Safe vs Risky)

- Line chart: Region-wise trend of products below ROP

- Column chart: Expiry timeline view by month

#### Alerts & Recommendations
- Color-coded KPI cards and visual alerts for quick decision-making.
- Helps identify risk zones and prevent non-compliance or drug wastage.

#### Sample Insights Unlocked
- 157 batches are already expired, posing regulatory and safety concerns.

- 51 batches need immediate restocking, many of which are critical drugs like Amoxicillin and Ciprofloxacin.

- West region showed the least number of ROP breaches, while East had the highest.

- Only 5 batches are expiring in the next 30 days — manageable but must be monitored.

