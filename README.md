# 📊 **Hospitality Analytics – Power BI Dashboard**

A data analytics project for a multi-city hospitality chain. This project delivers insights on revenue, occupancy, ADR, RevPAR, cancellations, booking platforms, and week-over-week performance trends using Power BI.

---

# 📘 **PROJECT OVERVIEW**

This project focuses on analyzing the performance of a multi-city hospitality chain using Power BI. The goal is to understand hotel revenue, occupancy, customer behavior, room performance, and booking patterns across various cities and room categories.

The dashboard provides insights for:

* Revenue optimization
* Occupancy growth
* Channel performance evaluation
* Cancellation and no-show management
* Pricing and room-class analytics
* Week-over-week trend analysis

This comprehensive BI solution enables the hospitality management team to **make data-driven decisions**, improve room utilization, boost revenue, and enhance customer experience.

---

# 📂 **DATA SOURCE**

The analysis is based on **5 CSV datasets** stored in the project folder:

### **1. dim_date.csv**

Date-level information for 3 months (May–July)

### **2. dim_hotels.csv**

Hotel metadata: property_id, property_name, category, city

### **3. dim_rooms.csv**

Room metadata: room_class and room type

### **4. fact_bookings.csv**

Transactional booking dataset including:

* booking status
* check-in/check-out
* revenue generated & realized
* number of guests
* booking platform
* customer ratings

### **5. fact_aggregated_bookings.csv**

Aggregated room availability & successful bookings per property and room type.

---

# 🛠 **TOOLS & TECHNOLOGIES USED**

| Category            | Tools                               |
| ------------------- | ----------------------------------- |
| BI & Visualization  | **Power BI Desktop**                |
| Data Transformation | **Power Query (M Language)**        |
| Calculations & KPIs | **DAX (Data Analysis Expressions)** |
| Data Modeling       | **Star Schema Design**              |
| Data Storage        | **CSV Files**                       |
| Project Management  | **GitHub Repository**               |

---

# 🔧 **TECHNIQUES USED**

### **1. Data Cleaning**

* Adjusted weekend logic (Friday & Saturday = weekend)
* Standardized column headers
* Removed redundant fields
* Applied proper datatypes in Power Query

### **2. Data Modeling**

* Built a **Star Schema** with:

  * Fact tables: fact_bookings, fact_aggregated_bookings
  * Dimension tables: dim_date, dim_hotels, dim_rooms
* Established one-to-many relationships

### **3. DAX Calculations**

Created **26+ measures** including:

* Revenue, ADR, RevPAR
* Occupancy %
* Realisation %
* DBRN, DSRN, DURN
* Week-over-week % changes
* Room-class and platform splits

### **4. Week-over-Week Trend Analysis**

Used dynamic DAX measures to compare performance across weeks:

* Revenue WoW Change %
* ADR WoW Change %
* RevPAR WoW Change %
* Occupancy WoW Change %

### **5. Interactive Dashboarding**

* Slicers: City, Room Class, Date Type
* Drill-through pages
* Dynamic KPI cards
* Line charts & bar charts
* Performance comparison visuals

---

# 📊 **BUSINESS METRICS (KPIs)**

### **Revenue Metrics**

* **Revenue Realized**
* **Revenue Generated**
* **ADR (Average Daily Rate)**
* **RevPAR (Revenue Per Available Room)**

### **Occupancy & Room Metrics**

* **Occupancy %**
* **Total Bookings**
* **Total Capacity**
* **DBRN (Daily Booked Room Nights)**
* **DSRN (Daily Sellable Room Nights)**
* **DURN (Daily Utilized Room Nights)**

### **Customer Behavior Metrics**

* **Cancellation %**
* **No-Show Rate %**
* **Realisation %**
* **Average Rating**

### **Channel & Category Metrics**

* **Booking % by Platform**
* **Booking % by Room Class**

### **Trend Metrics**

* **WoW Revenue Change %**
* **WoW Occupancy Change %**
* **WoW ADR/RevPAR/Realisation Change %**

---

# 📈 **KEY INSIGHTS FROM DASHBOARD**

### 🏨 **1. City-Level Performance**

* **Mumbai** generated the highest revenue but had comparatively lower occupancy.
* **Hyderabad** achieved **the best occupancy % (~67%)** with strong ratings.
* **Delhi** showed moderate performance across all KPIs.

---

### 💰 **2. Revenue Insights**

* Total Revenue = **₹582M**
* Highest contribution from **Atliq Exotic** & **Atliq Palace**
* **ADR stable at ~₹12.7K** across the period

---

### 🛏 **3. Occupancy & Room Utilization**

* Overall Occupancy = **58.55%**
* **Weekend occupancy higher** than weekdays (64% vs 56%)
* Presidential rooms have highest ADR but lowest volume

---

### 📦 **4. Booking Platform Insights**

* **Direct online + makeyourtrip** contribute the most bookings
* OTA channels show slightly higher cancellation rates
* Realisation % fairly stable across platforms (~69%)

---

### ❌ **5. Cancellation & No-Show Behavior**

* Average cancellation rate ~25%
* No-show rate low but impacts revenue leakage

---

### 🔄 **6. Week-over-Week Trends**

* Revenue spikes observed around Week 23 & Week 29
* Occupancy fluctuates between **50–62% WoW**
* RevPAR improves on weekends consistently

---

# 📑 **RECOMMENDATIONS**

### 🎯 **1. Improve Occupancy in Mumbai & Bangalore**

* Introduce dynamic pricing (lower weekday rates)
* Focus campaigns on low-performing weeks

### 📢 **2. Strengthen OTA and Direct Bookings**

* Improve incentives for direct online bookings
* Optimize platform performance with targeted discounts

### 🤝 **3. Reduce Cancellation Rate**

* Implement partial non-refundable models
* Offer rebooking incentives

### 🛌 **4. Optimize Room Class Revenue**

* Promote Elite & Premium rooms with packaged offers
* Increase visibility of Presidential rooms

### ⭐ **5. Enhance Customer Satisfaction**

* Improve service quality in properties with low ratings (e.g., Mumbai Atliq Bay)
* Analyze rating correlation with occupancy

### 🗓 **6. Leverage Weekend Demand**

* Increase weekend pricing (yield management)
* Promote weekday packages to balance occupancy

---

# 🙏 **ACKNOWLEDGMENT**

I would like to thank:

* **Codebasics** for providing the hospitality challenge dataset.
* **Power BI community** for learning resources.


This project was completed as a part of a learning journey in data analytics & business intelligence.

---


