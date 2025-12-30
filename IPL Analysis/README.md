# 🏏 IPL Data Analytics Dashboard (2008–2025)

## ❓ **Business / Analytical Question**

**How can ball-by-ball IPL data be analyzed to uncover team performance, player consistency, match outcomes, and season-wise trends that support deep cricket analytics and strategic insights?**

The objective of this real-time project is to **transform raw IPL ball-by-ball data into meaningful insights** using advanced **DAX-driven analysis**, enabling fans, analysts, and decision-makers to explore **historical and current IPL performance patterns**.

---

## 📌 **Project Overview**

This is a **real-time, end-to-end IPL analytics project** built using **2008–2025 IPL ball-by-ball and match-level datasets**.  
The dashboard provides **interactive, season-wise and team-wise insights** covering batting, bowling, match results, and tournament outcomes.

The project is designed to be **highly useful for anyone working with IPL datasets**, especially those aiming to practice **industry-level Power BI and DAX skills**.

---

## 🗂️ **Dataset Description**

The analysis is based on multiple related datasets:

- 🏏 **Ball-by-Ball Data (2008–2025)**
  - Match ID
  - Over & Ball Number
  - Batter, Bowler, Non-Striker
  - Runs, Extras, Wickets, Dismissal Type

- 📋 **Match-Level Data**
  - Season
  - Match Date
  - Teams
  - Venue
  - Match Winner
  - Match Type (League / Final)

- 🏟️ **Team & Player Reference Data**
  - Team Names & Short Codes
  - Player Details
  - Team Logos / Images

---

## 🔍 **What I Analyzed**

- ✔️ Season-wise **team performance and standings**
- ✔️ Match outcomes including **finals and championship wins**
- ✔️ Player-level **batting and bowling performance**
- ✔️ Consistency of players across seasons
- ✔️ Venue-wise and team-wise match trends
- ✔️ High-impact players in pressure matches (Finals & Playoffs)

---

## 🛠️ **What I Did (Methodology)**

### 🧹 **Data Cleaning & Preparation**
- Cleaned and validated ball-by-ball records across all seasons
- Handled team name changes and franchise rebranding
- Standardized player and team naming conventions
- Removed redundant and inconsistent records

### 🔄 **Data Modeling**
- Built a **star schema** with fact and dimension tables
- Established optimized relationships between ball-by-ball, matches, teams, and players
- Created season, venue, and match-type dimensions for slicing

### 🧮 **Advanced DAX Measures (Core Focus)**
- Developed **complex DAX measures** for:
  - Total Runs, Wickets, Overs, Strike Rate, Economy
  - Orange Cap & Purple Cap logic
  - Season-wise top scorers and wicket-takers
  - Final match winners and championship counts
  - Player consistency metrics across seasons
- Used advanced DAX concepts:
  - `CALCULATE`, `FILTER`, `ALL`, `ALLEXCEPT`
  - `LOOKUPVALUE`
  - `RANKX`
  - `CONCATENATEX`
  - Context transition and filter propagation
- Handled **missing seasons and edge cases** in historical data
- Created dynamic measures responding to slicers (Season, Team, Player)

### 📊 **Dashboard Development**
- Designed interactive Power BI dashboards
- Built KPIs for teams, players, and seasons
- Enabled drill-through and cross-filtering
- Integrated team and player images for better storytelling

---

## 🎯 **Key Insights**

- 🏆 Identified the **most successful IPL teams** across seasons
- 🔥 Highlighted **consistent top performers** in batting and bowling
- 📈 Revealed season-wise scoring and wicket trends
- 🏟️ Discovered venue-specific advantages and patterns
- 🧠 Demonstrated how DAX enables **deep cricket analytics beyond basic stats**

---

## 🧑‍💼 **Business & Analytical Impact**

- ✅ Provides a **ready-to-use IPL analytics framework**
- ✅ Helps analysts practice **real-time, large-scale DAX modeling**
- ✅ Supports strategic insights for teams, analysts, and fans
- ✅ Acts as a reference project for **sports analytics portfolios**
- ✅ Enables faster and deeper IPL data exploration

---

## 🧰 **Tools & Technologies Used**

- 📊 **Microsoft Excel** – Initial data validation and structure checks  
- 🔄 **Power Query** – Data cleaning, transformation, and season-wise integration  
- 📈 **Power BI** – Data modeling, advanced DAX measures, and interactive dashboards  

---

## 🚀 **Conclusion**

This IPL dashboard is a **real-time, industry-level Power BI project** showcasing the power of **advanced DAX and data modeling** on a large historical dataset (2008–2025).  
It serves as a **valuable analytical resource** for anyone looking to understand IPL data deeply or strengthen their **sports analytics and BI expertise**.

---

## 📎 **Future Enhancements**

- 📊 Player vs Player matchup analysis
- 🔮 Match outcome prediction models
- 📈 Advanced performance trend forecasting
- 🌐 Integration with live IPL data feeds
- 📱 Deployment via Power BI Service with scheduled refresh

