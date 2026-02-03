
# 🏏 Data-Driven Player Selection for IPL Auction

## 📌 Project Overview

This mini project focuses on **data-driven player selection** for an IPL-style auction using player performance data from **league** and **international T20 matches**.
The system combines **clustering, regression, and performance scoring** to identify suitable batsmen, all-rounders, and bowlers under a budget-friendly strategy.

---

## 🎯 Objectives

* Analyze batting and bowling performance using historical data
* Group players based on batting behavior using clustering
* Predict expected runs using regression
* Rank and select players for an IPL squad
* Generate a final auction dashboard

---

## 🧠 Problem Statement

Player selection in auctions is often subjective and experience-based.
This project uses **machine learning and statistical techniques** to support **objective and data-driven squad selection**, improving fairness and decision accuracy.

---

## 🛠 Technologies Used

* **Language:** Python
* **Libraries:**

  * Pandas, NumPy
  * Scikit-learn
* **ML Techniques:**

  * K-Means Clustering
  * Linear Regression
* **Tools:** Git, GitHub

---

## 📂 Project Structure

```
Data-Driven-Player-Selection/
│
├── data/
│   ├── Syd_Batting.xlsx
│   ├── Syd_Bowling.xlsx
│   ├── t20_batting_intl.csv
│   └── t20_bowling_intl.csv
│
├──  main.py
│  
├── outputs/
│   └── ipl_auction_dashboard.csv
├── README.md
```

---

## 📊 Dataset Description

The dataset includes:

* Batting metrics: Runs, Strike Rate, Average, 4s, 6s
* Bowling metrics: Wickets, Economy, Overs
* Player roles: Batsman, All-Rounder, Bowler
* Data from league and international T20 matches

Missing values are handled using **data imputation**.

---

## 🔄 Methodology

1. **Data Collection & Cleaning**
   League and international batting/bowling datasets are merged and cleaned.

2. **Feature Scaling**
   Batting features are standardized using `StandardScaler`.

3. **Batting Clustering**

   * K-Means clustering groups players into 3 batting performance clusters.

4. **Impact Score Calculation**
   A batting impact score is computed using:

   * Runs
   * Strike Rate
   * Batting Average

5. **Expected Runs Prediction**
   Linear Regression predicts expected runs based on:

   * Batting average
   * Strike rate
   * Matches played

6. **Squad Selection**

   * Top batsmen, all-rounders, and bowlers are selected
   * Budget-friendly players are prioritized
   * Final squad is generated

---

## 🤖 Machine Learning Techniques Used

### 🔹 K-Means Clustering

* Groups players based on batting characteristics
* Helps identify high-impact and low-impact batters

### 🔹 Linear Regression

* Predicts expected runs for each player
* Assists in future performance estimation

---

## 🚀 How to Run the Project

```bash
pip install -r requirements.txt
python main.py
```

---

## 📈 Output

* Final IPL squad with selected players
* Player impact scores and predicted runs
* Auction dashboard exported as:

```
ipl_auction_dashboard.csv
```

---

## 📌 Applications

* IPL / franchise auctions
* Sports analytics
* Talent scouting
* Decision support systems

---

## 🔮 Future Enhancements

* Add bowling impact score
* Use Random Forest or XGBoost
* Build a web-based auction dashboard
* Real-time data integration

---

## 👨‍💻 Author

**Tamilmani C**
MCA 

---

