<img width="721" height="403" alt="Screenshot 2026-07-20 184236" src="https://github.com/user-attachments/assets/c55d2909-0fb2-4f71-bf57-c1d83478c14b" />


# Fleet Performance & Delivery Efficiency Dashboard

## Project Overview

This project was developed as part of the **Power BI Module End Project**. The dashboard analyzes fleet performance and delivery efficiency using Power BI to help monitor transportation operations and support business decision-making.

---

## Objective

The objective of this project is to analyze fleet performance by measuring on-time deliveries, fuel efficiency, maintenance costs, and transportation costs. The dashboard provides interactive insights that help improve operational efficiency, optimize fleet utilization, and reduce logistics costs.

---

## Dataset

The project uses two tables:

### Trip_Data
- Trip ID
- Vehicle ID
- Driver ID
- Origin
- Destination
- Distance (km)
- Fuel Consumed (L)
- Delivery Status
- Delivery Date

### Vehicle_Master
- Vehicle ID
- Vehicle Type
- Capacity (kg)
- Maintenance Cost

---

## Data Cleaning

- Imported Excel dataset into Power BI.
- Replaced missing Fuel Consumed values using mean imputation.
- Verified data types.
- Created relationship between **Trip_Data** and **Vehicle_Master** using **Vehicle_ID**.

---

## Data Model

Relationship:

Trip_Data[Vehicle_ID] → Vehicle_Master[Vehicle_ID]

Relationship Type:
- One-to-Many
- Single Direction

---

## DAX Measures

Created the following measures:

- Fuel Efficiency
- On-Time Trips
- Total Trips
- On-Time Delivery %
- Cost per km

---

## Dashboard Visualizations

- Bar Chart – On-Time Delivery % by Destination
- Line Chart – Fuel Efficiency by Delivery Date
- Card – Average Cost per km
- Card – Average Fuel Efficiency
- Pie Chart – Average Maintenance Cost by Vehicle Type

---

## AI Visuals

- Key Influencers
- Decomposition Tree

> **Note:** The Q&A visual was not available in the installed Power BI Desktop version.

---

## Key Insights

- Identified delivery performance across destinations.
- Analyzed fuel efficiency trends over time.
- Measured transportation cost per kilometer.
- Compared maintenance costs across vehicle types.
- Used AI visuals to identify factors affecting delivery status and transportation costs.

---

## Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel

---


GitHub: https://github.com/yourusername

LinkedIn: https://www.linkedin.com/in/yourprofile
