# Netflix vs. Sleep: What Streaming Says About Our Habits

## 📊 Project Overview
This project explores the relationship between Netflix viewing habits and sleep quality.  
Using synthetic data, it analyzes how binge-watching and late-night sessions impact average sleep duration.

---

## 🔑 Business Question
**Does binge-watching late at night significantly reduce sleep hours compared to other viewing behaviors?**

---

## 🎯 Key Insights
1. **Late-night sessions** account for ~37% of all viewing activity.
2. **Average sleep** drops below **6 hours** when binge-watching late at night.
3. The **scatterplot** shows a clear negative relationship between episodes watched and sleep hours.
4. The **highlight table** confirms the worst segment: *Late Night + Binge* → lowest sleep (~5.9 hrs).
5. Device-hour heatmap highlights **8–11 PM** as peak binge time, especially on laptops & TVs.

---

## 🗂️ Dashboards Created
### 1. **KPI Summary Dashboard**
- Total Viewing Sessions
- % Late Night Sessions
- Avg Sleep Hours
- Avg Episodes per Session

📌 *Screenshot Placeholder:*  
`![KPI Dashboard](assets/kpi_dashboard.png)`

---

### 2. **Scatterplot: Episodes vs Sleep**
- X-axis: Episodes Watched  
- Y-axis: Avg Sleep Hours  
- Color: Late Night Flag  
- Tooltip storytelling: “User on Laptop watched 5 episodes, slept 4.5 hrs, session = Late Night.”

📌 *Screenshot Placeholder:*  
`![Scatterplot](assets/scatterplot.png)`

---

### 3. **The Sleep Cost of Binge-Watching (Highlight Table)**
- Rows: Binge vs Non-Binge  
- Columns: Late Night vs Not Late  
- Cells: Avg Sleep Hours (colored)  

📌 *Screenshot Placeholder:*  
`![Highlight Table](assets/highlight_table.png)`

---

### 4. **Device × Hour Heatmap**
- X-axis: Viewing Hour (0–23)  
- Y-axis: Device Type  
- Color: # of Sessions  
- Reveals peak binge hours and dominant devices.

📌 *Screenshot Placeholder:*  
`![Heatmap](assets/heatmap.png)`

---

## 🛠️ Tools Used
- Tableau (visualization, storytelling)
- Python & Pandas (data preparation, synthetic dataset)
- GitHub (portfolio hosting)

---

## 🚀 How to Use
1. Clone/download this repo.  
2. Open the Tableau workbook (`netflix_sleep_dashboard.twbx`).  
3. View dashboards in Tableau Public or Desktop.  

---

## 📌 Storytelling Takeaway
Late-night binge-watchers are the **worst-affected group**, sleeping nearly an hour less than other viewers.  
This highlights the trade-off between entertainment and well-being — a powerful example of how data can explain everyday behaviors.
