# 📦 Tableau Superstore Case Study

### Delivery Optimization, Seasonal Sales Trends & Global Expansion Strategy

---

## 📌 Project Overview

This Tableau-based analytics project dives deep into customer delivery patterns, product seasonality, and global market performance for a multinational superstore. The project is divided into **three focused cases**, using interactive dashboards to derive actionable insights for improving customer satisfaction, boosting seasonal sales, and guiding global expansion decisions.

---

## 🎯 Project Objectives

* Resolve delivery-related customer complaints and delays
* Analyze seasonal product performance for better inventory and marketing decisions
* Recommend regions for profitable expansion using sales and profit data

---

## 📁 Dataset Overview

* **Source**: Tableau Superstore Sample Dataset
* **Records**: 51,290 orders
* **Key Fields**:

  * `Order ID`, `Customer ID`, `Product Name`, `Category`
  * `Order Date`, `Ship Mode`, `Shipping Days`
  * `Sales`, `Profit`, `Quantity`, `Region`, `Country`, `Market`
  * `Order Priority`, `Segment`, etc.

---

## 🔍 Case 1: Customer Delivery Feedback Analysis

### 📝 Problem Statement

Customers have raised concerns about delayed deliveries. The aim is to assess whether deliveries match selected shipping modes and priorities, and identify causes behind the delays.

### 📊 Key Dashboard Insights

1. **Shipping Mode Accuracy**
   ✅ Delivery matches selected mode:

   * First Class: 2,925 orders
   * Second Class: 2,188 orders
   * Same Day: 1,013 orders

2. **Priority-Based Delivery**
   ⚠️ Mixed Results:

   * Critical orders: Avg. 2 shipping days
   * Low priority: Avg. 6 shipping days

3. **Delivery Delays**
   ⚠️ Standard Class has the most delays (9,000+ orders took 4+ days)

   * Heatmaps show delays mainly in low-priority orders

4. **Returns Due to Late Delivery**
   ❓ Not confirmed — return data not sufficient to conclude

5. **Regional Delivery Issues**
   ❌ Not fully addressed — recommend adding regional KPIs in future versions

### 📌 Recommendations

* Enhance **Standard Class** logistics
* Restrict **Same Day/First Class** shipping to **Critical/High** priority orders
* Add **region-wise late delivery tracking** for further insights

---

## ❄️ Case 2: Seasonal Product Sales Analysis

### 📝 Problem Statement

The business wants to identify which products are affected by seasonal sales shifts to plan inventory and promotions effectively.

### 📊 Key Dashboard Insights

* **Sales Comparison**:

  * Summer Sales: ₹3.3M
  * Other Seasons: ₹6.8M

* **Products with High Seasonal Variation**:

  * **High Speed Internet**: +8,188 units difference
  * **Hewlett Packard**: +8,060 units difference

### 📌 Recommendations

* Focus **seasonal promotions** on High Speed Internet and HP products
* Use trend data to forecast **stocking needs** and manage **seasonal discounts**
* Target peak seasons with personalized **email and ad campaigns**

---

## 🌍 Case 3: Global Sales & Expansion Strategy

### 📝 Problem Statement

The superstore seeks to expand its footprint. The goal is to identify regions with the highest profitability and future growth potential.

### 📊 Key Dashboard Insights

* **Global Coverage**:

  * Orders: 51,290
  * Countries: 165
  * Markets: USCA, Europe, Asia Pacific, LATAM, Africa

* **Top Markets by Profit**:

  * Europe: ₹449,552
  * Asia Pacific: ₹403,176
  * LATAM & Africa: Lowest returns

* **Year-wise Growth Trends**:

  * Consistent profit rise from 2012 to 2015
  * Europe & Asia Pacific show **sustainable, upward trends**

* **Future Sales Estimations**:

  * Europe and Asia Pacific are ideal for investment due to historical and projected performance

### 📌 Recommendations

* **Expand aggressively** in Europe & Asia Pacific
* **Pause large-scale investments** in LATAM and Africa until improvement
* Reignite USCA market with **targeted regional campaigns** to improve stagnant growth

---

## 🛠 Tools & Skills Used

* **Tool**: Tableau Desktop
* **Skills Applied**:

  * Dashboard Design
  * Data Cleaning & Filtering
  * Geo-Spatial Analysis
  * Heatmaps & Seasonal Forecasting
  * KPI Tracking & Profit Estimation

---

## 👤 Author

**Khushboo Verma**


