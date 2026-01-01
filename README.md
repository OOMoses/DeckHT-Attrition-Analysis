# DeckHT Attrition Analysis – A Business Intelligence Case Study

## 📑 Table of Contents

- [Executive Summary](#-executive-summary)
- [Dashboard Visuals](#-dashboard-visuals)
- [Context & Problem Statement](#-context--problem-statement)
- [Business Goals & Stakeholders](#-business-goals--stakeholders)
- [Tools & Skills Used](#-tools--skills-used)
- [Data Cleaning & Transformation (Power Query)](#-data-cleaning--transformation-power-query)
- [Exploratory & Statistical Analysis](#-exploratory--statistical-analysis)
- [Key Insights – What the Data Revealed](#-key-insights--what-the-data-revealed)
- [Business Value Created](#-business-value-created)
- [Recommendations](#-recommendations)
- [Conclusion](#-conclusion)

---

## 🚀 Executive Summary
DeckHT is losing high-value talent — particularly women, professionals aged **26–35**, and employees in **Specialist and Analyst roles**. Attrition in these groups is **significantly higher than the company average**, and **57% of leavers reported poor or below-average job satisfaction**.

This pattern signals **systemic retention risks** tied to:
- Pay disparity (men earn **$4,000 more on average**)
- Career progression concerns
- Workload & role-design challenges in specialist roles
- Engagement gaps

If left unaddressed, attrition will continue to:
✔ Increase hiring & onboarding costs  
✔ Reduce productivity & institutional knowledge  
✔ Disrupt culture & morale  

This project transforms raw HR data into **clear risk signals and actionable strategies**, helping leadership proactively protect capability, improve engagement, and stabilize the workforce.

---

## 📊 Dashboard Visuals
![DeckHT Attrition Dashboard](https://github.com/user-attachments/assets/5b41dc89-3a09-46dd-a5f4-31f2c0670cc6)

🔗 **Interactive Dashboard**  
https://1drv.ms/x/c/3921519a1e88d755/EXi49vGOC_VFvSy0Ve5W4kgBz14_RVelpD_h3jxdRsdTRA?e=Xc6T88

The dashboard enables leadership to:

✔ Explore attrition trends  
✔ Drill into high-risk demographics  
✔ Monitor satisfaction & role exposure  
✔ Make informed retention decisions  

---

## 🎯 Context & Problem Statement
DeckHT leadership observed a rise in voluntary employee departures.  
While some turnover is expected, **increasing attrition across critical roles and demographics raised concern** around:

- Talent continuity  
- Capability risk  
- Hiring & training cost  
- Employee morale  

The HR team needed **evidence-driven clarity** — not assumptions — on:

> **Who is leaving? Why are they leaving? And where is the risk concentrated?**

This project answers those questions.

---

## 👥 Business Goals & Stakeholders

### Primary Stakeholders
- Chief HR Officer  
- HR Business Partners  
- Executive Leadership  
- Finance (workforce planning)

### Business Objectives
✔ Identify at-risk employee segments  
✔ Understand drivers influencing attrition  
✔ Quantify workforce exposure  
✔ Support data-driven retention strategy  
✔ Provide HR a decision-ready dashboard  

---

## 🛠 Tools & Skills Used
- **Excel** — KPI modeling & dashboard design  
- **Power Query** — ETL & data preparation  
- **Pivot Tables** — aggregation & segmentation  
- **Exploratory & Descriptive Analytics**  
- **Data Storytelling & BI Strategy**

---

## 🔄 Data Cleaning & Transformation (Power Query)
**Goal:** Convert raw HR records into an accurate, analysis-ready dataset.

I followed a structured ETL workflow:

1️⃣ **Imported & Profiled the Data**  
   *Purpose:* Understand data structure, missing values, and inconsistencies.

2️⃣ **Removed Irrelevant Columns & Invalid Rows**  
   *Purpose:* Reduce noise and improve analytical reliability.

3️⃣ **Standardized & Split Columns Where Needed**  
   *Purpose:* Enable flexible segmentation (e.g., role, department, demographics).

4️⃣ **Renamed & Formatted Headers**  
   *Purpose:* Improve readability and maintain consistent schema.

5️⃣ **Corrected Data Types (text, numeric, date)**  
   *Purpose:* Prevent aggregation & calculation errors.

6️⃣ **Created Derived Fields & KPI Flags**  
   *Purpose:* Compute attrition metrics & support visualization logic.

Result:  
A **clean, structured dataset ready for HR analytics.**

---

## 🔍 Exploratory & Statistical Analysis
I analyzed attrition across:

- Gender  
- Age groups  
- Department  
- Job role  
- Compensation  
- Job satisfaction  
- Workforce composition  

The goal was not just to summarize —  
but to **understand patterns and risk concentration.**

---

## 📊 Key Insights – What the Data Revealed

### 1️⃣ Gender-Based Attrition Risk
Although the workforce is mostly male:

| Group | Attrition Rate |
|------|----------------|
| **Female** | **34%** |
| Male | 27% |

📌 **Women are leaving at meaningfully higher rates**

This signals:
- engagement challenges
- pay fairness concerns
- potential culture impact

---

### 2️⃣ Pay Inequality — a Predictable Risk Driver
- **Male employees earn ≈ $4,000 more on average**
- Average company salary: **$62,000**

📌 Pay equity risk exists  
📌 Likely influencing engagement & retention

---

### 3️⃣ The Most Vulnerable Age Groups
Attrition peaks among:

| Age Group | Attrition |
|----------|-----------|
| **31–35** | **38.9%** |
| **26–30** | **27.8%** |

These employees are typically:
- Career-advancing
- Highly mobile
- Expensive to replace

📌 **Nearly two-thirds of departures come from these two age brackets**

---

### 4️⃣ Job Roles Under Pressure
Highest attrition:

| Role | Attrition Rate |
|------|----------------|
| **Specialists** | **41%** |
| **Analysts** | **35%** |

These are **high-skill, high-impact roles.**

Meanwhile:
- Accountants show **low attrition (12%)**
- But **below-average satisfaction**

📌 Retention risk exists **before** resignations occur  
📌 Signals future churn if unaddressed

---

### 5️⃣ Departmental Stability — and Fragility
High-turnover departments include:

- HR  
- Sales  
- Marketing  
- Finance  

Meanwhile:

| Department | Attrition |
|-----------|-----------|
| **Engineering** | **6.8%** |
| **IT** | **7.7%** |

📌 Specialist knowledge loss is concentrated  
📌 Technical functions are relatively stable

---

### 6️⃣ Satisfaction Predicts Attrition
Among exiting staff:

- **57% report poor/below-average satisfaction**

Among current staff:

- **29% dissatisfied**
- **50% neutral**

📌 Neutral engagement is a **warning zone**
📌 Quiet dissatisfaction precedes churn

---

## 💼 Business Value Created
This project helps DeckHT:

✅ Move from **reactive hiring** → to **proactive retention**  
✅ Protect capability in critical roles  
✅ Reduce recruitment & onboarding cost  
✅ Strengthen employee experience & engagement  
✅ Support data-driven HR strategy  

---

## 💡 Recommendations

### Highest-Impact Actions
1️⃣ **Close the gender pay gap & improve transparency**  
2️⃣ **Design career-path programs for ages 26–35**  
3️⃣ **Stabilize Specialist & Analyst roles**
   - workload review  
   - recognition systems  
   - skill pathways  

4️⃣ **Engagement listening — before exit interviews**  
5️⃣ **Early-warning HR analytics monitoring**  

---

## 🏁 Conclusion
Attrition at DeckHT is **predictable — and preventable.**

By combining compensation analysis, demographic segmentation, and satisfaction metrics, this project provides **clear visibility into who is at risk and why.**

With targeted intervention, DeckHT can:
✔ retain key talent  
✔ reduce cost leakage  
✔ strengthen workforce morale  
✔ build a healthier, more equitable culture  

---

## 👤 Author
**Oluwatobi Moses Ojo**  
Data & BI Analyst  
*Turning data into business clarity.*
