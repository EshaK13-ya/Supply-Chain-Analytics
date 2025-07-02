# CASE STUDY: Inventory and Fulfillment Performance Analysis – A to Z Supplies

[🔗 View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/esha.khot/viz/SupplyChainAnalytics_17483328285100/ShipmentDashboard)

---

## 🛠️ Technologies Used

- **Tableau**: For data visualization and interactive dashboards
- **Excel / CSV**: Source data preparation

---

## 1. Executive Summary

A to Z Supplies processed over **31,000 orders**, with an **average delay of 0.5 days**. Alarmingly, **61% of these orders experienced delays**, revealing systemic inefficiencies in the supply chain. The root cause analysis highlights:

- **Mismatched supply and demand** across departments.  
- **Significant volatility in stock levels**, with both chronic oversupply and undersupply.  
- **No direct correlation** between high inventory and faster fulfillment, indicating deeper inefficiencies in warehouse processes and forecasting models.

By addressing these foundational issues, A to Z Supplies can improve fulfillment speed, optimize stock investments, and enhance overall customer experience.

---

## 2. Shipment Performance Overview

### 📊 Key Metrics
- **Total Orders**: 31,000+
- **Delayed Orders**: 61%
- **Avg. Shipment Delay**: 0.5 days


### ⏳ Trends Over Time
<img width="468" alt="Screenshot 2025-06-03 at 2 54 27 AM" src="https://github.com/user-attachments/assets/67bb9cd0-9f30-4a28-bb9d-4440d544154d" />

- Orders were stable through 2016–2017.
- A **sharp decline in order volume** and **increase in fulfillment delays** began in 2018.


### 📉 Delay Patterns
<img width="473" alt="Screenshot 2025-06-03 at 2 41 43 AM" src="https://github.com/user-attachments/assets/33e5487e-09a0-4706-8cff-bb6bb89da712" />

- The “Delay Across Months” chart shows a **consistent decrease in delay %** until mid-2017.
- This was followed by a **renewed spike in 2018**, coinciding with operational disruptions.
- The “% Delays Per Month” chart reveals increasing segments of **yellow and red zones**, signifying rising frequency of delayed shipments.

💡 **Insight**: While early efforts improved delivery timelines, late 2017–2018 shows regression, suggesting **supply chain instability**, **supplier delays**, or **forecasting failures**.

---

## 3. Delay Attribution & Product-Level Bottlenecks

<img width="562" alt="Screenshot 2025-06-03 at 2 55 18 AM" src="https://github.com/user-attachments/assets/4acc92fc-e226-43d8-af91-2fbae24aa3e6" />

### 📦 Top Delayed Categories
- **Toys** – 58% delayed
- **Fitness Accessories** – 53% delayed
- **Men’s Clothing** – 50% delayed

💡 **Insight**: Product-level delays cluster around **seasonal or demand-sensitive SKUs**, such as children’s gear and apparel. This reflects **inadequate forecasting**, particularly during peak periods, and **reactive stock replenishment**.

---

## 4. Supply & Demand Alignment

<img width="470" alt="Screenshot 2025-06-03 at 2 55 45 AM" src="https://github.com/user-attachments/assets/2bc58658-ea1a-41dd-a2e4-c4c874872fa8" />

From the “Supply vs Demand” chart (bubble plot):

- 🟢 **Green bubbles**: well-aligned products  
- 🔴 **Red bubbles**: major misalignment

### 🟢 Surplus Inventory
Some categories have large overstocks but low fulfillment demand, tying up working capital.

### 🔴 Chronic Undersupply
Key demand drivers are understocked (e.g., Pelican Sunstream, O'Brien Neoprene Vest), consistently failing to meet sales opportunity.

💡 **Insight**: Poor synchronization between demand forecasting and procurement planning is leading to **lost sales**, **customer churn**, and **increased storage costs**.

---

## 5. Stock Volatility & Fulfillment Times

From the **Stock Levels** chart:

- Extreme variance (ranging from **−88 to +65**) signals **volatile supply chains** and reactive inventory strategies.  
- Inconsistent inventory behavior shows **disconnect between stocking and actual sales velocity**.

### 📈 Avg. Fulfillment Days per Department

| Department               | Avg. Stock | Fulfillment Time |
|--------------------------|------------|------------------|
| Toys                    | +60.0      | 3.7 days         |
| Indoor/Outdoor Games    | –45.6      | 5.5 days         |
| Fishing                 | –20.7      | 4.9 days         |
| Video Games             | –7.6       | 8.8 days         |
| Water Sports            | –27.8      | 2.1 days         |
| Camping & Hiking        | +2.6       | 6.9 days         |
| DVDs                    | +3.88      | 6.6 days         |
| Music                   | +2.67      | 9.3 days         |

💡 **Insight**: High inventory (e.g., Toys) does **not guarantee faster fulfillment**, and some **severely understocked departments** (like Water Sports) still fulfill quickly, indicating **inefficiencies in warehouse picking**, **location**, or **SKU accessibility**.

---

## 6. Product-Level Inventory Mismanagement
<img width="1006" alt="Screenshot 2025-06-03 at 2 57 51 AM" src="https://github.com/user-attachments/assets/7669fa2d-ec20-4419-8b5d-85b88a848aee" />

From “Inventory Levels per Product”:

### 📉 Major Shortfalls
- **Pelican Sunstream**: −329 units  
- **O'Brien Neoprene Vest**: −547 units  

### 📈 Overstocked SKUs
- **Diamondback Women’s**: +60 units (with sluggish movement)

💡 **Insight**: SKU-level inventory planning is misaligned. Some products with high demand are perpetually understocked, while low-movement SKUs are excessively stocked, causing **working capital drain** and **order fulfillment failures**.

---

## 7. Recommendations

🎯 **Actionable Strategic Moves**:


- **Optimize demand forecasting**:  
      Use a blended model of **seasonality, historical delays, and trend analysis** to anticipate peaks and avoid reactive stocking.  

    

-  **Segment stock strategies by department**:  
      High-turnover products (e.g., Toys, Fitness) need **automated replenishment**.  
      Low-frequency departments should have **buffer-based planning** to minimize overstock.  

-  **Conduct SKU-level audits**:  
    Flag items that are consistently over- or under-stocked.  
    Reallocate stock across warehouses as needed.  

-  **Streamline warehouse operations**:  
    Digitize picking routes.  
    Prioritize **high-stock, high-delay SKUs** for faster dispatching.  
---

## 8. Final Thoughts

This case study reveals that **operational inefficiencies are deeply interconnected**, from demand forecasting failures to inventory planning breakdowns, and from warehouse process delays to supplier unreliability.

By aligning **forecasting, procurement, inventory, and fulfillment workflows**, A to Z Supplies can unlock:

-  Better **service-level reliability**  
-  Reduced **operational waste**  
-  Higher **customer satisfaction**

---

📈 **Result**: A strategic transformation in supply chain coordination and stock strategy will help A to Z Supplies scale sustainably and competitively in future demand cycles.

---

## Shipment Dashboard



<img width="1440" alt="Screenshot 2025-06-03 at 1 45 58 AM" src="https://github.com/user-attachments/assets/c3bcfd7a-5e72-4438-8b5a-b891aa3fb18f" />



## Inventory Dashboard

<img width="1440" alt="Screenshot 2025-06-03 at 1 49 03 AM" src="https://github.com/user-attachments/assets/36680965-ce81-48f8-b471-859921d4d46a" />



