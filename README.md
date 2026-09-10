# Uber Analytics Dashboard – Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Project](https://img.shields.io/badge/Project-Uber%20Analytics-000000)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📊 Project Overview

**Uber Analytics Dashboard** is an interactive Microsoft Power BI report designed to analyze Uber booking, revenue, vehicle, cancellation, and rider-related performance.

The report provides a multi-page executive-style dashboard that turns operational data into interactive KPIs and visual insights. Users can navigate between dedicated pages and apply filters to explore the data from different business perspectives.

## 📁 Power BI File

- **Power BI report:** `Uber_Dashboard(1).pbix`
- **Platform:** Microsoft Power BI Desktop
- **Report format:** `.pbix`

## 🧭 Dashboard Pages

The report contains **five main pages**:

### 1. Home

The landing page of the dashboard.

**Purpose**
- Provides the main navigation experience.
- Uses Uber branding and visual assets.
- Allows users to move to the analytical sections of the report.

### 2. Overview

Provides a high-level summary of Uber performance.

**Key analysis areas**
- Total revenue / booking value
- Booking counts
- Completed and lost bookings
- Average distance
- Total distance
- Monthly performance trends
- Vehicle-type performance
- Payment-method analysis
- Booking status and related operational metrics

**Visuals include**
- KPI cards
- Monthly trend charts
- Column/bar charts
- Donut charts
- Slicers
- Supporting vehicle and payment visuals

### 3. Vehicle

Focuses on vehicle-level performance and customer/booking behavior.

**Key analysis areas**
- Vehicle type
- Booking and revenue performance
- Average distance
- Completed vs. lost bookings
- Vehicle-related customer metrics
- Payment-method distribution

**Visuals include**
- KPI cards
- Vehicle detail table
- Trend/summary charts
- Donut charts
- Interactive slicers

### 4. Revenue

Focuses on revenue and booking-value analysis.

**Key analysis areas**
- Revenue / booking value
- Monthly revenue trends
- Revenue by vehicle type
- Revenue by payment method
- Booking performance
- Completed vs. lost bookings

**Visuals include**
- KPI cards
- Area and column charts
- Bar charts
- Donut charts
- Interactive filters

### 5. Rider

Focuses on rider/customer behavior and booking outcomes.

**Key analysis areas**
- Customer count
- Customer activity
- Booking volume
- Revenue
- Average distance
- Completed vs. lost bookings
- Incomplete/cancelled ride reasons
- Payment methods
- Rider-related details

**Visuals include**
- KPI cards
- Monthly customer trends
- Detailed tables
- Bar charts
- 100% stacked bar chart
- Donut charts
- Slicers

## 🔑 Key Metrics

The report contains reusable measures for important business KPIs, including:

| Metric | Purpose |
|---|---|
| `Booking_Value` / Revenue | Measures booking revenue/value |
| `Booking_Count` | Counts bookings |
| `Complete_Bookings` | Tracks completed bookings |
| `Lost_Bookings` | Tracks lost bookings |
| `Avg_Distance` | Calculates average trip distance |
| `Total_Distance` | Calculates total trip distance |
| `Customer_Count` | Measures customer/rider count |
| `Booking_Reomve_Status` | Supports booking outcome/status analysis |
| `Monthly_Revenue` | Supports monthly revenue reporting |

## 🗂️ Data Model / Main Entities

The Power BI report references several model entities, including:

- **Uber** – primary booking/ride data
- **_Measures** – centralized DAX measures
- **Calender** – calendar/month-related analysis
- **Date_Axis** – date axis used for trend visuals
- **IMG** – vehicle/image mapping and vehicle-type information
- **Cancel Rides** – cancellation/incomplete ride information

The report also uses image assets for Uber branding and vehicle/category presentation.

## 🎛️ Interactivity

The dashboard is designed for interactive exploration.

Typical interactions include:

- Date/month filtering
- Vehicle-type filtering
- Cross-filtering between visuals
- Slicers for focused analysis
- Page navigation
- Detailed tables for drill-down style inspection

When a slicer or visual is selected, related visuals can update to provide a focused view of the selected segment.

## 🛠️ Technologies Used

- **Microsoft Power BI Desktop**
- **DAX** for calculated measures
- **Power Query / Power BI data model**
- Interactive charts, cards, slicers and tables
- Custom report theme and image assets

## 🚀 How to Open the Dashboard

1. Install **Microsoft Power BI Desktop**.
2. Open `Uber_Dashboard(1).pbix`.
3. Allow Power BI to load the report and its model.
4. If Power BI asks for data-source credentials or refresh permissions, provide the required credentials.
5. Navigate through **Home → Overview → Vehicle → Revenue → Rider**.
6. Use slicers and visual selections to explore the report.

## 🔄 Refreshing the Data

If the underlying data source is still connected:

1. Open the `.pbix` file in Power BI Desktop.
2. Go to **Home → Refresh**.
3. Resolve any data-source credential or privacy prompts if shown.
4. Verify that all visuals update correctly.
5. Save the report after a successful refresh.

> **Note:** Refresh requirements depend on the original data source and connection configuration. The README does not assume a specific external database or file path.

## 🎯 Business Questions This Dashboard Can Help Answer

- How much revenue is being generated?
- How many bookings are being completed?
- How many bookings are lost or incomplete?
- How does performance change month by month?
- Which vehicle types contribute most to revenue or bookings?
- What is the average and total travel distance?
- Which payment methods are most commonly used?
- How does customer activity change over time?
- What are the main incomplete/cancellation reasons?
- How do booking outcomes vary across different segments?

## 📌 Project Highlights

- Multi-page interactive Power BI dashboard
- Dedicated executive overview page
- Vehicle, revenue, and rider analysis
- KPI-driven reporting
- Monthly trend analysis
- Interactive slicers and cross-filtering
- Payment-method analysis
- Booking-status analysis
- Custom visual assets and Uber branding

## 📂 Suggested Project Structure

```text
Uber-Analytics-Dashboard/
│
├── README.md
├── Uber_Dashboard(1).pbix
└── assets/
    └── dashboard-images-and-branding/
```

## 👤 Author

**Aman Saroj**

Data Analytics / Business Intelligence Project

## 📄 License

This project is intended for educational, portfolio, and demonstration purposes.

Uber and related branding/assets are the property of their respective owners. This project is not an official Uber product.

---

**Built with Microsoft Power BI | Uber Analytics Dashboard**
