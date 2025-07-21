# 🏏 ICC Cricket World Cup 2023 Winner Prediction

This project uses **machine learning** to predict match outcomes and the potential winner of the **2023 ICC Cricket World Cup** using historical performance and team statistics.

---

## 🎯 Objective

- Predict the **winner** of the 2023 Cricket World Cup
- Perform **exploratory data analysis** (EDA) on past and current team performance
- Help analysts understand key factors contributing to match outcomes
- Forecast match results based on team rankings, win percentage, and other metrics

---

## 📂 Dataset Description

Multiple datasets were used for this project:

| Dataset Name       | Description |
|--------------------|-------------|
| `fixtures.csv`     | Match schedule for the 2023 World Cup |
| `icc_ranking.csv`  | Official ICC ODI rankings for the 10 participating teams |
| `world_cup_2023.csv` | Historical win/loss stats and percentages |
| `results.csv`      | Match results since 2015 including venue and margin |

---

## 📊 Exploratory Data Analysis (EDA)

- Win percentages across teams in ODIs
- Comparison of ICC rankings
- Past performance in World Cup matches
- Venue-wise impact on results

---

## 🧠 Modeling Approach

- Used **Random Forest** classifier
- Split data into training and testing sets
- Model trained on:
  - Win percentage
  - Team-wise and match-wise statistics
  - ICC rankings

### ⚙️ Model Results

| Metric     | Value     |
|------------|-----------|
| Training Accuracy | 63% |
| Testing Accuracy  | 53% |

- Predicted **Semi-Finalists** and **Finalist** based on match simulations

---

## 🏁 Conclusion

- The Random Forest model helped analyze over **720 international matches** (since 2015)
- Gained meaningful insights on **team strengths**, win probabilities, and match factors
- Despite modest accuracy, the model effectively demonstrated prediction capability in sports analytics
