# 🏡 Airbnb Listings Dashboard

### 📊 Overview

This project explores **Airbnb listing data** from two major U.S. cities — **Chicago** and **New Orleans** — to uncover insights into market dynamics, host behavior, pricing trends, and property distribution.
Using **Power BI**, raw data is transformed into an **interactive dashboard** that allows users to compare and explore Airbnb activity across both cities.

The primary objective is to conduct **Exploratory Data Analysis (EDA)** and convert findings into a visually appealing dashboard that supports decision-making for stakeholders, hosts, and analysts.

---

### 🎯 Objectives

* Analyze neighborhood-level performance and pricing variations
* Identify dominant property and room types
* Understand host behavior and review patterns
* Visualize city-level comparisons through interactive dashboards

---

### 🗂️ Data Source

Data was collected from **open Airbnb datasets** on Kaggle, containing detailed information for each listing.

**Datasets Used:**

* `Chicago.csv`
* `NewOrleans.csv`

**Key Attributes:**

* Listing ID
* Property and room types
* Host details and review metrics
* Availability and pricing
* Neighborhood information

---

### 🌍 Why Airbnb?

Airbnb operates in **191+ countries**, hosting **4 million listings** and serving **150 million users**.
Its appeal lies in offering **affordable, authentic local experiences**.
With a valuation of **$32 billion** and global growth of **153%** since 2009, Airbnb provides rich data for analyzing tourism and accommodation trends.

---

### ⚙️ Methodology

#### 1️⃣ Data Cleaning and Transformation

Performed using **Python (Pandas, NumPy)** for data preprocessing and structuring before importing into Power BI.

#### 2️⃣ Power BI Data Modeling

DAX Calculated Columns created:

* `Host Category`
* `Price Category`
* `Latitude Round`
* `Longitude Round`

---

### 📈 Dashboard Sections

#### 1. **Overview of Airbnb**

* **KPI Card:** Total Listings → *10,177 listings*
* **Slicers:** City, Room Type, Price Category
* **City-wise Breakdown (Pie Chart):**

  * Chicago → 60% (≈ 6,113 listings)
  * New Orleans → 39% (≈ 4,064 listings)

#### 2. **Property Analysis**

* **Top 10 Neighborhoods by Price (Clustered Bar Chart):**
  Highlights premium areas like *Freret (Chicago)* and *Near North Side (New Orleans)*.
* **Listings by Neighborhood (Stacked Bar Chart):**
  Shows hotspots like *Central Business District (Chicago)* and *Near North Side (New Orleans)*.
* **Room Type Distribution (Donut Chart):**
  Majority are *Entire home/apartment* — indicates preference for full-property stays.

#### 3. **Pricing Analysis**

* **Avg Price by Location (Map Chart):**
  Bubble sizes show average price — *Chicago generally higher than New Orleans*.
* **Avg Price vs Room Type (Clustered Column Chart):**

  * *Hotel rooms → Highest average price*
  * *Shared rooms → Most budget-friendly*

#### 4. **Host Analysis**

* **Host Category vs Avg Reviews & Pricing (Stacked Bar Chart):**

  * *Experienced hosts* → Highest reviews and pricing
  * *New hosts* → Fewer reviews and lower prices (competitive entry strategy)

---

### 💡 Key Insights

1. **Popular Neighborhoods:**

   * *French Quarter (New Orleans)* → Highest average price ($2,576.08)
   * *CBD (New Orleans)* → Most listings (673 properties)

2. **Room Type Trends:**

   * *Entire home/apartment* dominates (8,408 listings)
   * *Private rooms* most common in low-price range

3. **Location Patterns:**

   * Chicago & New Orleans show distinct neighborhood-level differences
   * *French Quarter* = premium tourist area
   * *CBD* = business-focused, high volume

4. **Price Variation:**

   * New Orleans generally cheaper than Chicago
   * Premium pricing linked to hotel rooms and prime neighborhoods

5. **Host Patterns:**

   * *Experienced hosts* enjoy more reviews and charge higher prices
   * *Moderate hosts* show an interesting anomaly — slightly higher pricing than experienced ones

---

### 🧠 Tools & Technologies

* **Python:** Pandas, NumPy
* **Power BI:** DAX, Data Modeling, Interactive Visuals
* **Excel:** Preprocessing & Validation

---

### 📷 Dashboard Preview

<img width="1920" height="1080" alt="Airbnb Insight's" src="https://github.com/user-attachments/assets/d64f540e-85ce-419f-a88a-821051d06815" />


### 🧩 Insights Summary

This Power BI dashboard empowers analysts and hosts to:

* Compare city-level performance
* Identify profitable property types
* Design better pricing strategies
* Understand how host experience impacts guest engagement

---

### 🏁 Conclusion

The **Airbnb Listings Dashboard** demonstrates the power of combining **data cleaning in Python** with **visual storytelling in Power BI**.
It delivers clear, interactive, and actionable insights that help decode urban accommodation trends across two major U.S. cities.

---
