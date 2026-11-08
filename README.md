# 🏏 NEXORA Cricket Intelligence
### IPL Analytics Platform | Microsoft Power BI

**WHERE CRICKET MEETS DATA INTELLIGENCE**

An interactive sports analytics platform covering **17 IPL seasons (2008–2024)**, developed using Microsoft Power BI to analyze player performance, franchise statistics, match outcomes, and tournament trends.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analytics-512BD4?style=for-the-badge)
![Sports Analytics](https://img.shields.io/badge/Domain-Sports%20Analytics-00CFE8?style=for-the-badge)
![IPL](https://img.shields.io/badge/IPL-2008--2024-00BFA6?style=for-the-badge)

---

## 📑 Table of Contents

1. [Project Overview](#-project-overview)
2. [Project Objectives](#-project-objectives)
3. [Dashboard Modules](#-dashboard-modules)
4. [Key Performance Indicators](#-key-performance-indicators)
5. [Interactive Features](#-interactive-features)
6. [Tools and Technologies](#-tools-and-technologies)
7. [Dataset Information](#-dataset-information)
8. [Data Preparation and Modeling](#-data-preparation-and-modeling)
9. [How to Run the Project](#-how-to-run-the-project)
10. [Project Outcomes](#-project-outcomes)
11. [Repository Structure](#-repository-structure)
12. [Author](#-author)

---

## 🎯 Project Overview

**NEXORA Cricket Intelligence** is a multi-page IPL analytics platform developed using Microsoft Power BI.

Covering 17 IPL seasons from 2008 to 2024, this project transforms historical match-level and ball-by-ball cricket data into meaningful analytical insights.

The platform provides an interactive environment to explore:

- Tournament statistics and historical trends.
- Individual batting and bowling performances.
- Franchise achievements and team comparisons.
- Match outcomes and toss-related patterns.
- Venue activity and season-wise scoring trends.

The solution combines Power Query transformations, data modeling, DAX calculations, and interactive visualizations to deliver a comprehensive cricket analytics experience.

## 🎯 Project Objectives

- Analyze IPL tournament statistics across multiple seasons.
- Identify top-performing batsmen and bowlers.
- Evaluate batting and bowling performance using statistical measures.
- Compare franchise wins and team performance.
- Understand batting-first versus chasing match outcomes.
- Analyze toss decisions and their relationship with match results.
- Explore venue activity and season-wise scoring patterns.
- Present complex cricket data through interactive visual storytelling.

---

## 📊 Dashboard Modules

The platform consists of **six report pages**, including one introduction page and five analytical dashboard pages.

### 1. Introduction – NEXORA Cricket Intelligence

Introduces the analytics platform and provides navigation to its five analytical modules.

**Key highlights:**
- NEXORA Cricket Intelligence branding.
- IPL 2008–2024 coverage.
- Overview of the five dashboard modules.
- Dedicated dashboard navigation.

### 2. Tournament Overview

Provides a consolidated overview of IPL tournament statistics and franchise achievements.

**Key insights:**
- Total matches, teams, runs, and wickets.
- Orange Cap and Purple Cap leaders.
- Player of the Tournament.
- Runs by season and franchise.
- Batting-first versus chasing wins.
- Average runs per match by season.
- Franchise-wise wins and tournament titles.
- Season-wise highest and lowest innings.

### 3. Batting Intelligence

Evaluates individual batting performance and identifies top-performing batsmen.

**Key insights:**
- Batter runs, fours, and sixes.
- Batting strike rate.
- Top 10 batters by runs.
- Top 10 batters by strike rate.
- Fours versus sixes comparison.
- Runs versus strike rate scatter analysis.

### 4. Bowling Intelligence

Analyzes bowling effectiveness, wicket-taking ability, and bowling performance.

**Key insights:**
- Total wickets.
- Bowler runs conceded.
- Bowling economy.
- Legal balls bowled.
- Top wicket takers.
- Best bowling economy.
- Wickets by season.
- Bowling performance: runs versus wickets.
- Wickets by match phase.
- Dismissal type analysis.
- Over-by-over bowling analysis.

### 5. Match Insights

Explores match outcomes, toss decisions, venue activity, and winning patterns.

**Key insights:**
- Total matches.
- Batting-first and chasing wins.
- Toss-to-wins percentage.
- Toss decision and match outcome analysis.
- IPL match locations and venue activity.
- Top 10 venues by matches hosted.
- Impact of winning the toss on match victory.

### 6. Team Performance

Compares IPL franchise performance through wins, winning percentages, and historical team rankings.

**Key insights:**
- Total matches and total wins.
- Total runs and bowler wickets.
- Average runs per match.
- Wins by franchise.
- Win percentage by team.
- Team wins versus losses.
- Team rankings across IPL seasons.

---

## 🔢 Key Performance Indicators

The following KPIs are displayed across the dashboard pages.

| Dashboard | KPI | Displayed Value |
|---|---|---:|
| Tournament Overview | Total Matches | 1,095 |
| Tournament Overview | Total Teams | 15 |
| Tournament Overview | Total Runs | 348K |
| Tournament Overview | Total Wickets | 13K |
| Batting Intelligence | Batter Runs | 330K |
| Batting Intelligence | Total Fours | 30K |
| Batting Intelligence | Total Sixes | 13K |
| Batting Intelligence | Batting Strike Rate | 130.70 |
| Bowling Intelligence | Total Wickets | 13K |
| Bowling Intelligence | Bowler Runs Conceded | 341K |
| Bowling Intelligence | Bowling Economy | 8.14 |
| Bowling Intelligence | Legal Balls Bowled | 251K |
| Match Insights | Batting First Wins | 500 |
| Match Insights | Chasing Wins | 590 |
| Match Insights | Toss-to-Wins % | 50.8% |
| Team Performance | Total Wins | 1,090 |
| Team Performance | Average Runs per Match | 158.79 |

*Note: Values are taken from the displayed dashboard pages. Different pages may use different measures and filter contexts.*

---

## ⚡ Interactive Features

The dashboard provides several interactive features for deeper analysis.

- **Season Filters:** Explore individual IPL seasons or all seasons.
- **Team Filters:** Analyze franchise-level performance.
- **Batter Filters:** Focus on individual batting statistics.
- **Bowler Filters:** Explore individual bowling performance.
- **Venue Filters:** Analyze match activity across venues.
- **Result Filters:** Examine team performance by match result.
- **Cross-Page Navigation:** Move between dashboard modules.
- **Reset Button:** Restore the report to its default filter state.
- **Interactive Visuals:** Explore detailed insights through Power BI visual interactions.

---

## 🛠️ Tools and Technologies

| Technology | Application |
|---|---|
| Microsoft Power BI | Interactive dashboard development |
| DAX | Measures, calculations, and KPIs |
| Power Query | Data cleaning and transformation |
| Data Modeling | Relationships between datasets |
| CSV | IPL match and delivery datasets |
| JSON | Custom Power BI report theme |

### Technical Highlights

- Developed a multi-page Power BI analytics platform.
- Created DAX measures for batting, bowling, and team statistics.
- Established relationships between match-level and delivery-level datasets.
- Standardized historical franchise names.
- Built season, team, batter, and bowler filters.
- Designed a consistent dark navy, cyan, and purple theme.
- Used different visualizations for different analytical perspectives.

---

## 📂 Dataset Information

The project uses two primary IPL datasets.

### 1. Matches Dataset – `matches.csv`

Contains match-level information, including:

- Match ID
- Season
- Date
- Teams
- Venue and city
- Toss winner
- Toss decision
- Match winner
- Player of the match
- Result details

### 2. Deliveries Dataset – `deliveries.csv`

Contains ball-by-ball information, including:

- Match ID
- Inning
- Batting team
- Bowling team
- Over and ball
- Batter
- Bowler
- Batsman runs
- Extra runs
- Total runs
- Wicket information
- Dismissal type

**Dataset Coverage:** IPL seasons 2008–2024.

---

## 🧹 Data Preparation and Modeling

Data preparation was performed using Power Query and Power BI modeling capabilities.

Key activities included:

- Standardizing historical franchise names.
- Handling missing and blank values.
- Correcting column data types.
- Validating match and delivery records.
- Preparing season and team dimensions.
- Establishing relationships between datasets.
- Developing measures for batting, bowling, and team analysis.

The analytical model connects match-level and delivery-level records through their common match identifier.

---

## 🚀 How to Run the Project

Follow these steps to explore the dashboard locally.

### Step 1 – Clone the Repository

```bash
git clone https://github.com/Sujal2611/NEXORA-Cricket-Intelligence.git
```

### Step 2 – Open Power BI Desktop

Navigate to the downloaded repository and open:

`Cricket_Analytics.pbix`

### Step 3 – Connect the Datasets

If Power BI requests updated file locations, reconnect:

- `DataSet/matches.csv`
- `DataSet/deliveries.csv`

### Step 4 – Refresh the Data

Select **Home → Refresh** in Power BI Desktop.

### Step 5 – Explore the Dashboard

Use the navigation buttons, filters, and interactive visualizations to explore IPL analytics.

---

## 💡 Project Outcomes

NEXORA Cricket Intelligence demonstrates the practical application of business intelligence techniques in sports analytics.

The project showcases:

- Transformation of raw cricket data into analytical information.
- Player performance evaluation using statistical measures.
- Franchise comparison and historical performance analysis.
- Match outcome and toss decision analysis.
- Interactive reporting using DAX and Power BI.
- Professional dashboard design and analytical storytelling.

---

## 📁 Repository Structure

```text
NEXORA-Cricket-Intelligence/
│
├── DataSet/
│   ├── deliveries.csv
│   └── matches.csv
│
├── Cricket_Analytics.pbix
├── Cricket_Analytics.pdf
├── NEXORA_Theme.json
├── Logo.png
├── Intro_page.png
├── Match_Insights.png
├── IPL Batting Intelligence Banner.png
├── NEXORA Bowling Intelligence Banner.png
├── Nexora_Team_Performance_Banner_1280x150.png
├── Action Button.png
├── Title BG.png
├── .gitattributes
└── README.md
```

---

## 👨‍💻 Author

### Sujal Upadhyay

**Data Science Student | Aspiring Data Analyst**

Interested in Data Analytics, Business Intelligence, SQL, and Data Visualization.

- **GitHub Profile:** [Sujal2611](https://github.com/Sujal2611)
- **Project Repository:** [NEXORA Cricket Intelligence](https://github.com/Sujal2611/NEXORA-Cricket-Intelligence)

---

## 🏁 Conclusion

NEXORA Cricket Intelligence brings cricket and data analytics together through an interactive, multi-page Power BI platform.

By combining data preparation, DAX, data modeling, and professional visualization, the project transforms historical IPL data into meaningful insights about players, teams, matches, and tournament performance.

**NEXORA – WHERE CRICKET MEETS DATA INTELLIGENCE. 🏏**

⭐ If you find this project interesting, consider giving the repository a star!
