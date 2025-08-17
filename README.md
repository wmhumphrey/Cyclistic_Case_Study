# 🚲 Cyclistic Bike Share Case Study  

## 📌 Project Overview  
This project analyzes the **Cyclistic bike share dataset** to understand the differences between **casual riders** and **annual members**. The goal is to provide insights that can help design strategies to **convert casual users into annual members**.  

The project was completed as part of my **Google Data Analytics Capstone** and extended with R and Tableau for advanced analysis and visualization.  

---

## 🛠 Tools & Technologies  
- **R / RStudio** → Data cleaning, transformation, and feature engineering  
- **R Markdown** → Reproducible analysis documentation  
- **Tableau** → Interactive dashboards and visual storytelling  
- **GitHub** → Version control and portfolio presentation  

---

## 📂 Project Structure  
```
Cyclistic-Bike-Share-Analysis/
│
├── data/                  # Processed summary CSVs (non-sensitive only)
├── R/                     # R scripts and R Markdown files
│   └── data_prep.Rmd
├── tableau/               # Tableau workbook (.twbx) or exports
│   └── CyclisticDashboard.twbx
├── images/                # Screenshots of Tableau dashboards
├── README.md              # Project overview (this file)
└── LICENSE
```

---

## 🔑 Key Steps  

### 1. Data Preparation (R)  
- Combined **Q1 2019–2020 quarterly data**  
- Cleaned and standardized column names (`ride_id`, `started_at`, `ended_at`, etc.)  
- Calculated new fields:  
  - `ride_length` = ride duration  
  - `day_of_week` = weekday/weekend grouping  
  - `month`, `year` for trend analysis  
- Exported summary files (CSV) for Tableau  

### 2. Visualization (Tableau)  
Dashboards created in Tableau to highlight usage patterns:  
- **Ride Duration**: Members vs Casual riders (average & distribution)  
- **Usage by Time of Day**: Hourly trends to show peak riding hours  
- **Day of Week Trends**: Compare weekend vs weekday behaviors  
- **Station Hotspots**: Top 10 start and end stations visualized on a map  
- **Optional**: Sankey diagram showing start → end station flows  

### 3. Insights  
- **Casual riders** tend to ride longer but mostly on **weekends**.  
- **Members** ride more frequently, especially during **commute hours (7–9 AM, 5–7 PM)**.  
- Certain **stations are hotspots** for casual riders (tourist-heavy locations).  
- Members prefer stations closer to **business districts** and residential areas.  

---

## 📊 Tableau Dashboard  
👉 [View the Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/yourname/viz/CyclisticAnalysis/Dashboard1)  

*(If you’re viewing this on GitHub, click the link above for the interactive version. Screenshots are included below for quick reference.)*  

---

## 📷 Sample Visuals  
![Dashboard Preview](./images/dashboard_preview.png)  

---

## 🚀 How to Reproduce  
1. Clone this repo  
   ```bash
   git clone https://github.com/yourusername/Cyclistic-Bike-Share-Analysis.git
   ```
2. Open `R/data_prep.Rmd` in RStudio and knit to generate summary CSVs  
3. Open `tableau/CyclisticDashboard.twbx` in Tableau Desktop  
4. Connect the CSVs and refresh data sources  

---

## 📌 Next Steps  
- Add predictive modeling (e.g., forecasting seasonal demand)  
- Optimize dashboard filters for smoother interactivity  
- Explore demographic data (if available) to enrich insights  

---

## 📬 Contact  
Created by **[Your Name]**  
- [LinkedIn](https://linkedin.com/in/yourprofile)  
- [Tableau Public](https://public.tableau.com/app/profile/yourname)  
- [GitHub](https://github.com/yourusername)  
