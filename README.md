# Player-Team-Fatigue-Analysis-under-Fixture-Congestion
This project analyzes the impact of fixture congestion on football team performance by examining rest
days between matches and categorizing workload intensity. Using match-level data and team physical
attributes, the analysis explores how short recovery periods influence goal difference, attacking and
defensive performance, and overall team resilience. The project further evaluates whether higher team
quality and stronger physical profiles help mitigate fatigue-related performance decline during
congested schedules.


---

## Dataset
- Source: European Soccer Dataset (Kaggle)
- Data includes:
  - Match dates and seasons
  - Goals scored and conceded
  - Team identifiers
  - Player and team physical attributes
  - Rest days and workload categories

---

## Key Questions Addressed
- How does team performance change as rest days decrease?
- Does fixture congestion negatively impact goal difference?
- Are some teams more resilient to congestion than others?
- Do physical attributes reduce fatigue-related performance decline?
- How does match volume vary across seasons?

---

## Methodology
1. Extracted data from SQLite database and CSV files
2. Cleaned and processed match and player attribute data
3. Engineered workload metrics such as rest days and congestion categories
4. Performed analysis using Python and SQL
5. Visualized insights using Tableau dashboards

---

## Key Insights
- Performance declines as fixture congestion increases
- Both attacking and defensive performance suffer under high congestion
- Teams with higher overall quality show better resilience
- Physical attributes like sprint speed and strength reduce fatigue impact
- Match congestion varies across seasons, increasing risk in certain periods

---

## Business Recommendations
- Reduce the number of short-rest fixtures where possible
- Use squad rotation strategically during congested schedules
- Invest in player fitness and squad depth
- Monitor workload metrics proactively throughout the season
- Apply data-driven planning for long and congested seasons

---

## Tools & Technologies
- Python (Pandas, NumPy)
- SQL (SQLite)
- Tableau (Data Visualization)

---

## Repository Structure
player-Team-Fatigue-Analysis-under-Fixture-Congestion/
│
├── data/
│ ├── raw/
│ ├── processed/
│ └── final/
│
├── notebooks/
├── tableau/
├── reports/
│ └── insights_summary.txt
│
└── README.md

---

## Conclusion
This project demonstrates how data analysis can uncover the impact of workload and congestion on football
team performance and highlights the importance of physical conditioning and squad management in
high-demand seasons.

