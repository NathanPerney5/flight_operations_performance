# ✈️ Flight Operations Performance Dashboard (2015)

## 📌 Project Overview

This project analyzes U.S. flight operations data from 2015 to evaluate airline performance, delay patterns, and operational efficiency.

The objective is to demonstrate end-to-end data skills:

* Data cleaning and transformation
* Analytical SQL with large datasets (5M+ rows)
* Data modeling for BI tools
* Interactive dashboard design with Tableau

---

## 🎯 Key Objectives

* Analyze flight delays across time, airlines, and airports
* Identify the main causes of delays
* Evaluate airline performance
* Highlight geographical patterns in delays
---

## Data

Raw data is not included in this repository due to size limitations.

You can download the dataset here:
(https://www.kaggle.com/datasets/usdot/flight-delays)

---

## 📊 Dashboard Overview

The dashboard includes 5 main components:

### 1. KPI Overview

* Total Flights
* Average Arrival Delay
* Cancellation Rate

### 2. Monthly Delay Trend

* Evolution of average arrival delay across months
* Identification of seasonal patterns

### 3. Airline Performance

* Comparison of airlines based on average arrival delay
* Identification of best and worst performers

### 4. Airport Delay Map

* Geographic visualization of departure delays
* Identification of congested hubs and regional patterns

### 5. Delay Causes

* Distribution of delay causes:

  * Late Aircraft
  * Airline
  * Weather
  * Air System
  * Security

---

## 🛠️ Tech Stack

* **DuckDB** → Analytical SQL on large dataset (5M+ rows)
* **Tableau Public** → Dashboard visualization
* **GitHub** → Project versioning and portfolio

---

## 🧱 Data Pipeline

1. Raw data ingestion (CSV files)

2. Data transformation with DuckDB:

   * Aggregations (monthly, airline, airport)
   * KPI computation
  
3. Export of optimized datasets for Tableau
4. Dashboard creation

---

## 📂 Project Structure

```text
flight-delay-analysis/
│
├── data/
│   ├── raw/                # Original datasets
│   ├── processed/          # Cleaned & aggregated datasets
│
├── notebooks/
│   ├── data_understanding_analysis.ipynb
├── visual/
│   ├── screenshot of Tableau dashboard
│
├── README.md
```

---

## 📈 Key Insights

* Flight delays peak during summer months (June–July)
* Late aircraft is the primary cause of delays
* Major airport hubs show higher congestion levels
* Significant variation in performance across airlines

---

## 🚀 What This Project Demonstrates

* Ability to handle large datasets efficiently
* Strong SQL skills (aggregation, modeling)
* Understanding of business KPIs
* Data visualization and storytelling
* End-to-end BI workflow

---

## 🔗 Next Steps

* Add interactive filters (airline, region, time)
* Extend analysis to multiple years

