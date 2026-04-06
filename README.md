# 🏏 IPL Data Analysis (2008–2017)

Exploratory Data Analysis on IPL match data using Python, NumPy, and Pandas.

---

## 📁 Project Structure

```
ipl-data-analysis/
│
├── data/
│   └── matches.csv
├── notebooks/
│   └── ipl_analysis.ipynb
├── ipl_analysis.html
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

- **Source:** [IPL Dataset on Kaggle](https://www.kaggle.com/datasets/nowke9/ipldata)
- **File:** `matches.csv`
- **Records:** 636 matches across 10 seasons (2008–2017)
- **Columns:** 17 features including teams, toss, venue, winner, player of the match

---

## 🛠️ Tools Used

- Python 3
- NumPy
- Pandas
- Jupyter Notebook

---

## 🔍 Analysis Performed

### Phase 1 — Data Cleaning
- Loaded dataset and inspected shape, columns, dtypes
- Handled null values in `city`, `winner`, `player_of_match`, `umpire1`, `umpire2`
- Dropped `umpire3` column (entirely empty — 0 non-null values)
- Verified no duplicate rows exist

### Phase 2 — Basic Exploration
- Number of seasons, teams, and total matches
- Which team has played the most matches

### Phase 3 — Winning Analysis
- Team with the most wins overall
- Win percentage per team
- Matches won by batting first vs chasing
- Cities hosting the most matches

### Phase 4 — Toss Analysis
- Does winning the toss help win the match?
- Preferred toss decision (bat/field) after winning
- Which team wins the toss most often

### Phase 5 — Player Analysis
- Top Player of the Match award winners
- Top 10 players per season

### Phase 6 — Close Matches & Big Wins
- Closest matches (wins by 1–5 runs)
- Biggest wins by runs and by wickets
- Super Over matches per season

---

## 💡 Key Findings

- **Mumbai Indians** have played the most matches and have the highest win count overall
- **Winning the toss** helps win the match roughly **51-52%** of the time — a slight but not decisive advantage
- Teams generally **prefer fielding first** after winning the toss
- **CH Gayle** is among the top Player of the Match award winners
- The biggest win by runs in IPL history is **146 runs**

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place `matches.csv` inside the `data/` folder
4. Open the notebook:
   ```bash
   jupyter notebook notebooks/ipl_analysis.ipynb
   ```

Or simply open `ipl_analysis.html` in any browser to view the full analysis without installing anything.

---

## 📌 Requirements

```
numpy
pandas
jupyter
```

---

## 👤 Author
- Made as a Data Science learning project.

=======
