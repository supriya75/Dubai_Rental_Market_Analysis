# Dubai Rental Market Analysis (Power BI)

## 📊 Project Overview

This project analyzes the Dubai rental market using Power BI, focusing on pricing behavior, market segmentation, and investment positioning.

The objective is to derive **data-driven insights for real estate decision-making**, including identifying premium areas, high-liquidity zones, and efficient investment opportunities.

---

## 📁 Dataset

* ~34,000 rental listings across Dubai
* Key attributes:

  * Location
  * Rent (AED)
  * Bedrooms
  * Area (sqft)
  * Property Type

---

## ⚙️ Data Cleaning & Preparation

* Removed invalid rent values (0 and unrealistic entries)
* Handled extreme outliers in rent and area
* Managed 0-bedroom edge cases
* Created derived metrics:

  * Rent per Sqft
  * Rent per Bedroom

---

## 📊 Dashboard Structure

### 1️⃣ Executive Overview

* KPIs:

  * Average Rent: 211K AED
  * Median Rent: 145K AED
  * Avg Rent per Sqft: 132 AED
  * Total Listings: 34,229

📌 **Insight:**
Average rent is ~45% higher than median → indicating strong positive skew due to luxury properties.

---

### 2️⃣ Area Market Structure & Price Efficiency

* Compared locations based on:

  * Average Rent
  * Rent per Sqft
  * Listings (Liquidity)

📌 **Insights:**

* Downtown Dubai → Premium Core (high efficiency + liquidity)
* Palm Jumeirah → Luxury Segment (high volatility, skewed pricing)
* Business Bay → Secondary Premium (price efficient)
* JVC → Mid-market (high volume, affordability-driven)

---

### 3️⃣ Investment Risk–Return Positioning

* Risk → Rent Std Deviation
* Return → Rent per Sqft
* Liquidity → Total Listings

📌 **Insights:**

* Premium areas show high returns but varying risk
* Luxury zones exhibit extreme volatility
* Mid-market areas provide stable and liquid opportunities

---

## 📌 Key Analytical Concepts

* Skewness (Mean vs Median)
* Volatility (Standard Deviation)
* Liquidity (Listing Volume)
* Price Efficiency (Rent per Sqft)

---

## 🛠 Tools Used

* Power BI
* DAX
* Data Cleaning & Transformation

---

## 📷 Dashboard Preview

(Screenshots will be added)

---

## 🚀 Conclusion

The Dubai rental market is segmented into:

* Luxury segment (high risk, high price dispersion)
* Premium core (efficient and stable)
* Mid-market (high liquidity, moderate pricing)

This project demonstrates how data analytics can guide real estate investment decisions.

---

## 👤 Author

Supriya Rajendran
