# 📊 Y.Afisha Marketing Analytics – Sprint 8 Project  

This project simulates working as a **junior marketing analyst** for Y.Afisha, an online service.  
The goal was to **optimize marketing spend** by analyzing user behavior, sales patterns, and marketing investments across channels.  

---

## 📌 Project Overview  

The analysis is structured in three key parts:  

### 1. Product Metrics  
- Measured **daily, weekly, and monthly active users (DAU, WAU, MAU)**  
- Calculated **sessions per day** and **average session length**  
- Evaluated **user retention rates** across cohorts  

### 2. Sales Metrics  
- Analyzed **conversion lag** (time from registration to first purchase)  
- Measured **order frequency per customer**  
- Calculated **average order value (AOV)**  
- Estimated **Customer Lifetime Value (LTV)** across cohorts and sources  

### 3. Marketing Metrics  
- Tracked **total and channel-level marketing spend**  
- Calculated **Customer Acquisition Cost (CAC)** by channel  
- Measured **Return on Investment (ROI)** by source and over time  
- Compared performance across **devices and acquisition sources**  

---

## 🛠️ Tools & Technologies  
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  - `pandas`, `numpy` (data processing)  
  - `matplotlib`, `seaborn` (visualizations)  
  - `datetime` (session and cohort analysis)  

---

## 📂 Datasets  

1. **Visits Log** (`visits_log_us.csv`)  
   - `Uid` — unique user ID  
   - `Device` — device used  
   - `Start Ts`, `End Ts` — session start and end timestamps  
   - `Source Id` — acquisition channel  

2. **Orders Log** (`orders_log_us.csv`)  
   - `Uid` — user ID  
   - `Buy Ts` — timestamp of purchase  
   - `Revenue` — purchase value  

3. **Marketing Costs** (`costs_us.csv`)  
   - `source_id` — ad source  
   - `dt` — date  
   - `costs` — marketing spend  

---

## 🎯 Key Learning Outcomes  
- Applied **business-focused KPIs** (DAU/WAU/MAU, AOV, LTV, CAC, ROI)  
- Practiced **cohort analysis and retention measurement**  
- Strengthened ability to connect **user behavior → revenue → marketing efficiency**  
- Gained experience in making **data-driven recommendations** for budget allocation  

---

## 🚀 Business Insights  
- Identified which marketing sources delivered **highest ROI**  
- Recommended channels where spend should be scaled down or reallocated  
- Showed how conversion lag and retention vary by cohort and device  
- Quantified the point at which **marketing investments break even**  

---

## 📊 Sample Visuals  

*(Optional: DAU trend, cohort retention heatmap, CAC vs. LTV by source, ROI curve)*  

---

✍️ **Author**: Eric Moraes  
📍 Dublin, Ireland  
🔗 [LinkedIn](https://linkedin.com/in/eric--moraes)  
