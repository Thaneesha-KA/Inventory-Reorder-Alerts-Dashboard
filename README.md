# Inventory-Reorder-Alerts-Dashboard

Overview:
This project is built using Microsoft Power Platform to manage inventory and automate low stock alerts.

Tools Used:
- Dataverse (Database)
- Power Apps (Frontend app)
- Power Automate (Alert system)
- Power BI (Dashboard)

Features:
- Track stock levels (OnHand)
- Prevent negative stock
- Automated low stock alerts (email)
- Dashboard with stock insights

Key Logic:
- Alert triggers when OnHand <= ReorderPoint
- AlertSent prevents repeated alerts
- Reset when stock is replenished

Dashboard Insights:
- Stock distribution by category
- Stock status (Good / Low)
- Total low stock items

Conclusion:
This system helps businesses monitor inventory and automate reorder decisions efficiently.
