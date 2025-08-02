# 📊 Retail Store Student Purchase Analysis – Power BI Project

## 📝 Project Overview
In this project, we explored [**student survey data**](https://app.powerbi.com/reportEmbed?reportId=dbd50427-2c85-41ea-a3e6-37843a25f600&autoAuth=true&ctid=38c234ae-7725-479d-81a1-9b6d2fa56530) from various retail stores in the USA to understand **spending patterns** on different categories like 🎮 *Video games*, 🏀 *Outdoor sports*, 📚 *Books*, 🧩 *Toys*, etc.  
The dataset included **Store location** and **Store setting** to analyze trends based on geographical and environmental factors.

---

## 🎯 Objectives
1. Build **interactive Power BI reports** to visualize student spending trends.
2. Apply **conditional formatting** and **advanced filtering** for better insights.
3. Use **Row-Level Security** to restrict data access for specific users.
4. Publish and schedule automatic data refresh in **Power BI Service**.

---

## 🛠️ Features Implemented

### 1️⃣ **Tabular Visualization**
- Displayed **Total Amount of Purchase (TAP)** by `Store location` and `Store setting`.
- Applied **Conditional Formatting**:
  - 🔴 **Red** → `TAP` < 35000  
  - 🟡 **Yellow** → 35000 ≤ `TAP` < 60000  
  - 🔵 **Blue** → `TAP` ≥ 60000  

---

### 2️⃣ **Matrix Visualization**
- Showed **Outdoor sports spending** by `Age` (rows) and `Store setting` (columns).
- Applied **color formatting** to highlight spending intensity.

---

### 3️⃣ **Funnel Chart**
- Visualized **Total Amount of Purchase** by `Store setting`.
- Displayed values as **Percentage of First**.

---

### 4️⃣ **Pie Chart with Filter Context**
- Showed **TAP by Store location** for **Suburban Store setting** only.
- Used **visual-level filters** to restrict the data.

---

### 5️⃣ **Scatter Plot**
- X-axis: `Sum of Video Games`  
- Y-axis: `Sum of OutDoor Sports`   
- Legend: `Age`  

---

### 6️⃣ **Sand Dance Plot**
- Visualized **Indoor sports** and **Video games** spending across `Age groups`.

---

### 7️⃣ **Row-Level Security (RLS)**
- Created role `RuralOnly` to restrict user **Mani** to view only `Store setting = Rural`.

---

### 8️⃣ **Publishing & Scheduling**
- Published report to **Power BI Service**.
- Created **Master Dashboard** with Funnel Chart + Scatter Plot.
- Configured **Scheduled Refresh** → ⏱ **6 times every 4 hours** in a day.

---

### 9️⃣ **Q&A Feature**
- `Average age of students`
- **Donut Chart** for total purchases by `Store location`.

---

## 📂 Files in this Repository
| File Name              | Description |
|------------------------|-------------|
| `Studentdata.pbix` | Power BI report file |
| `README.md`            | Project documentation |
| `Student Survey Data.xlsx`    | Dataset used in the project |

---

## 🎨 Dashboard Preview
<p align="center">
  <img src="Screenshots/Tabular%20Chart.png" width="250"/>
  <img src="Screenshots/Matrix%20chart.png" width="250"/>
  <img src="Screenshots/Funnel%20chart.png" width="250"/>
</p>
<p align="center">
  <img src="Screenshots/Pie%20chart.png" width="250"/>
  <img src="Screenshots/Scatter%20Plot.png" width="250"/>
  <img src="Screenshots/Sand%20Dance.png" width="250"/>
</p>

---

## 📌 Insights Discovered
- **Urban** stores have the highest TAP.
- **Suburban** students spend more on **Video games** compared to **Outdoor sports**.
- **Rural** settings show significantly lower spending overall.

---

## 🖋 Author
**Harish S**  
📧 harishselvakannan@gmail.com  
💼 [LinkedIn Profile](https://www.linkedin.com/in/harishselvakannan) | 🌐 [Studentdata Online](https://app.powerbi.com/reportEmbed?reportId=dbd50427-2c85-41ea-a3e6-37843a25f600&autoAuth=true&ctid=38c234ae-7725-479d-81a1-9b6d2fa56530)

---
