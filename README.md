# 🏥 Healthcare Dashboard: Billing & Patient Insights

---

## 🧠 Overview
This Power BI dashboard analyses **healthcare billing and patient data** across multiple hospitals, doctors, and medical conditions.  
It uncovers **billing patterns, hospital efficiency, and cost trends** to help healthcare managers optimise operations and improve patient care.

---

## 🚀 Project Objective
To create a **comprehensive billing and patient insight dashboard** that tracks revenue drivers, stay durations, and cost efficiency in healthcare institutions.

---

## 📊 Dataset
The dataset spans **2019–2024** and includes:  
`Patient ID, Age, Gender, Medical Condition, Hospital, Doctor, Admission Date, Discharge Date, Consultation Charges, Bed Charges, Total Billing`.

Additional sheets contain:
- Doctor Consultation Charges  
- Hospital Bed Charges  
- Medical Condition Costs (e.g., Cancer ₹80,000, Obesity ₹50,000)

---

## 🧹 Data Cleaning & Preparation
Key steps included:
1. **Data Integration:** Used `VLOOKUP` and `INDEX-MATCH` to merge multi-sheet data (doctors, beds, and medical conditions).  
2. **Stay Duration Calculation:** Derived hospital stay length from admission and discharge dates.  
3. **Cost Mapping:** Linked medical conditions (e.g., Asthma, Cancer, Obesity) to treatment costs using conditional logic.  
4. **Inflation Adjustment:** Adjusted doctor and bed charges annually to reflect realistic cost increases.

---

## 📈 Dashboard Insights
- **Total Patients:** 10,000  
- **Total Revenue:** ₹2.53 B  
- **Average Revenue per Patient:** ₹253 K  
- **Average Stay Duration:** 16 days  

**Doctor Analysis:**  
- Michael Fisher leads with ₹748 K total and ₹187 K average billing.  

**Hospital Analysis:**  
- Johnson PLC tops overall billing (₹3.3 M).  
- Johnson Inc. has the highest bed charge (₹132 K).  

**Medical Condition Trends:**  
- Cancer → 20% of total revenue  
- Obesity → 16.33% of total patients  
- Total billing grew from ₹274 M (2019) → ₹567 M (2023)  
- Average bed charges rose from ₹8.1 K (2020) → ₹14.1 K (2024)

**Revenue vs. Stay:**  
Longer hospital stays correlate with higher billing—Cancer patients (15.8 days) generate ₹450 K+ per case.

---

## 💡 Key Takeaways
- **Johnson PLC’s** high billing indicates strong operational efficiency—study further.  
- **Cancer treatment** drives revenue—invest in specialised care.  
- **Bed charge inflation** (₹14.1 K in 2024) suggests a need for resource optimisation.  
- **Obesity cases** have long stays (15.19 days)—optimise treatment to reduce costs.  

---

## 🩺 Recommendations for Hospitals
1. **Streamline Stay Duration:**  
   Shorten high-frequency condition stays (e.g., Obesity) through improved protocols to reduce operational cost.  

2. **Expand High-Revenue Services:**  
   Invest in Cancer care units (20% revenue share) to enhance profitability.  

3. **Optimise Bed Charge Costs:**  
   Address rising charges via supplier negotiations and better resource allocation.  

4. **Leverage Top Doctor Practices:**  
   Train others based on Michael Fisher’s efficiency model (₹748 K billing) to raise hospital-wide revenue.  

---

## 🛠️ Tools Used
- **Power BI:** Dashboard creation & data visualisation  
- **Microsoft Excel:** Data cleaning & integration  
- **Power Query:** Data transformation and aggregation  

---

## 📚 Learnings
This project improved my ability to:
- Integrate multiple sheets with `VLOOKUP` / `INDEX-MATCH`  
- Compute time-based KPIs (e.g., stay duration)  
- Create healthcare-specific dashboards highlighting operational and financial efficiency  

A special thanks to **Rajinder Chitoria** and **Mani Bhushan** for their guidance throughout the project.  

---

## 📸 Dashboard Preview

![Healthcare Dashboard](Top 7.png)

---
