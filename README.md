# Taxi-Booking-Revenue-Analytics
Interactive Power BI dashboard analyzing taxi bookings, revenue, vehicle performance, cancellations, and customer reviews.

# 🚕 Taxi Booking & Revenue Analytics Dashboard | Power BI

## 📌 About This Project

I built this Power BI dashboard to understand and analyze taxi booking data from a business perspective.

The dataset contains **150,000 taxi booking records** with information about bookings, vehicle types, revenue, ride distance, payment methods, cancellations, and customer and driver ratings.

The main idea behind this project was simple: instead of looking at thousands of rows in a CSV file, I wanted to turn the data into an interactive dashboard where important business questions could be answered quickly.

The dashboard focuses on **booking performance, vehicle performance, revenue, cancellations, customer experience, and overall business performance**.

---

## 🎯 What I Wanted to Find Out

While working on this project, I focused on questions like:

- How many bookings are completed, cancelled, or incomplete?
- How does booking value change over time?
- Which vehicle types perform better in terms of bookings and revenue?
- What are the main reasons behind customer and driver cancellations?
- How do customer and driver ratings compare?
- Which payment methods contribute more to booking value?
- How does revenue vary throughout the day?
- What does the overall business performance look like?

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **CSV**
- Data Cleaning & Transformation
- Data Visualization
- Business Intelligence

---

## 📂 Dataset

The project uses the `rideBookings.csv` dataset containing:

- **150,000 booking records**
- **21 fields**

Some of the important fields include:

- Booking ID
- Booking Date & Time
- Booking Status
- Customer ID
- Vehicle Type
- Pickup Location
- Drop Location
- Booking Value
- Ride Distance
- Payment Method
- Customer Rating
- Driver Rating
- Customer Cancellation Reason
- Driver Cancellation Reason
- Incomplete Ride Reason
- Average VTAT
- Average CTAT

The original dataset is included in the **Dataset** folder of this repository.

---

## 📊 Key Numbers

Here are some of the main metrics explored in the dashboard:

| KPI | Value |
|---|---:|
| Total Bookings | 150K |
| Completed Rides | 93K |
| Total Booking Value | ₹51.85M |
| Average Customer Rating | 4.40 |
| Average Driver Rating | 4.23 |
| Cancellation Rate | 25% |

---

# 📈 Dashboard Pages

## 🏠 Homepage

The homepage acts as the main navigation screen for the dashboard.

It provides access to the different analysis sections without overcrowding the landing page with charts.

---

## 📊 Overall Analysis

This page gives a quick overview of the booking performance.

It includes:

- Total bookings
- Completed rides
- Cancelled rides
- Cancellation rate
- Booking status distribution
- Monthly booking performance

The purpose of this page is to understand the overall booking situation before going deeper into individual areas.

---

## 🚗 Vehicle Analysis

This page focuses on the performance of different vehicle types.

It looks at:

- Completed rides by vehicle type
- Revenue by vehicle type
- Cancellation by vehicle type
- Average ride distance
- Revenue vs. ride distance

This helps compare how different vehicle categories perform across important business metrics.

---

## 💰 Revenue Analysis

The Revenue page focuses on understanding where booking value and revenue are coming from.

It includes:

- Booking value by payment method
- Revenue per KM by vehicle type
- Monthly booking value
- Revenue trends
- Revenue by day part

This page helps break down revenue performance from different perspectives.

---

## ❌ Cancellation Analysis

This page focuses specifically on booking cancellations.

It includes:

- Completed bookings
- Cancelled bookings
- Total bookings
- Cancellation rate
- Customer cancellation reasons
- Driver cancellation reasons

Separating customer and driver cancellation reasons makes it easier to understand where cancellations are coming from.

---

## ⭐ Reviews & Ratings

This page focuses on customer and driver experience.

It includes:

- Average customer rating
- Average driver rating
- Customer retention
- Customer rating trends
- Customer ratings by vehicle
- Driver ratings by vehicle
- Driver rating distribution

This section provides a different perspective on the business by looking beyond bookings and revenue.

---

## 📋 Summary

The Summary page brings important business metrics together in one place.

It includes:

- Total bookings
- Booking value
- Revenue per KM
- Customer retention
- Service quality score
- Revenue momentum
- Booking value by day part
- Quarterly average booking value

The goal of this page is to give a quick business-level overview without having to go through every individual analysis page.

---

# 🔍 What I Learned from the Data

Working on this dashboard helped me understand how the same dataset can answer different business questions depending on how it is analyzed.

Some of the patterns I explored include:

- Completed rides make up the largest booking outcome category.
- Vehicle types differ in terms of booking volume, revenue, and ride distance.
- Payment methods contribute differently to overall booking value.
- Customer and driver cancellations have different reasons and patterns.
- Customer and driver ratings provide two different views of service experience.
- Revenue and booking patterns vary across different parts of the day.
- Looking at trends over time gives more context than looking at individual totals.

---

# ⚙️ My Power BI Workflow

I didn't want the project to be only about creating charts, so I followed a basic analytics workflow:

### 1. Data Preparation
Imported the raw CSV dataset into Power BI and reviewed the available fields and data types.

### 2. Data Cleaning
Used **Power Query** to clean and prepare the data for analysis.

### 3. Calculations
Created calculated columns and **DAX measures** for the KPIs and analysis required for the dashboard.

### 4. Visualization
Selected different visual types depending on the question being answered, including cards, column charts, line charts, scatter charts, and a gauge.

### 5. Dashboard Design
Created separate pages for different areas of the business instead of putting everything onto one page.

### 6. Interactivity
Added date slicers, navigation buttons, and interactive visuals so users can explore the data themselves.

---

# 🎨 Dashboard Features

The dashboard includes:

- Interactive date slicers
- KPI cards
- Gauge visualization
- Column charts
- Bar charts
- Line charts
- Scatter chart
- Interactive navigation buttons
- Cross-filtering
- Consistent dark and gold theme

---

# 🖼️ Dashboard Preview

## Homepage

![Homepage](Screenshots/HomePage.png)

## Overall Analysis

![Overall Analysis](Screenshots/Overall.png)

## Vehicle Analysis

![Vehicle Analysis](Screenshots/VehicleAnalysis.png)

## Revenue Analysis

![Revenue Analysis](Screenshots/Revenue.png)

## Cancellation Analysis

![Cancellation Analysis](Screenshots/Cancellations.png)

## Reviews & Ratings

![Reviews & Ratings](Screenshots/Reviews.png)

## Summary

![Summary](Screenshots/Summary.png)

---

# 📁 Repository Structure

```text
Taxi-Booking-Revenue-Analytics/
│
├── README.md
│
├── Dataset/
│   └── rideBookings.csv
│
├── PowerBI/
│   └── Taxi_Booking_Revenue_Analytics.pbix
│
└── Screenshots/
    ├── HomePage.png
    ├── Overall.png
    ├── VehicleAnalysis.png
    ├── Revenue.png
    ├── Cancellations.png
    ├── Reviews.png
    └── Summary.png
