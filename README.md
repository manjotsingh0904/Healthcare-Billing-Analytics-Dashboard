# 📞 Call Centre Dashboard: 67 Seconds to Answer, 317 Calls Missed  
*Uncovering operational insights through Power BI storytelling*

---

## 🧠 Overview
This Power BI project explores a **call centre dataset** to reveal how agent efficiency, customer satisfaction, and call resolution vary across products and hours.  
It highlights **bottlenecks, workload imbalances, and service gaps**, enabling actionable insights for better performance management.

---

## 🎯 Objective
To build a **real-time operations dashboard** that tracks:
- Call handling time  
- Resolution rates  
- Customer satisfaction  
- Agent efficiency  
- Missed call trends  

---

## 🗂️ Dataset
A call centre dataset containing:  
`Date, Agent, Product, Call Time, Answer Time, Talk Time, Resolution Status, Customer Rating`

Covers:
- 8 agents  
- 5 product categories (TV, AC, Toaster, Fridge, Washing Machine)  
- Call data over multiple days and hours  

---

## 🧹 Data Preparation
Key cleaning and transformation steps:
1. Converted timestamps into **hourly buckets** for time-based analysis.  
2. Created calculated measures:
   - Average Answer Time  
   - Resolution Rate (%)  
   - Missed Calls Count  
   - Satisfaction Score (avg.)  
3. Grouped calls by **product, agent, and time of day** for drill-down visuals.  
4. Filtered invalid or duplicate entries (same call logged twice).  

---

## 📊 Dashboard Insights

### 🧠 Operational Intelligence
- ⏰ **Peak load:** 11 AM (236 calls), 5 PM (218), 9 AM (216)  
- ⏱️ **Avg. answer time:** 67.2 sec, clustered between 30–90 sec  
- ✅ **Resolution rate:** 90% overall (TV 91%, AC 92%)  

### 💼 Agent Analytics
- 🌟 **Martha:** Top satisfaction performer (3.7/5 avg.)  
- 🧊 **Stewart:** Most efficient (avg. talk time 228 sec)  
- 📞 **Dan:** Most calls (190) but longest talk time (237 sec)  

### 😀 Customer Experience
- 😊 **Avg. satisfaction:** 3.45/5  
- 🧩 **Fridge:** Highest satisfaction (3.52/5)  
- 📉 **32%** of resolved calls rated just 3/5 — clear improvement scope  
- ⚡ **Toaster:** Fastest responses (65.79 sec)  
- ❄️ **AC:** Slowest (68.76 sec)  

### 🔍 Product Analysis
- 📺 **TV:** Most calls (382), longest talk time (193.4 sec) — complex issue handling  
- ❌ **AC:** Most unresolved calls — rushed handling suspected  

### 🚫 Unanswered Calls
- 📉 **317 missed calls** overall  
- ⏰ **Peak misses:** 11 AM (42), 5 PM  
- ☎️ **Answer rate:** 82% — strong resolution, weak responsiveness  

---

## 🔎 Deep Insights
- ⚖️ **Agent Imbalance:** Dan overburdened; Martha underutilised.  
- 💬 **TV category:** High complexity → needs better scripts.  
- ❗ **AC support:** Long waits, poor resolution → requires training.  
- 🧩 **Answer vs. Resolution gap:** Excellent recovery but poor initial handling.  

---

## ✅ Actionable Recommendations
1. 🕙 Reinforce **staffing at 11 AM & 5 PM** (peak load hours).  
2. 📤 **Rebalance workloads** — give more to Martha, ease Dan’s load.  
3. 🛠️ **Train agents** for TV & AC — customised scripts improve resolution.  
4. 🧠 **Audit AC quick drops** — identify process inefficiencies.  
5. 📲 Use **resolution strength** to follow up on missed calls.  

---

## 🧰 Tools Used
- **Power BI:** Data modelling & dashboard creation  
- **Power Query:** Data cleaning & transformation  
- **Excel:** Pre-processing and exploratory analysis  

---

## 📚 Learnings
This project strengthened my ability to:
- Combine visual storytelling with KPI-based dashboards  
- Build interactive slicers & visuals in Power BI  
- Translate raw data into operational narratives for business use  

## 📸 Dashboard Preview
*(Upload your Power BI dashboard screenshots here once added)*  

![Call Centre Dashboard](images/callcentre-dashboard.png)
