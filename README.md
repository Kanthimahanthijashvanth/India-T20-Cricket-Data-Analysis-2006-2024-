# 🏏 India T20 Cricket Data Analysis (2006–2024)

This project performs data analysis and visualization on Team India’s T20 cricket matches from 2006 to 2024. Using Python libraries like **Pandas**, **Matplotlib**, and **Seaborn**, it explores trends in wins, toss outcomes, captains' performance, and team matchups.

---

## 📊 Dataset

The dataset is taken from the following GitHub URL:
[Cricket Dataset](https://raw.githubusercontent.com/badapa1502/Cricket-Data-Analysis-T20/refs/heads/main/Datasets/india_T20_matches_2006-2024.csv)

Contains columns like:
- `Team 1`, `Team 2`
- `Winner`, `Margin`
- `Toss Winner`, `Toss Result`
- `Scorecard`, `Year`
- (Simulated) `Captain` *(added manually for captain analysis)*

---

## 🔍 Key Features & Analysis

### ✅ Team-based Filters:
- Filtered all matches where India played.
- Further filtered matches where India **won** the game.
- Filtered matches where India **won the toss**.

### 📈 Visualizations:

#### ✔ India Toss Wins per Year
- Bar plot of number of tosses India won each year.

#### ✔ India Wins Over the Years
- Bar plot showing matches India won per year.

#### ✔ Heatmap of Opponents
- Heatmap of matches between New Zealand and opponents.

#### ✔ Scatter Plot of Australia Matches
- Scatter plot showing year-wise match margins involving Australia.

#### ✔ Radar Plot of Indian Captains
- Radar chart comparing captain stats like:
  - Matches captained
  - Win percentage
  - (Optionally Batting Avg / Wickets if data available)

---

