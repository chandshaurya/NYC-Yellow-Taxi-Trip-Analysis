# 🚖 NYC Yellow Taxi Analytics Dashboard (Jan–May 2025)

A real-world business intelligence dashboard built on New York City Yellow Taxi trip data from January to May 2025 (~20 million rows). This Power BI project provides deep insights into urban ride patterns, fare behavior, payment trends, peak traffic periods, and zone profitability. Designed to support operational decision-making for city planners, taxi businesses, and transportation analysts.

---

## 🎯 Project Objective

To analyze large-scale transportation data from NYC Yellow Taxi trips and develop an interactive Power BI dashboard that helps uncover:

- 📈 Trends in ride frequency, revenue, and duration
- 🧭 Zone and borough-level performance
- 🧠 Passenger behavior by time, location, and payment mode
- 💰 Revenue growth, tip patterns, and fare type dynamics

---

## 📁 Dataset Overview

- **Source**: [NYC Taxi & Limousine Commission (TLC) Trip Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)   
- **Format**: `.parquet` files (Jan–May 2025)  
- **Size**: ~20 million records  
- **Core Columns**:
  - `pickup_datetime`, `dropoff_datetime`, `trip_distance`
  - `fare_amount`, `tip_amount`, `total_amount`
  - `payment_type`, `passenger_count`, `RatecodeID`
  - `PULocationID`, `DOLocationID`, `service_zone`

---

## 🛠️ Tools Used

| Tool        | Purpose                                      |
|-------------|----------------------------------------------|
| **Power BI**| Data modeling, dashboarding, DAX measures    |
| **DAX**     | KPIs, revenue growth, custom insights        |
| **Excel**   | Pre-processing and date formatting           |


---

## ✅ What I Did

- Cleaned and joined 5 months of `.parquet` data into a single data model
- Created calculated measures using **DAX** for revenue growth, averages, and ratios
- Applied **dynamic slicers** by month, borough, payment type, and zone
- Designed **5 fully interactive Power BI pages** using maps, cards, tables, heatmaps
- Built **insight boxes** and explained business trends visually

---

## 📊 Dashboard Pages

### 1️⃣ Executive Summary  
- Total Trips: **16M**, Revenue: **$516.46M**  
- Key KPIs: Avg Fare, Avg Distance, Avg Duration  
- Monthly trip and revenue trends  
- Revenue share by borough and payment type  
<img width="1216" height="707" alt="summary" src="https://github.com/user-attachments/assets/2cb86aa4-98fb-4e21-bbf2-1bb148fbca3c" />


### 2️⃣ Trips Overview  
- Ride count by hour, weekday, and month  
- Heatmap of trip frequency (Hour × Day)  
- Passenger count segmentation  
<img width="1241" height="713" alt="trips" src="https://github.com/user-attachments/assets/5199ea4b-2d2f-4f4c-96c8-f39d7500e75e" />

### 3️⃣ Revenue & Fare Analysis  
- Borough-wise revenue breakdown  
- Top 5 revenue-generating zones  
- Fare types, payment modes, tip % contribution  
<img width="1245" height="709" alt="revenue" src="https://github.com/user-attachments/assets/4d2e8029-84d3-4064-8ee4-ad17bcbea86e" />


### 4️⃣ Zone and Segment Analysis  
- Most visited zones  
- Trip count vs. trip duration  
- Longest distance trips by zone  
<img width="1246" height="710" alt="zone" src="https://github.com/user-attachments/assets/bbfd3a65-5d9e-40ce-aa87-95304f2c3b8f" />


### 5️⃣ Customer & Payment Insights  
- Tip-based zone ranking  
- Payment trends by zone and time  
- Card vs. Cash patterns across boroughs  
<img width="1242" height="718" alt="customer" src="https://github.com/user-attachments/assets/840be896-2039-4b05-8965-07fbf355129e" />


---

## 💼 Key Business Insights

- 💳 **Credit cards dominate**: Over **73% of all payments** were done using cards
- 🛫 **JFK & LaGuardia** are the most profitable zones — together generating **over $10M**
- 🧭 **Manhattan** alone contributed **~75% of total revenue** in 5 months
- 📈 **Revenue increased by 38.68%** from January to May — showing strong seasonal growth
- ⏰ **Rush hours (4–7 PM)** and **weekends** showed highest trip density
- 💰 **Tips formed ~10%** of total earnings — higher in airports and business zones

---

> 🔎 This dashboard brings together complex transportation data into simple, dynamic visuals that can guide fleet deployment, pricing decisions, and rider engagement strategies.






