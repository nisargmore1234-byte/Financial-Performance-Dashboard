# 📊 Financial Performance & Regional Intelligence Dashboard

A dynamic, interactive data visualization tool built to track enterprise-wide financial health across India—focusing on multi-year revenue trends, regional sales distribution, profit margins, volume metrics, and predictive forecasting.

---

## 2. Short Description / Purpose

The Financial Performance Dashboard is a visually engaging and analytical Power BI report designed to help executives, financial analysts, and regional heads monitor key business drivers across multiple fiscal years. The dashboard highlights major financial metrics including total revenue (**362.25bn**), profit margins (**14.59%**), sales volumes (**1.45bn liters**), and state-level YoY performance, empowering data-driven strategic planning and forecasting.

---

## 3. Tech Stack

The dashboard was built using the following tools and technologies:
• 📊 **Power BI Desktop** – Main data visualization platform used for report creation and interactive layout design.
• 📂 **Power Query** – Data transformation and cleaning layer for reshaping, merging, and preparing multi-region financial data.
• 🧠 **DAX (Data Analysis Expressions)** – Used for calculated financial measures, dynamic YoY growth calculations, upper/lower prediction bounds, and conditional logic.
• 📝 **Data Modeling** – Star-schema relationships established among tables (financial transactions, regional mapping, and calendar/fiscal year dimensions) to enable seamless cross-filtering.
• 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews and stakeholder presentations.

---

## 4. Data Source

Enterprise financial records spanning multiple fiscal years (**FY22 to FY26**), tracking transactional sales, product categories, raw material costs, discount schemes, and state-wise distribution data across India's primary regions (**East, North, South, and West**).

---

## 5. Features / Highlights

• **Business Problem**  
Large-scale enterprises operating across diverse geographic zones often struggle to aggregate multi-regional revenue streams, evaluate profit margin fluctuations, and isolate the exact drivers of variance (such as volume growth, pricing shifts, or raw material changes) in real time.

• **Goal of the Dashboard**  
To deliver an intuitive, executive-ready BI reporting tool that:  
• Centralizes multi-year financial tracking from FY22 to FY26.  
• Facilitates drill-down analysis into product categories, regions, and individual states (e.g., Andaman and Nicobar Islands, Andhra Pradesh, Arunachal Pradesh, and Assam)[cite: 1].  
• Visualizes forecasting trends with upper and lower confidence bounds[cite: 1].  
• Breaks down the exact financial levers impacting bottom-line revenue changes[cite: 1].

• **Walkthrough of Key Visuals**  
- **Global KPIs & Time Slicers (Top Left):** Interactive year selectors (`FY22` to `FY26`) and region filters alongside high-level KPI cards displaying **Total Revenue (362.25bn)**, **Profit Margin (14.59%)**, and **Total Volume (1.45bn Liters)**[cite: 1].  
- **Advanced Trend & Prediction (Top Right):** Features a Product Category drill-down bar and a **Forecast vs Actual Trend line chart** tracking performance across months with confidence boundaries[cite: 1].  
- **Regional Revenue Density (Bottom Left - Map):** A geographic choropleth map of India segmented by East, North, South, and West zones to visualize spatial revenue concentration[cite: 1].  
- **Category Profitability and Volume (Bottom Center - Treemap):** A hierarchical treemap displaying revenue contributions and volume distributions across product categories by region[cite: 1].  
- **YoY Growth by State (Bottom Right - Matrix Table):** A detailed tabular matrix breaking down Total Revenue, Profit Margin %, and Total Volume (Litres) per state alongside grand totals[cite: 1].  
- **Revenue Change Drivers (Bottom Right - Waterfall Chart):** A financial waterfall chart explaining variances from Starting Revenue to Ending Revenue through drivers like Volume Growth, Price Realization, Market Share Gains, Raw Material Price Changes, and Discounts[cite: 1].

• **Business Impact & Insights**  
**Executive Decision Making:** Leadership can instantly evaluate yearly financial health and profitability thresholds without digging through raw accounting ledgers.  
**Variance Accountability:** The waterfall breakdown exposes precisely how factors like discounting, raw material costs, and volume shifts impact the final revenue line.  
**Regional Strategy:** Geographic heatmaps and state-level matrices enable regional directors to pinpoint underperforming states and reallocate resources effectively.  
**Predictive Planning:** Forecast trend models assist inventory and supply chain teams in anticipating future volume demands (measured in liters) across seasonal cycles[cite: 1].

---

## 6. Screenshots / Demos

![Dashboard Preview](Financial%20Performance%20Dashboard.png)
