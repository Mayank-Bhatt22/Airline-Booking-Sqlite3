# Airline-Booking-Sqlite3
Analyzed airline booking data using SQLite3 with a focus on data cleaning and date transformation. Extracted date components from booking timestamps, created derived columns, and prepared structured data for daily analysis. This project demonstrates SQL-based preprocessing and time-based analytics using SQLite.
# ✈️ Airline Booking Data Analysis using SQLite3

## 📌 Project Overview
This project focuses on analyzing airline booking data using **SQLite3**. The primary goal was to clean and transform booking date-time data and prepare it for **daily and time-based analysis** using SQL queries.

---

## 📊 Dataset
- Airline booking dataset
- Contains booking date-time information and booking details
- Raw timestamps required transformation for analysis

---

## 🧹 Data Cleaning & Transformation
Key preprocessing steps performed using SQLite3:

- Converted booking timestamp columns into usable date formats
- Extracted date-only values from datetime fields
- Created derived columns for simplified daily analysis
- Ensured consistency and accuracy for reporting

Example SQL logic:
```sql
DATE(book_date) AS booking_date
