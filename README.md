# ⚽ Artificial Intelligence – Exercise 1
## International Football Results Analysis (1872–2024)

---

## 📌 Project Overview

This project analyses international football match results spanning over 150 years (1872–2026).
Using Python and data analysis libraries, we explore match outcomes, goal patterns, home advantage,
and the most successful national teams of all time.

---

## 📂 Dataset

**Source:** [Kaggle – International Football Results from 1872 to 2024](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)

| File | Description |
|---|---|
| `results.csv` | Main dataset — 49,287 international match results |
| `goalscorers.csv` | Details of individual goal scorers |
| `shootouts.csv` | Penalty shootout outcomes |
| `former_names.csv` | Historical name changes of countries/teams |

---

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** — data loading, cleaning, and analysis
- **Matplotlib** — data visualisation
- **Seaborn** — statistical chart styling
- **Jupyter Notebook** — interactive coding environment

---

## 📊 Analysis Sections

### Section A — Basic Exploration
- Total number of matches in the dataset
- Earliest and latest match dates
- Number of unique countries/teams
- Most frequent home team

### Section B — Goals Analysis
- Average goals per match
- Highest scoring match ever
- Home goals vs away goals comparison
- Most common total goals value

### Section C — Match Results
- Percentage of home wins, away wins, and draws
- Whether home advantage exists
- Country with the most wins all time

### Section D — Visualisations
- Histogram of total goals per match
- Bar chart of match outcomes (Home Win / Away Win / Draw)
- Horizontal bar chart of top 10 teams by total wins

---

## 🔑 Key Findings

| Question | Finding |
|---|---|
| Total matches | 49,287 matches |
| Date range | 30 November 1872 to 27 June 2026 |
| Unique countries | 333 countries / teams |
| Most frequent home team | Brazil (614 home matches) |
| Average goals per match | 2.94 goals |
| Highest scoring match | Australia 31–0 American Samoa (11 April 2001) |
| Goals: home vs away | More goals scored at HOME (86,426 vs 58,192) |
| Most common goals total | 2 goals per match |
| Home win % | 48.9% of matches |
| Home advantage | YES — confirmed |
| Most wins all-time | Brazil (670 wins) |

---

## ▶️ How to Run

1. Clone this repository:
```bash
git clone https://github.com/sandracod0/football-analysis.git
cd football-analysis
```

2. Install required libraries:
```bash
pip install pandas matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `football_analysis.ipynb` and run **Cell → Run All**

---

## 👩‍🎓 Submission Info

- **Course:** Artificial Intelligence
- **Exercise:** 1 — Football Data Analysis
- **Dataset:** International Football Results (Kaggle)
- **Author:** sandracod0
