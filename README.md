# 🏏 IPL 2008–2024 Data Analysis

Exploratory Data Analysis (EDA) of IPL ball-by-ball dataset from **2008 to 2024** using **Python, Pandas, Matplotlib, and Seaborn**.

This project analyzes IPL match data to uncover insights about **players, teams, scoring patterns, and match phases**.

---

## 📊 Project Objectives

The goal of this project is to:

* Explore IPL ball-by-ball data
* Analyze player and team performance
* Identify scoring trends and patterns
* Perform Exploratory Data Analysis (EDA)
* Visualize insights using Python libraries

This project is part of a **Data Science / Machine Learning portfolio**.

---

## 📁 Project Structure

```
IPL-EDA-Analysis/
│
├── data/
│   └── ipl_2008_2024.csv
│
├── notebooks/
│   └── ipl_eda.ipynb
│
├── images/
│   └── plots
│
├── README.md
└── requirements.txt
```

---

## 📂 Dataset

The dataset contains **ball-by-ball data of IPL matches from 2008–2024**.

Each row represents **one delivery in a match**.

### Important Features

* `id` – Match ID
* `innings` – Innings number
* `overs` – Over number
* `ball_number` – Ball within the over
* `batter` – Batsman facing the ball
* `bowler` – Bowler delivering the ball
* `batsman_run` – Runs scored by the batter
* `extras_run` – Extra runs (wide, no ball, etc.)
* `total_run` – Total runs from the delivery
* `iswicket_delivery` – Whether a wicket occurred
* `batting_team` – Batting team

Dataset location:

```
data/ipl_2008_2024.csv
```

---

## 🔎 Exploratory Data Analysis (EDA)

The following analyses were performed:

### 1️⃣ Dataset Overview

* Dataset size
* Column information
* Summary statistics

### 2️⃣ Data Cleaning

* Handling missing values
* Data preprocessing

### 3️⃣ Feature Engineering

New features created:

* Boundary indicator
* Dot ball indicator
* Match phase classification (Powerplay / Middle / Death overs)

### 4️⃣ Player Analysis

* Top run-scoring batsmen
* Players with most sixes
* Players with most fours
* Strike rate analysis

### 5️⃣ Bowling Analysis

* Most wickets by bowlers
* Dot ball specialists
* Bowling performance insights

### 6️⃣ Team Performance

* Total runs scored by teams
* Team scoring comparison

### 7️⃣ Match Phase Analysis

Runs scored in:

* Powerplay overs (1–6)
* Middle overs (7–15)
* Death overs (16–20)

### 8️⃣ Dismissal Analysis

* Types of wickets
* Most common dismissal methods

---

## 📈 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

---

## ▶️ How to Run This Project

1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/Data-Analysis.git
```

2. Navigate to the project folder

```
cd Data-Analysis
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Open the notebook

```
notebooks/ipl_datanalysis.ipynb
```

---

## 📊 Sample Insights

Some interesting insights discovered:

* Certain players dominate IPL run charts with consistent performances.
* Death overs contribute significantly to total match runs.
* A small group of bowlers accounts for a large percentage of wickets.
* Boundary hitting plays a major role in team scoring rates.

---

## 🚀 Future Improvements

Possible extensions of this project:

* Match outcome prediction using Machine Learning
* Player performance prediction
* IPL analytics dashboard
* Interactive visualizations using Plotly or Power BI

---

## 👨‍💻 Author

**Navyam Jain**

Computer Science Student
Aspiring AI / Machine Learning Engineer
