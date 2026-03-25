# 🛒 E-Commerce Performance Command Center
### *A Strategic Narrative through Dynamic Data Modeling*

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/Advanced_DAX-005A9C?style=for-the-badge)

## 📖 The Story
In a high-volume e-commerce environment, a static report is a missed opportunity. Decision-makers don't just need to know "what" happened; they need to pinpoint **outliers**—the champions to reward and the red flags to fix.

This project transforms standard transactional data into a **Dynamic Narrative**. Using a custom-built "N-Factor" engine, this dashboard allows a user to switch from a high-level bird's-eye view to a surgical "Custom" analysis in a single click.

---

## 🚀 Navigation & Experience
The journey begins at the **Interactive Home Page**, designed to minimize cognitive load and provide a "Web-App" feel.

![Home Page](Dashboard_screenshots/home_page.png)

> **Insight:** Users aren't forced into a maze of tabs. They choose their strategic path—**Sales Analysis** or **Distribution**—immediately upon entry.

---

## 📊 Dashboard 1: Product & Marketing Performance
*The Pulse of Revenue & ROI*

This dashboard is a dynamic engine. Using the custom sidebar, users can toggle between **Top N**, **Bottom N**, and **Custom** views. The titles and colors update instantly to reflect the data’s "mood."

### **View A: The Winners (Top N)**
*Identifying the engines of growth.*
![Top N Dashboard](Dashboard_screenshots/top_N_Dash_1.png)
* **🟢 Green Excellence:** Highlights the "Running Shoes" ($53M) and "NeoStore" as the primary revenue anchors.
* **Marketing Win:** The **"Green Week"** campaign is a massive outlier with a **520% ROI**, signaling a clear strategy for next quarter's budget allocation.

### **View B: The Red Flags (Bottom N)**
*Spotting leakage before it becomes a crisis.*
![Bottom N Dashboard](Dashboard_screenshots/bottom_N.png)
* **🔴 Critical Alert:** While total sales sit at $2.75bn, the **"Bosch Refrigerator"** and **"GadgetZone"** store are lagging significantly behind.
* **The Growth Story:** The "Sales Growth Over Time" chart reveals a sharp decline in late 2024, dropping from $371M to $60M. This visual prompt forces an immediate investigation into Q4 seasonality or supply chain disruptions.

### **View C: Custom Deep-Dive**
*For the surgical precision required by Category Managers.*
![Custom Dashboard](Dashboard_screenshots/custom_dash.png)
* **On-Demand Slicers:** Using **Bookmarks**, I implemented hidden slicer panels that only appear in Custom Mode. This keeps the interface clean while offering 100% granular control over specific product comparisons.

---

## 👥 Dashboard 2: Customer & Salesperson Analysis
*The Human Capital & Market Penetration*

![Customer & Sales Analysis](Dashboard_screenshots/dash_2.png)

* **Regional Dominance:** The **Southwest** leads in volume (22,163 customers), but the stacked bars reveal the "quality" of that volume, showing a healthy mix of **Premium** and **Loyal** shoppers.
* **Retention Risk:** The red segments represent **"Churn Risk."** By visualizing this by region, the marketing team can deploy targeted re-engagement offers to the West Coast specifically.
* **Star Performers:** Visualizing **Michael Davis** and **Jason Miller** as top sellers allows management to benchmark their performance against the "Category-wise Brand Coverage" table.

---

## ⚙️ Technical Mastery (The "How")
To deliver this level of interactivity without cluttering the report, I implemented:

* **Dynamic DAX Engines:** Created disconnected tables for `ViewMode` and `TopN_Selector` to drive visual filtering.
* **Smart Titles:** Used DAX-driven titles that change based on user slicer selection (e.g., *"Top 5 Products"* vs *"Bottom 10 Products"*).
* **Conditional Formatting Logic:** * 🟢 **Top Performers**
    * 🟡 **Intermediate Values**
    * 🔴 **Lowest Performers**
* **Optimization:** Utilized **Switch Measures** and **Bookmarks** to reduce the number of visuals per page, significantly boosting report loading speed and performance.

---

## 📽️ Full Demo
Experience the smooth transitions and interactive slicers in action:
👉 **[View the Full Dashboard Presentation](https://vimeo.com/1177020649?share=copy&fl=sv&fe=ci)**

---

### 🛠️ Tools Used
* **Power BI Desktop** (Data Modeling & UI)
* **Advanced DAX** (Dynamic Measures & Logic)
* **Power Query** (ETL & Schema Design)


- Reduces visual clutter.  
- Simplifies user interaction.  
- Improves understanding of complex datasets.  

---
