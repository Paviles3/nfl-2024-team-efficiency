# NFL 2024 Team Efficiency Analysis

This project explores the relationship between team performance metrics and wins during the 2024 NFL season. Using a custom dataset of all 32 teams, I analyzed trends such as red zone efficiency, turnovers, total yards, and scoring to uncover key factors that contribute to winning football games.

## 🔍 Project Goals
- Identify which metrics (e.g., red zone %, turnovers, total yards) correlate most with wins
- Visualize team performance trends using Python (Pandas, Matplotlib, Seaborn)
- Practice exploratory data analysis (EDA) and storytelling with real-world sports data

## 📊 Key Findings
- **Red Zone Efficiency** had a strong positive correlation with total points scored and wins
- Teams with **fewer turnovers** generally won more games (e.g., Bills, Chargers)
- **Total yards** alone didn’t always predict wins — some high-yardage teams struggled to convert (e.g., Dolphins)
- **Rushing yards** had a stronger correlation with wins than passing yards for top teams

## 🛠 Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Custom-built CSV dataset using data from Pro Football Reference

## 📁 Files
- `NFL_2024_User_Data.csv`: Custom dataset of 2024 team stats
- `nfl_analysis.ipynb`: Notebook with all visualizations and code
- `README.md`: Project summary

## 📈 Sample Visualizations
- Wins vs Turnovers
- Red Zone % vs Points Scored
- Total/PASS/RUSH Yards vs Wins
- Top & Bottom 10 charts for key metrics
- Correlation heatmap of all stats

## 📌 Next Steps
- Build a Streamlit dashboard for interactive visualizations
- Expand analysis to include playoff data or player-level stats

---

### 📌 How to Use
Clone the repo and run `nfl_analysis.ipynb` in Jupyter Notebook. Make sure `pandas`, `matplotlib`, and `seaborn` are installed.

