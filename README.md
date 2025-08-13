# ✈ Airline Database – SQL Analytics Capstone

From improving travel routes to diving deep into passenger details, this project embodies the power of *data-driven choices in the aviation sector*.  
Built using *PostgreSQL/MySQL* with *30+ complex queries*, it reveals operational insights to support strategic airline decisions.

---

## 🌟 Key Features

1️⃣ *Tackling 30 Complex Queries* – Unveiling detailed insights to boost operational efficiency.  
2️⃣ *Streamlining Routes* – Formulating queries to optimize flight paths for better resource use.  
3️⃣ *Analyzing Passenger Data* – Examining passenger information to customize services and enhance travel experience.  
4️⃣ *Decision-Making with Data* – Guiding strategic decisions by thoroughly understanding the airline database.

---

## 🔍 Project Overview
This SQL capstone explores how airlines can use data to:
- *Optimize scheduling* for aircraft and crew
- *Increase route profitability* through data-backed decisions
- *Enhance customer satisfaction* via targeted services
- *Monitor performance* with clear operational KPIs

---

## 📊 Data Description
*Core Tables:*
- *Bookings* – booking_id, book_date, passenger_id, flight_id, fare_class, price, status  
- *Flights* – flight_id, flight_no, origin_airport, destination_airport, scheduled_dep, actual_dep, scheduled_arr, actual_arr, aircraft_id, status  
- *Passengers* – passenger_id, name, gender, loyalty_tier, country  
- *Aircrafts* – aircraft_id, model, manufacturer, capacity  
- *Airports* – airport_code, city, country, timezone  

---

## 📂 Project Structure
Airline_DB_Capstone/
│
├── queries/
│   ├── 01_date_formatting.sql
│   ├── 02_top_routes.sql
│   ├── …
│
├── data/
│   ├── bookings.csv
│   ├── flights.csv
│   ├── passengers.csv
│
├── README.md
└── insights_report.pdf

---

## 🛠 Tech Stack
- *Database:* PostgreSQL / MySQL  
- *Query Language:* SQL (CTEs, Joins, Window Functions, Subqueries)  
- *Tools:* MySQL Workbench  
- *Version Control:* Git & GitHub  

---

## 📈 Insights & Outcomes
- *Route Efficiency:* Identified underperforming flight routes and suggested reallocation for a 12% improvement in seat occupancy.  
- *Passenger Segmentation:* Segmented passengers by loyalty tier & spending patterns to target premium services.  
- *On-Time Performance:* Found that 18% of delays were linked to a specific aircraft type, prompting operational review.  
- *Revenue Insights:* Top 5 profitable routes contributed to 40% of total revenue.  

---

## 🎯 What I Learned
- Writing *optimized SQL queries* using *CTEs, window functions, and subqueries*  
- Applying *real-world data analysis* in the aviation industry  
- Using *data modeling principles* for relational databases  
- *Debugging & validating queries* for accuracy and performance  
- Transforming raw SQL results into *actionable business insights*

---

## 🚀 Performance Optimization
- *Indexing:* Added indexes on frequently queried columns (flight_id, passenger_id) to improve query speed.  
- *Query Refactoring:* Used CTEs to reduce repeated calculations.  
- **Partitioning
