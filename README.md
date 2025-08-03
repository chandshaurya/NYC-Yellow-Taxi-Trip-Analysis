# 🚖 NYC Yellow Taxi Analytics Dashboard — Power BI Project

A detailed business intelligence dashboard using NYC Yellow Taxi trip data (Jan–May 2025). This end-to-end data analytics project demonstrates real-world data cleaning, data modeling, spatial analytics, time-series analysis, and dashboard storytelling using Power BI.

---

## 🎯 Project Objective

To build a multi-page interactive Power BI dashboard that uncovers key transportation trends in New York City using millions of rows of taxi trip data. The goal is to provide stakeholders (e.g., city planners, transport authorities, business strategists) with actionable insights into ridership patterns, revenue flows, and service performance.

---

## 📁 Dataset Description

**Source:** [NYC Taxi & Limousine Commission (TLC) Trip Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
**Files Used:** Monthly `.parquet` files for **Jan 2025 to May 2025**  
**Rows Analyzed:** ~20 million records (5 months combined)  
**File Identifier:** `Source.Name` column represents monthly source (e.g., `Jan2025`, `Feb2025`)

### 🧾 Key Columns Used:
| Column Name              | Description                                 |
|--------------------------|---------------------------------------------|
| `tpep_pickup_datetime`   | Pickup timestamp                            |
| `tpep_dropoff_datetime`  | Dropoff timestamp                           |
| `trip_distance`          | Distance in miles                           |
| `fare_amount`            | Fare paid by customer                       |
| `tip_amount`             | Tip amount                                  |
| `total_amount`           | Total paid (fare + tip + extras)            |
| `passenger_count`        | Number of passengers                        |
| `payment_type`           | Payment method (card, cash, etc.)           |
| `RatecodeID`             | Rate type (e.g., airport, negotiated)       |
| `PULocationID` / `DOLocationID` | Pickup and drop-off zone codes (geo) |
| `VendorID`               | Taxi vendor/company ID                      |

---

## 📊 Dashboard Architecture

The project is divided into **8 key dashboard pages**, of which **5 are fully complete**, and 3 are under development.

---

### ✅ Page 1: Executive Summary
**Purpose:** Provide high-level KPIs for business stakeholders

- 🔢 KPIs: Total Trips, Total Revenue, Avg Fare, Avg Tip, Avg Distance
- 📈 Monthly performance comparison (Jan–May)
- 📊 Revenue vs. trip count trend lines
- 📌 Interactive filters: Month, Vendor, Payment Type

- <img width="1349" height="780" alt="Screenshot 2025-08-04 000200" src="https://github.com/user-attachments/assets/b861e540-5a94-41ef-8be6-9b5a5806f45e" />


---

### ✅ Page 2: Trips Overview
**Purpose:** Identify volume distribution by vendor, day, and passenger profile

- 📅 Day-wise trip frequency bar chart
- 👥 Passenger count segmentation
- 🏢 Vendor comparison – trip volume and performance
- 🧭 Average trip distance by passenger type

<img width="1354" height="783" alt="Screenshot 2025-08-04 000218" src="https://github.com/user-attachments/assets/55468489-b95f-41fa-ae93-9027e1f34c08" />

---

### ✅ Page 3: Revenue & Fare Analysis
**Purpose:** Deep dive into fare economics and customer tipping behavior

- 💳 Payment type distribution (cash vs. card vs. others)
- 💰 Avg fare per passenger count
- 📊 Revenue distribution by tip category
- 📌 Donut + stacked visuals on total and tip-based earning categories

<img width="1356" height="781" alt="Screenshot 2025-08-04 000238" src="https://github.com/user-attachments/assets/b0fcaac4-0b7d-4744-8a84-ab353679bd77" />

---

### ✅ Page 4: Geospatial Analysis
**Purpose:** Map-based insights to identify urban mobility trends

- 🗺️ Pickup & drop-off density heatmaps using NYC zone coordinates
- 🚕 Top 10 active pickup and drop-off zones
- 🛫 Airport (JFK/LGA) trip analysis and contribution
- 🌆 Borough-level trip and revenue distribution

<img width="1352" height="780" alt="Screenshot 2025-08-04 000252" src="https://github.com/user-attachments/assets/446ec931-a20f-45f9-a453-5c1b2b6554d8" />

---

### ✅ Page 5: Hourly and Day-Wise Analysis
**Purpose:** Analyze rider behavior over time

- 🔥 Heatmap of hourly trip count (Hour × Day)
- 🧭 Morning vs. evening rush hour trend line
- 🎯 Average trip distance/time by hour of day
- 📅 Most active days and time slots (business optimization)

<img width="1356" height="781" alt="Screenshot 2025-08-04 000305" src="https://github.com/user-attachments/assets/e31bad13-891c-414f-b50f-8e222faab3d0" />

---

### 🧪 Page 6: Forecasting (🔄 Work in Progress)
**Purpose:** Predict future trip volumes and revenue flows

- ⏳ Time series forecasting using Power BI's built-in analytics
- 📈 Trend line forecast with confidence intervals
- 📆 Expected seasonality and demand planning

---

### 🧩 Page 7: Clustering & Segmentation (🔄 Work in Progress)
**Purpose:** Identify distinct behavior patterns across zones or customers

- 🤖 Manual clustering based on trip distance, fare, tip, and vendor
- 🏷️ Create customer segments: high-tippers, frequent riders, airport users
- 📌 Visual segmentation using scatter and radar charts

---

### 📚 Page 8: Behavioral & Anomaly Insights (🔄 Work in Progress)
**Purpose:** Identify outliers and behavioral traits in riders and vendors

- ❗ Short-distance high-fare analysis
- 📉 Trip cancellations or low-tip pattern detection
- 👤 Compare new vs. repeat passenger profiles (proxy via trip frequency)

---

## 🛠️ Tools & Technologies Used

| Tool/Tech        | Use Case                                      |
|------------------|-----------------------------------------------|
| **Power BI**     | Dashboard creation, DAX, storytelling         |
| **Excel**        | Pre-cleaning of flat files                    |
| **Parquet Files**| Raw NYC TLC data loading                      |
| **DAX**          | KPI and measure formulation                   |
| **Geo Maps**     | Pickup/dropoff heatmaps (ArcGIS/Map visual)  |
| **Power BI Bookmarks & Navigation** | UX design, page transitions |

---

## 📍 Business Impact Simulated

- Help city authorities allocate more taxis during peak hours
- Support decisions for airport fare regulation and tip behavior
- Predict future revenue drops or surges based on travel trends
- Zone prioritization for fleet expansion or driver deployment

---

## 📌 Key Learnings

- 🧠 Worked with real-world high-volume datasets (~20M+ rows)
- 🧮 Mastered advanced Power BI visuals and storytelling design
- 🧭 Performed geospatial and temporal analytics in one BI system
- 🧠 Prepared future-ready dashboards with forecasting & clustering
- 📈 Improved decision-support thinking from raw data



