# 💼 Deloitte Data Analytics Simulation – Daikibo Case Study

This repository showcases my completed tasks from the **Deloitte Data Analytics Simulation** on [Forage](https://www.theforage.com/). The case study focuses on a global manufacturing company, **Daikibo**, with two main challenges: ensuring fair employee compensation and monitoring machine health across international factories.

I used **Excel** and **Tableau** to clean, analyze, and visualize the data — drawing clear business insights and making recommendations, just like in a real analyst role. 📊🔍

---

## 📊 Task 1: Employee Equality Score Classification (Excel)

### 🔧 What I Did:
- Analyzed employee compensation data from Daikibo's factories in Tokyo, Osaka, Berlin, and Shenzhen.
- Used Excel to classify **equality scores** into 3 categories:
  - ✅ **Fair**: -10 to +10
  - ⚠️ **Unfair**: -11 to -20 or 11 to 20
  - ❌ **Highly Discriminative**: Less than -20 or greater than 20
- Applied an Excel formula to auto-classify each row, reducing error and ensuring consistency.

### 📌 Insights I Gained:
- Several job roles in **Berlin** and **Shenzhen** had more highly discriminative scores — indicating potential regional policy misalignment.
- **Managerial roles** showed more fairness than **manual labor roles**, highlighting a possible systemic bias in lower-tier compensation.

### 📁 Files:
- [Equality Table - Original.xlsx](equality-score-analysis/Equality%20Table%20-%20Original.xlsx)
- [Equality Table - Cleaned.xlsx](equality-score-analysis/Equality%20Table%20-%20Cleaned.xlsx)


---

## 🏭 Task 2: Machine Downtime Analysis (Tableau)

### 🔧 What I Did:
- Analyzed JSON telemetry data from Daikibo’s machines across 4 factories.
- Created a calculated field in Tableau to track **unhealthy machine status** (10 minutes of downtime per flag).
- Built an **interactive dashboard** showing:
  - Factory with the highest downtime
  - Most problematic machine types
  - Filtering across factories for deeper drilldown

### 📌 Insights I Gained:
- **Daikibo Factory Meiyo (Tokyo)** had the **highest total downtime** over the month.
- The **Type B and Type G machines** were consistently underperforming in that factory.
- This suggests those specific machines may need preventive maintenance or vendor review.

### 📁 Files:
- [Dashboard.png](machine-downtime-analysis/Dashboard.png)
- [Down Time per Factory.png](machine-downtime-analysis/Down%20Time%20per%20Factory.png)
- [Down Time per Device Type.png](machine-downtime-analysis/Down%20Time%20per%20Device%20Type.png)


---

## 🧠 What This Project Taught Me:
- 📌 How to structure real-world business problems into analytical workflows
- 📈 Building clean and meaningful data visualizations using Tableau
- 🧹 Applying consistent logic in Excel for large datasets
- 🎯 Identifying trends and root causes by combining logic + visualization
- ✍️ Communicating insights clearly for business stakeholders

---

## 📜 Certificate
🔗 [View my Deloitte Forage Completion Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/9PBTqmSxAf6zZTseP/io9DzWKe3PTsiS6GG_9PBTqmSxAf6zZTseP_wTgCduzYJrNm8dxdY_1748020437175_completion_certificate.pdf)

---

### 📫 Let's Connect!
If you liked this project, feel free to star ⭐ the repo or connect with me!

Thanks for visiting! This project is part of my journey to becoming a well-rounded data analyst with strong technical and business communication skills. 💪📊
