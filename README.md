# Uber-Ride-Analytics-Dataset-2024
Uber Ride Analytics Dataset 2024 This comprehensive dataset contains detailed ride-sharing data from Uber operations for the year 2024, providing rich insights into booking patterns, vehicle performance, revenue streams, cancellation behaviors, and customer satisfaction metrics.
# 🚖 Uber Ride Bookings – Cleaned Dataset

## 📌 Overview
This repository contains a **cleaned and structured Uber ride booking dataset**, preprocessed to remove inconsistencies and ready for:

- Data analysis  
- Visualization  
- Machine learning models  

It provides insights into **ride demand patterns, trip characteristics, pricing behavior, and customer trends**.

---

## 📂 Dataset Information
- **File Name:** `uber_ride_bookings_cleaned.csv`  
- **Format:** CSV (Comma-Separated Values)  
- **Encoding:** UTF-8  
- **Delimiter:** `,`  

---

## 📊 Dataset Contents

### 1. Booking Information
- `booking_id` – Unique ride identifier  
- `pickup_datetime` – Ride pickup timestamp  
- `dropoff_datetime` – Ride drop-off timestamp  
- `status` – Ride status (completed, cancelled, no-show)  

### 2. Trip Metrics
- `trip_duration` – Total trip duration (minutes/seconds)  
- `trip_distance` – Distance of the trip (km or miles)  
- `fare_amount` – Total fare charged  
- `surge_multiplier` – Surge pricing factor  

### 3. Geospatial Data
- `pickup_latitude`, `pickup_longitude` – Pickup location coordinates  
- `dropoff_latitude`, `dropoff_longitude` – Drop-off location coordinates  
- `pickup_area`, `dropoff_area` – Named zones (if available)  

### 4. User & Driver Info
- `user_id` – Unique passenger identifier  
- `driver_id` – Unique driver identifier  
- `payment_type` – Payment method (card, cash, wallet)  
- `cab_category` – Type of cab (e.g., UberX, UberBlack, UberPool)  

---

## ✅ Data Cleaning & Preprocessing
The dataset has been cleaned and standardized:
- Removed duplicate records  
- Standardized datetime formats  
- Handled missing/null values  
- Normalized categorical variables  
- Filtered outliers (unrealistic fares, distances, or trip durations)  

---

## 🔎 Potential Use Cases
- **Exploratory Data Analysis (EDA):** ride demand by time, day, or location  
- **Geospatial Analysis:** pickup/drop-off hotspots  
- **Machine Learning:**  
  - Fare prediction  
  - Trip duration estimation  
  - Ride demand forecasting  
- **Business Insights:** driver allocation, surge pricing analysis  

---

## ⚠️ Notes
- Timestamps may require conversion to local timezone.  
- Latitude/longitude should be verified against the appropriate coordinate reference system (CRS).  
- Identifiers (`user_id`, `driver_id`) are anonymized for privacy.  

---



---





