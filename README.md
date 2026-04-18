# Inventory-Optimisation-Replenishment-Model-
🔍 Project Summary

This project centres on inventory control and stock decision-making using a simulated dataset that reflects real-world supply chain behaviour.

Rather than focusing on forecasting, the model is designed to answer a practical question:
“When should we reorder stock, and how much?”

It showcases how Excel can be used to build an operational tool that supports day-to-day planning, highlights risk areas, and improves stock efficiency.

🎯 What This Model Does
- Monitors stock levels across multiple SKUs
- Identifies items at risk of running out
- Calculates reorder points using demand and lead time
- Highlights excess stock and inefficiencies
- Allows users to test how changes impact inventory decisions

🛠️ Tools & Skills Demonstrated
- Excel formulas and structured modelling
- Data organisation across multiple sheets
- Business logic implementation (reorder calculations)
- Scenario-based analysis
- Dashboard design for operational reporting

🧱 How the Workbook Is Structured

The workbook is organised into layers to separate data, logic, and outputs:

SKU_Master
Contains core product data such as stock levels, demand, supplier details, and lead times

Movement_Ledger
Tracks stock inflows and outflows over time to simulate real inventory behaviour

Replenishment_Centre
Core calculation engine where reorder points, safety stock, and stock coverage are determined

Ops_Review
Aggregated insights by category and warehouse, helping identify pressure points

Model_Assumptions
Editable inputs such as demand changes and lead time adjustments

Control_Panel / Dashboard
A high-level operational view showing key metrics and stock health

⚙️ Core Logic

The model is built around a standard inventory control approach:

Reorder Point = (Demand × Lead Time) + Safety Stock

Where:

- Demand is based on weekly usage
- Lead Time reflects supplier delivery delays
- Safety Stock accounts for uncertainty

This ensures stock is replenished before shortages occur while avoiding overstocking.

🔄 Scenario Testing

Users can adjust key variables to explore different situations:

- Increased demand
- Supplier delays
- Changes in service levels

The model updates automatically to show how these changes affect:

- Reorder requirements
- Stock coverage
- Inventory risk

📊 Dashboard Focus

The dashboard is designed as an operations control view, not a reporting page. It highlights:

- Total inventory value
- Number of SKUs requiring action
- Average stock coverage
- Stock distribution across products

The goal is to make quick decisions rather than conduct in-depth analysis.

💡 Why This Project Matters

This project demonstrates the ability to:

- Translate business problems into structured Excel models
- Build tools that support operational decisions
- Work with realistic datasets and constraints
- Present outputs in a clear, usable format

🧾 Data Disclaimer

All data used in this project is simulated for portfolio purposes.
It is designed to reflect realistic inventory patterns, including variability in demand and supply conditions.
