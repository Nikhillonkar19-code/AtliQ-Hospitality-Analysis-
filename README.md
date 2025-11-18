

# 🧠 **Hospitality Analytics | Power BI • DAX • Power Query • Star Schema • Business Insights**




---

<!-- Badges -->

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-Analytics-0A75AD?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20Query-M%20Language-4CAF50?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data%20Modeling-Star%20Schema-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GitHub-Project-181717?style=for-the-badge&logo=github" />
</p>

---

# 🏨 **Hospitality Analytics Dashboard – Power BI Project**

A complete end-to-end **Business Intelligence solution** designed to help hospitality leaders make data-driven decisions on revenue, occupancy, customer behavior, cancellations, pricing, and channel performance.
This repository showcases my expertise across **Power BI, Data Modeling, DAX, Power Query, and Business Analytics**.

---

# 🌐 **PROJECT OVERVIEW**

This project analyzes the performance of a multi-city hospitality chain using **three months of operational data (May–July)**.
The dashboard translates raw data into actionable insights for:

* Revenue optimization
* Occupancy improvement
* Booking platform strategy
* Cancellation & no-show management
* Pricing performance (ADR, RevPAR)
* Room class contribution
* Week-over-week performance trends

The end result is a **manager-friendly, interactive analytical dashboard** that empowers leadership to make strategic and operational decisions with confidence.

---

# 📂 **DATA SOURCES**

The analysis is built using **5 structured CSV datasets**, forming a complete star-schema model:

### **1. dim_date** — Calendar table (date, month, week number, day type)

### **2. dim_hotels** — Hotel metadata (name, category, city)

### **3. dim_rooms** — Room class definitions

### **4. fact_bookings** — Individual customer booking transactions

### **5. fact_aggregated_bookings** — Daily room availability & successful bookings

These datasets collectively provide a **360° view of hotel operations**.

---

# 🛠 **TOOLS & TECHNOLOGIES USED**

| Category               | Tools                                 |
| ---------------------- | ------------------------------------- |
| **BI & Visualization** | Power BI Desktop                      |
| **Scripting / ETL**    | Power Query (M Language)              |
| **Metrics / KPIs**     | DAX                                   |
| **Data Modeling**      | Star Schema (Fact & Dimension Tables) |
| **Version Control**    | GitHub                                |
| **Data Format**        | CSV                                   |

---

# 🔧 **TECHNIQUES USED**

### **1️⃣ Data Cleaning & Preparation (Power Query)**

* Corrected weekend–weekday logic (Fri & Sat = weekend)
* Standardized headers & datatypes
* Removed redundant columns
* Ensured consistency across fact & dimension tables

### **2️⃣ Dimensional Data Modeling**

Created a clear **Star Schema**:

* Fact tables: *fact_bookings*, *fact_aggregated_bookings*
* Dimensions: *dim_date*, *dim_rooms*, *dim_hotels*

### **3️⃣ DAX for Advanced Analytics**

Developed **26+ professional DAX measures**, including:

* Revenue, Occupancy, ADR, RevPAR
* DBRN, DSRN, DURN
* Realisation %, Cancellation %, No-Show %
* WoW dynamic percent changes
* Platform & room class contribution metrics

### **4️⃣ Interactive Dashboard Experience**

* Dynamic slicers
* Drill-through pages
* KPI scorecards
* Line & bar charts
* Comparative analysis visuals
* Week-by-week trends

This ensures a smooth stakeholder experience.

---

# 📊 **BUSINESS METRICS (KPIs)**

### **📌 Revenue Metrics**

* Revenue Generated
* Revenue Realized
* ADR (Average Daily Rate)
* RevPAR (Revenue Per Available Room)

### **📌 Occupancy & Room Utilization**

* Occupancy %
* Total Bookings
* Total Capacity
* DBRN / DSRN / DURN

### **📌 Customer & Behavioral Metrics**

* Cancellation %
* No-Show %
* Realisation %
* Customer Rating

### **📌 Channel & Category Metrics**

* Booking % by Platform
* Booking % by Room Class

### **📌 Trend Metrics**

* Week-over-Week Revenue Change
* ADR / RevPAR Change %
* Occupancy Change %

---

# 📈 **KEY INSIGHTS FROM THE DASHBOARD**

### 🏙 **1. City-Level Performance**

* **Mumbai** leads in revenue but has weaker occupancy.
* **Hyderabad** delivers the **highest occupancy (~67%)** and strong customer ratings.
* **Bangalore** remains stable across major KPIs.

---

### 💰 **2. Revenue & Pricing Insights**

* Total Revenue: **₹582M**
* Highest performing properties: **Atliq Exotic** & **Atliq Palace**
* ADR remains stable at **~₹12.7K**

---

### 🛏 **3. Occupancy & Demand**

* Overall Occupancy: **58.55%**
* **Weekend occupancy (64%) > Weekday occupancy (56%)**
* Room class performance shows **Presidential rooms have high ADR but low volume**

---

### 📦 **4. Booking Channel Behavior**

* **Direct Online** and **Makeyourtrip** dominate booking contribution
* OTAs show higher cancellation tendencies
* Realisation % remains steady (~69%) across channels

---

### ⚠ **5. Cancellations & No-Shows**

* Cancellation rate: **~25%**
* No-show rate: low but still affects revenue reliability

---

### 🔄 **6. Week-over-Week Trends**

* Revenue spikes around Week 23 and Week 29
* Occupancy fluctuates between **50–62%**
* RevPAR consistently improves during weekends

---

# 📑 **RECOMMENDATIONS**

### 🎯 **1. Boost Occupancy in Low-Performing Cities**

* Deploy dynamic pricing (weekday discounts, weekend surge pricing)
* Target corporate travelers & long-stay guests

### 💼 **2. Strengthen Direct Booking Strategy**

* Promote direct booking discounts
* Reduce dependence on OTAs

### 🛑 **3. Reduce Cancellations**

* Introduce partially refundable models
* Provide rebooking credits to minimize revenue leakage

### 🏷 **4. Enhance Revenue from Premium Rooms**

* Upsell Elite/Premium rooms with packaged deals
* Promote high-ADR room classes during weekends

### ⭐ **5. Improve Customer Experience**

* Conduct service audits for low-rated hotels
* Use customer feedback loops for continuous improvement

### 🧳 **6. Leverage Weekend Demand**

* Launch weekend-specific promotional bundles
* Offer weekday packages to balance occupancy

---

# 🙏 **ACKNOWLEDGMENT**

Special thanks to:

* **Codebasics** for the dataset used in this project
* **Power BI Community** for knowledge sharing


This project showcases my ability to build **end-to-end BI solutions**, from raw data to powerful insights.

---


