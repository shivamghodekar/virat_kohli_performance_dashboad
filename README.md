# 📊 Virat Kohli ODI & T20 Performance Index Dashboard

This repository contains an **interactive Power BI dashboard** that analyzes **Virat Kohli’s ODI & T20 performance**.  
The data is extracted from **PostgreSQL**, processed using **SQL queries**, and visualized in **Power BI**.

---

## 🔹 Features
- **Total Runs** → Displays overall runs scored (aggregated).  
- **Runs by Ground** → Highlights performance across stadiums (Wankhede, Visakhapatnam, Wellington, etc.).  
- **Maximum Runs vs Opponent Team** → Top individual scores against South Africa, Sri Lanka, and England.  
- **Max Individual Score** → Highest score recorded in a single innings.  
- **Average Runs** → Career batting average calculation.  
- **Year, Quarter & Month Filters** → Time-based performance analysis.  
- **Interactive Slicers** → Dynamic filtering for deeper insights.  

---

## 🛠️ Tech Stack
- **Database**: PostgreSQL  
- **Data Processing**: SQL  
- **Visualization**: Power BI  
- **Data Source**: Historical ODI & T20 match records of Virat Kohli  

---

## 🚀 Insights
- Virat Kohli’s **highest ODI/T20 runs (254)** came against **South Africa**.  
- Strongest performances recorded at **Wankhede** (931 runs) and **Visakhapatnam** (879 runs).  
- Maintains a career **average of 45.95** runs.  

---

## 💡 Business Problems & Solutions
This dashboard answers key cricket performance questions using **data analytics**:

1. **Top 5 Ground Performances in 2021**  
   - Analyzed stadium-wise performance to identify where Virat scored the most runs in 2021.  
   - Result: Highlighted top 5 grounds for strategic insights on favorable venues.  

2. **Monthly & Quarterly Performance in 2018**  
   - Compared runs scored across months and quarters of 2018.  
   - Result: Identified peak form periods where Virat consistently performed above average.  

3. **Top 5 Opponent Teams in 2021**  
   - Evaluated batting records against all opposition teams in 2021.  
   - Result: Showed which teams Virat dominated most with high batting scores.  

4. **Matches Played for India in 2017, 2018, 2019**  
   - Counted matches year-wise using PostgreSQL queries.  
   - Result: Clear year-wise participation trend for workload and performance analysis.  

---

## 📂 Project Workflow
1. **Extract Data**: Raw data loaded into PostgreSQL.  
2. **SQL Queries**: Cleaned, aggregated, and structured data.  
3. **Load into Power BI**: Imported PostgreSQL dataset.  
4. **Visualization**: Built dashboard with KPIs, charts, and filters.  

---

## 📥 Setup Instructions
### Prerequisites
- Install **PostgreSQL** (v13+ recommended).  
- Install **Power BI Desktop**.  
- Clone this repository:  
  ```bash
  git clone https://github.com/your-username/virat-kohli-dashboard.git
  cd virat-kohli-dashboard
