# 🏨 Hotel Operations Data Modeling & Analytics | Power BI Project

This project demonstrates a full-scale **Power BI data modeling and reporting solution** for a hotel chain's operations. Leveraging rich, multi-dimensional datasets, it models and visualizes key aspects such as guest bookings, staff performance, billing, events management, and service utilization.

The project showcases how raw hotel data can be structured and visualized to generate insights that support operational efficiency and strategic planning.

---

## 📁 Files Included

- `HotelOperationsDashboard.pbix` – Complete Power BI report with all relationships, measures, and visuals
- `Hotel_Data_v2.xlsx` – Raw and structured data used in the report (multiple dimension and fact tables)

---

## 🗃️ Data Model Overview

The model includes **star schema design** integrating multiple fact and dimension tables:

### 🔹 Fact Tables
- `FactBooking`: Guest bookings including dates, status, channels, rooms
- `FactBilling`: Financial data on services, rooms, and discounts
- `FactEventsManagement`: Revenue, costs, and attendance from hotel events
- `Fact_Staff_Schedule`: Employee schedules, performance, labor cost
- `FactTasksDone`: Task tracking for maintenance and service teams

### 🔸 Dimension Tables
- `DimGuest`, `DimEmployee`, `DimRoom`, `DimLocation`, `DimPromotion`, `DimEvent`, etc.
- Support analysis on demographics, service types, departments, shifts, booking channels, and more

---

## 📊 Key Insights Delivered

- **Revenue Trends**: By service, room type, promotion, and location
- **Guest Demographics**: Loyalty tiers, contact data, identity types
- **Operational Efficiency**: Shift management, labor cost vs. hours worked
- **Event Performance**: Attendance, revenue, planner performance
- **Booking Behavior**: Cancellation rates, booking lead time, seasonal demand
- **Maintenance Tracking**: Task types, durations, spare parts usage

---

## 🛠 Tools Used

- **Power BI Desktop**: Data modeling (relationships, DAX), report design
- **Microsoft Excel**: Raw data structuring and preparation
- **DAX**: Custom KPIs and performance metrics
- **Star Schema**: Efficient and scalable data modeling

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `HotelOperationsDashboard.pbix` in Power BI Desktop.
3. Ensure the `Hotel_Data_v2.xlsx` file is located in the same folder.
4. Refresh the data to enable full interactivity and explore the dashboards.

---

## 📈 Business Impact

This model supports:
- **Hotel managers** to optimize booking and staffing strategies
- **Finance teams** to track revenue and cost performance
- **Operations teams** to manage tasks and event planning
- **Executives** to view high-level summaries and drill down into issues

---

## 🧠 What I Learned

- Building an enterprise-ready data model using real-world business logic
- Designing for both exploratory and explanatory data analysis
- Applying DAX to calculate dynamic, contextual KPIs
- Creating reports that are actionable and intuitive

---
