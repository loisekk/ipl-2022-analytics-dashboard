# 🏏 IPL 2022 Analytics Dashboard

<div align="center">

![IPL 2022](https://img.shields.io/badge/IPL-2022-blue?style=for-the-badge&logo=cricket&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A comprehensive exploratory data analysis (EDA) suite for IPL 2022 match-level data — uncovering team dynamics, player performances, venue trends, and match outcome patterns.**

</div>

---

## 📌 Overview

The **Indian Premier League (IPL)** is one of the most-watched T20 cricket leagues in the world. This capstone project performs in-depth analysis on the IPL 2022 season dataset, transforming raw match data into actionable insights through statistical analysis and rich visualizations.

From toss strategies to top-scorers, from venue dominance to bowling masterclasses — this notebook covers it all.

---

## 📁 Project Structure

```
ipl-2022-analytics-dashboard/
│
├── IPL_analytics_suite.ipynb   # Main analysis notebook
├── ipl.xls                     # Raw IPL 2022 match dataset
├── requirements.txt            # Python dependencies
└── README.md
```

---

## 📊 Dataset

The dataset (`ipl.xls`) contains **match-level records** from the IPL 2022 season with the following key fields:

| Column | Type | Description |
|---|---|---|
| `date` | string | Match date |
| `venue` | string | Stadium name |
| `stage` | string | Group / Qualifier / Final |
| `team1` / `team2` | string | Competing teams |
| `toss_winner` | string | Team that won the toss |
| `toss_decision` | string | Bat or field |
| `first_ings_score` | integer | 1st innings total |
| `second_ings_score` | integer | 2nd innings total |
| `match_winner` | string | Winning team |
| `won_by` | string | Runs or Wickets |
| `margin` | integer | Winning margin |
| `player_of_the_match` | string | POTM award winner |
| `top_scorer` | string | Highest-run batter |
| `highscore` | integer | Individual top score |
| `best_bowling` | string | Best bowler of the match |
| `best_bowling_figure` | string | Bowling figures (e.g., 3--24) |

---

## 🔍 Analysis Modules

### 1. 🏆 Team Performance
- Which team won the **most matches** in IPL 2022
- Visual: Horizontal bar chart of team win counts

### 2. 🎲 Toss Analysis
- **Toss decision trends** — how teams chose to bat or field
- **Toss winner vs Match winner** correlation — percentage of times winning the toss translated to winning the match

### 3. ⚡ Match Outcomes
- How teams won — breakdown by **Runs** vs **Wickets**
- Win margin distribution

### 4. 🌟 Player Performances
- Top 10 **Player of the Match** award winners
- **Top scorers** by cumulative runs
- **Best bowling figures** — top 10 bowlers ranked by wickets

### 5. 🏟️ Venue Analysis
- Most-used venues across the tournament
- Match distribution by stadium

### 6. 💡 Custom Insights
| Question | Finding |
|---|---|
| Highest win margin by runs | Team with the biggest margin victory |
| Highest individual score | Top-scoring batsman in a single innings |
| Best bowling figure | Most wickets taken in a single match |

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, transformation |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting |
| `seaborn` | Statistical visualizations |
| `plotly` | Interactive charts |
| `warnings` | Suppress deprecation noise |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Jupyter Notebook or JupyterLab

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/loisekk/ipl-2022-analytics-dashboard.git
cd ipl-2022-analytics-dashboard

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Jupyter
jupyter notebook IPL_analytics_suite.ipynb
```

> **Note:** Make sure `ipl.xls` is in the same directory as the notebook before running cells.

---

## 📈 Sample Visualizations

- **Team Win Counts** — Seaborn horizontal barplot with `viridis` palette
- **Toss Decision Trends** — Countplot colored by highscore with `rainbow` palette
- **Top 10 POTM Winners** — Barplot with `mako` palette
- **Top Scorers** — Horizontal bar chart by cumulative runs
- **Best Bowling Figures** — Ranked barplot with `rainbow` palette

---

## 🔑 Key Findings

- Toss-to-win correlation: ~**X%** of toss winners went on to win the match *(run notebook to compute)*
- A few elite all-rounders dominate the **Player of the Match** leaderboard
- **Chasing** (fielding first) was the preferred toss decision across the season
- Certain venues recorded significantly higher match counts, reflecting scheduling density

---

## 👤 Author

**Yash Brahmankar**
- GitHub: [@loisekk](https://github.com/loisekk)
- Email: yashbrahmankar95@gmail.com

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">
Made with ❤️ and cricket data
</div>
