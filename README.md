# 🏀 NBA_BenchImpact_Analysis

This project aims to analyze the impact of a teams bench players across NBA seasons relative to their teams success. Current game data is retrieved using `nba_api`, seperated by regular season and playoffs for the 19.  

**Latest Update:**  
✅ All playoff data from 1983–84 to 2023–24 has been collected using automated season-by-season scrapers. Added logic to skip previously games and resume failures.  
🔄 Currently working on collecting regular season data and building the preprocessing pipeline for analysis.

---

## 🧠 Technologies Used

- Python (pandas, numpy, nba_api)
- JupyterLab
- Git/GitHub for version control
- Power BI / Tableau (planned)

---

## 📁 Structure

NBA_BenchImpact_Analysis/
├── data/
│ └── raw/
│ ├── playoff_batches/
│ └── regular_batches/
├── logs/
└── notebooks/

---

## ✨ Features

- Downloads game-level box score data using `nba_api`
- Saves each season’s playoff and regular season data in separate folders
- Built-in logic to skip already processed games and resume failed ones
- Logs any failed GAME_IDs for retry later
- Automatically creates required directories if missing

---

## 📌 Future Plans

- Add historical data from 1976–1983 using Basketball Reference in Phase 2
- Transform data into clean player stats
- Visualize bench performance metrics
- Build a model to estimate bench impact on win probability (Does a good bench = more wins?)

---

## 👤 Author

[Evon Williams](https://www.linkedin.com/in/evon-williams-03729989)

---

> 📂 *This is a work-in-progress portfolio project. Updates will be made incrementally and transparently as more data is collected and developed.*
