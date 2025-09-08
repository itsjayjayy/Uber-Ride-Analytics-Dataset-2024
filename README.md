# 🚖 Uber Ride Bookings – Cleaned Dataset

## 📌 Overview
This repository contains a **cleaned Uber ride booking dataset** with **150,000 records** and **23 features**, prepared for analysis and machine learning tasks.  

The dataset captures details about ride bookings, trip outcomes, cancellations, distances, payments, and user/driver interactions.

---

## 📂 Dataset Information
- **File Name:** `uber_ride_bookings_cleaned.csv`  
- **Rows:** 150,000  
- **Columns:** 23  
- **Format:** CSV (Comma-Separated Values)  
- **Encoding:** UTF-8  

---

## 📊 Dataset Schema

### 1. Booking Metadata
- `Date` – Date of booking  
- `Time` – Timestamp of booking  
- `Booking ID` – Unique identifier for each ride  
- `Customer ID` – Unique passenger identifier  
- `Vehicle Type` – Category of booked vehicle (Bike, Auto, Sedan, etc.)  
- `Booking Status` – Status of booking (`Completed`, `Incomplete`, `Cancelled`, `No Driver Found`)  

### 2. Location Information
- `Pickup Location` – Pickup area/zone  
- `Drop Location` – Drop-off area/zone  

### 3. Performance Metrics
- `Avg VTAT` – Average Vehicle Turnaround Time (minutes)  
- `Avg CTAT` – Average Customer Turnaround Time (minutes)  
- `Ride Distance` – Distance traveled during trip (km)  
- `Speed` – Average ride speed (km/h)  
- `time` – Trip duration in hours (decimal)  

### 4. Cancellation & Incompletion
- `Cancelled Rides by Customer` – Indicator if cancelled by customer  
- `Reason for cancelling by Customer` – Cancellation reason given by customer  
- `Cancelled Rides by Driver` – Indicator if cancelled by driver  
- `Driver Cancellation Reason` – Cancellation reason given by driver  
- `Incomplete Rides` – Indicator if ride was incomplete  
- `Incomplete Rides Reason` – Reason for incompletion  

### 5. Value & Ratings
- `Booking Value` – Total fare charged (currency units)  
- `Driver Ratings` – Driver rating given by customer  
- `Customer Rating` – Customer rating given by driver  
- `Payment Method` – Payment type (UPI, Debit Card, Cash, etc.)  

---

## ✅ Data Cleaning & Preprocessing
This dataset has been **cleaned and standardized**:
- Removed duplicates  
- Fixed inconsistent datetime formats  
- Normalized categorical values  
- Handled missing/null entries  
- Filtered outliers in distance, value, and duration  

---

## 🔎 Sample Records
```text
| Date       | Time                | Booking ID  | Status         | Vehicle Type | Pickup Location   | Drop Location    | Value | Distance | Payment |
|------------|---------------------|-------------|----------------|--------------|------------------|-----------------|-------|----------|---------|
| 2024-03-23 | 2025-09-07 12:29:38 | CNR5884300  | No Driver Found| eBike        | Palam Vihar      | Jhilmil         | NaN   | NaN      | NaN     |
| 2024-11-29 | 2025-09-07 18:01:39 | CNR1326809  | Incomplete     | Go Sedan     | Shastri Nagar    | Gurgaon Sector 56| 237.0 | 5.73     | UPI     |
| 2024-08-23 | 2025-09-07 08:56:10 | CNR8494506  | Completed      | Auto         | Khandsa          | Malviya Nagar   | 627.0 | 13.58    | Debit   |


