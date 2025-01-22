# IPL Analysis Dashboard (2008-2022)

## Overview

This project focuses on analyzing IPL (Indian Premier League) data from 2008 to 2022. Using Power BI, the project covers various aspects of data processing, modeling, and visualization to derive actionable insights about IPL performances.

---

## Problem Statements Addressed

1. **Orange Cap Holder**: Identifying the player with the most runs in a season or across all seasons.
2. **Purple Cap Holder**: Determining the bowler with the most wickets.
3. **Player Statistics**: 
   - **Batsman Stats**: Total runs, sixes, fours, and strike rates.
   - **Bowling Stats**: Wickets, average, strike rate, and economy.
   - **Slicers for Players**: Allows users to filter stats by player.
4. **Season-wise Data**:
   - Added a slicer to view stats for a specific season.
5. **Match Wins Analysis**:
   - **Wins by Team**: Visual representation of team performance over the years.
   - **Wins by Venue**: Matches won by different teams at various venues.
   - **Wins Based on Toss Decision**: Insight into winning trends for teams opting to bat or field after winning the toss.
6. **Match Results**: Matches categorized by result type – runs, wickets, super over, or no result.

---
 The dataset used for this analysis was sourced from **Kaggle**.
 
## Data Processing

- **Data Cleaning**:
  - Removed inconsistencies and unnecessary columns using Power Query.
  - Ensured integrity between tables by handling missing and duplicate values.
- **Data Modeling**:
  - Modeled three tables: `ipl_matches_2008_2022`, `ipl_ball_by_ball_2008_2022`, and `Calendar_Table`.
  - Established relationships between the tables to enable seamless data analysis.

---

## Key Learnings

1. **Data Modeling**:
   - Integrated multiple datasets and established appropriate relationships.
2. **Data Cleaning**:
   - Cleaned data using Power Query to ensure consistency.
3. **KPIs**:
   - Designed KPIs to track:
     - Top batsmen and bowlers based on performance metrics.
     - Team wins by season, venue, and match result.
     - Toss decisions and their impact on match outcomes.
4. **DAX Queries**:
   - Applied complex DAX formulas to generate insights, such as:
   - Worked on dynamic measures like strike rate, economy rate, and averages.
5. **Time Intelligence Functions**:
   - Used `CALCULATE` with filters to apply seasonal logic.
6. **Visualizations**:
   - Designed charts, KPIs, and slicers for user interaction.
   - Created formatted and polished dashboards with shapes and themes.
7. **Insights Generation**:
   - Delivered meaningful insights through graphs and data points.

---

## Tools and Technologies Used

- **Power BI Desktop**:
  - Data cleaning with Power Query
  - Data modeling
  - Visualizations (e.g., bar charts, pie charts, KPIs, and slicers)
  - DAX (Data Analysis Expressions)
- **Data Modeling Techniques**:
  - Star schema modeling
- **IPL Dataset**:
  - Match-level and ball-by-ball data from IPL seasons.

---

## Screenshots

### Full IPL Analysis Dashboard

![Screenshot (37)](https://github.com/user-attachments/assets/fa9352fd-fc12-4eeb-9286-bfa7e9cdfeaa)


### Season-wise IPL Dashboard

![Screenshot (36)](https://github.com/user-attachments/assets/ced1c635-0cca-4667-bd83-633d86356c44)


---

## How to Use

1. Clone this repository.
2. Open the Power BI file (`IPL_Analysis.pbix`) in Power BI Desktop.
3. Explore insights through the dashboard by interacting with slicers (e.g., seasons, players).
4. Modify and add filters as per your interest.

---

## Future Improvements

- Add advanced metrics like player consistency, partnership analysis, and economy trends over time.
- Incorporate additional datasets, such as player profiles and team details, for enhanced insights.
- Use R or Python scripts within Power BI for advanced statistical analysis.



