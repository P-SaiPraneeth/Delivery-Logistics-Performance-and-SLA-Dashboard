📦 Delivery Logistics Performance & SLA Dashboard (Power BI)
📌 Project Overview

This project presents an interactive Power BI dashboard designed to analyze delivery logistics performance, parcel characteristics, and SLA (Service Level Agreement) compliance.
The dashboard helps identify operational inefficiencies, understand delivery behavior across modes, distances, and parcel weights, and evaluate SLA breaches.

🎯 Objectives

Analyze delivery performance across delivery modes and courier partners

Study the impact of parcel weight and distance on delivery cost and time

Monitor SLA breach percentage as an executive KPI

Enable data-driven decision-making using interactive visuals

📊 Dashboard Features
🔹 Key KPIs

SLA Breach % (Gauge)

On-Time vs Delayed Delivery Distribution

Delivery Volume Insights

🔹 Visual Analysis

100% Stacked Column Chart
Parcel Weight Category vs Delivery Status

Scatter Plot
Delivery Cost vs Package Weight with Distance Categorization
(Local / Regional / Long-Haul)

Bar Charts
Delivery performance across modes and parcel categories

Donut Chart
Parcel distribution by weight category

🔹 Interactivity

Slicers for:

Delivery Partner

Delivery Mode

Region

Logo-based page navigation

Tooltips for detailed inspection

🧠 Key Insights

Heavier parcels show higher variability in delivery performance

Long-haul deliveries tend to incur higher delivery costs

Certain delivery modes contribute disproportionately to SLA breaches

SLA breach percentage provides a quick view of operational reliability

🛠️ Tools & Technologies Used

Power BI Desktop

DAX (for measures like SLA Breach %)

Power Query (M) for data transformation

Custom visuals (Box Plot / Scatter)

Interactive navigation using buttons and images

📐 SLA Definition Used

A delivery is considered an SLA breach if:

delivery_time_hours > expected_time_hours


SLA Breach % is calculated dynamically using a Power BI measure to ensure accurate results under filters.

📁 Repository Structure
📦 Delivery-Logistics-Dashboard
 ┣ 📊 dashboard.pbix
 ┣ 📄 README.md

🚀 How to Use

Download the .pbix file

Open it in Power BI Desktop

Interact with slicers and visuals

Navigate between pages using logo buttons

📌 Use Cases

Academic projects (Data Analytics / BI)

Logistics performance monitoring

SLA compliance tracking

Operational decision support
