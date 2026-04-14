# 🚗 Uber Ride Analytics Dashboard — Power BI
> An interactive multi-page Power BI dashboard analyzing Uber ride data across bookings, revenue, cancellations, vehicle types, and ratings.

## 📌 Purpose
This project explores Uber ride data to uncover patterns in booking behavior, revenue generation, cancellation trends, and driver/customer satisfaction. The goal was to build a clean, navigable dashboard that tells a complete story — from high-level KPIs down to granular breakdowns by vehicle type and market.

## 🛠️ Tech Stack
**Power BI Desktop** - Dashboard design, data modeling, and visualization
**DAX** - Custom measures (Cancellation Rate, Total Booking Status) 
**Power Query** - Data transformation and loading 
**Excel / CSV** - Source data format                                        


## 📂 Data Source
The dataset was provided by **[DataSpace Academy](https://dataspace.academy/)** as part of their Data Analytics training program. It is a simulated Uber ride dataset containing the following key fields:

- `Booking ID` — Unique identifier per ride
- `Booking Status` — Success, cancelled by customer, cancelled by driver
- `Booking Value` — Revenue per ride
- `Ride Distance` — Distance covered per trip
- `Vehicle Type` — UberGo, Premier, UberXL, etc.
- `Payment Method` — Cash, UPI, card, etc.
- `Customer ID` / `Customer Rating`
- `Driver Ratings`
- `Reason for cancelling by Customer` / `Driver Cancellation Reason`
- `Date` — Date of the booking


## ✨ Features / Highlights
### 🏠 Home Page
- Clean landing page with navigation buttons linking to all 5 analytical pages.

### 📊 Overall
- Total Booking Value KPI card
- Booking Status breakdown (pie chart)
- Bookings over time (line chart)
- Date slicer for dynamic filtering

### 🚙 Vehicle Type Analysis
- Booking Value and Ride Distance (sum + average) broken down per vehicle type
- Visual cards paired with vehicle images for each category

### 💰 Revenue
- **Revenue by Payment Method** — clustered column chart
- **Ride Distance Distribution** — clustered column chart
- **Top 5 Customers** by booking value (pivot table)
- Date slicer for period-based analysis

### ❌ Cancellation
- KPI cards: Total Bookings, Successful Bookings, Cancelled Bookings, Cancellation Rate
- Pie charts for cancellation reasons split by **Customer** vs **Driver**
- DAX measure: `Cancellation Rate = Cancelled Bookings / Total Bookings`

### ⭐ Ratings
- Customer Rating and Driver Rating variance displayed per vehicle type
- Card-based layout across all vehicle categories for side-by-side comparison


## 📸 Dashboard Preview
> Home Page - [Home Page](https://github.com/NITISH-SAHOO/Power-BI/blob/main/Snapshot%20of%20Dashboard.png)
> Overall - [Overall](https://github.com/NITISH-SAHOO/Power-BI/blob/main/Snapshot%20of%20Dashboard%20(Overall).png)
> Vehical Type - [Vehical Type](https://github.com/NITISH-SAHOO/Power-BI/blob/main/Snapshot%20of%20Dashboard%20(Vehical%20Type).png)
> Revenue - [Revenue](https://github.com/NITISH-SAHOO/Power-BI/blob/main/Snapshot%20of%20Dashboard%20(Revenue).png)
> Cancellation - [Cancellation](https://github.com/NITISH-SAHOO/Power-BI/blob/main/Snapshot%20of%20Dashboard%20(Cancellation).png)
> Rating - [Rating](https://github.com/NITISH-SAHOO/Power-BI/blob/main/Snapshot%20of%20Dashboard%20(Rating).png)


## 🚀 How to Open
1. Download the `.pbix` file from this repository.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. Use the navigation buttons on the Home Page to explore each section.
4. Use the **Date slicer** on each page to filter by time period.

## 👤 Author
**Nitish Sahoo** — BCA Student & Data Analytics Trainee  
[LinkedIn](www.linkedin.com/in/nitish-sahoo-924540346) | [GitHub](https://github.com/NITISH-SAHOO)
