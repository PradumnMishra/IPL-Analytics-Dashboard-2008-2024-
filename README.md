# IPL Analytics Dashboard (2008 - 2024)

## 📊 Project Overview
This Power BI project provides a comprehensive analysis of the Indian Premier League (IPL) data across **17 seasons**. It features interactive reporting on match trends, team performance, and individual player statistics, utilizing a dataset of **1,106 matches** and **16 teams**.

## 📂 Key Report Pages

### 1. IPL Overview
Provides a high-level summary of the tournament's history and global trends.
* **Tournament Metrics:** Displays the total number of seasons, matches, and teams involved.
* **Most Used Venues:** A specialized visual highlighting stadiums with the highest match density.
* **Bowling Discipline:** Analysis of **Sum of No-balls** and **% of Wide Balls** by season to track bowling accuracy over time.
* **Seasonal Trends:** A line chart displaying **Average Runs Per Match** by season.
* **Dynamic Tooltip:** Hovering over the "Average Runs" chart triggers a custom tooltip showing:
    * **Total Boundary Trends** (Year-over-Year).
    * **Distribution of Runs** (Breakdown of 1s, 2s, 4s, and 6s).
    <img width="931" height="257" alt="tooltip" src="[https://github.com/user-attachments/assets/56fc14b2-e7f1-4e80-8e38-3fdd7aee43de]" />

 * **Qualifying Teams Table:** A historical leaderboard showcasing the **Top 4 teams (QFT1, QFT2, QFT3, QFT4)** for every season, providing an instant look at the league's most consistent franchises.   

### 2. Team Profile
A deep dive into specific franchise performance and situational analytics.
* **Interactive Slicers:** Users can filter by Season, Team, and specific Over ranges.
* **Dynamic Toggle:** A specialized feature allowing users to toggle the view between **Overs, Wickets, and Boundaries** to see how a team performs in specific phases of the game.
* **Performance Leaderboards:** Dynamically identifies the top batting and bowling contributors for the user-selected season.

### 3. Player Profile
Focuses on individual player efficiency and granular head-to-head matchups.
* **Batsman vs. Bowler:** Analyze exactly how a specific batsman performs against a specific bowler within a selected season.
* **Batting Leaderboard:** Ranks players by **Strike Rate** and their **Highest Score** in a particular season.
* **Bowling Leaderboard:** Lists bowlers by **Economy Rate** and total **Wickets** taken in a particular season.

## 📈 Key Insights
* **2024 Scoring Spike:** The dashboard highlights 2024 as the highest-scoring season ever, driven by the "Impact Player" rule and aggressive batting mindsets.
* **Boundary Dominance:** Tooltip data reveals a significant increase in 6s during the middle overs compared to the 2008-2015 era.
* **Venue Bias:** High-scoring trends are most prominent at venues like Wankhede and M. Chinnaswamy, as shown in the Venue Analysis.

## 🛠️ Technical Details
* **Tool:** Power BI Desktop
* **DAX Implementation:** Includes advanced measures for:
    * **Accurate Economy Rate** (handling legal vs. illegal deliveries).
    * **Strike Rates** and **Boundary Percentages**.
    * **Dynamic Title Headers** that change based on slicer selections.


