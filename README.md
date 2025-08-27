# 🏏 IPL Data Analysis

## 📌 Overview
This project focuses on **data analysis of IPL (Indian Premier League) cricket statistics** using Python.  
The objective is to explore batting and bowling performances of players, clean and transform the dataset, and extract meaningful insights using data analysis and visualization techniques.

## 📂 Dataset
- **File Used:** `cricket_data.csv`  
- **Features include:**  
  - Player details: `Player_Name`  
  - Batting stats: `Matches_Batted`, `Runs_Scored`, `Highest_Score`, `Batting_Average`, `Strike_Rate`, `Centuries`, `Fours`, `Sixes`,      etc.  
  - Bowling stats: `Matches_Bowled`, `Balls_Bowled`, `Runs_Conceded`, `Wickets_Taken`, `Bowling_Average`, `Economy_Rate`, `Five_Wicket_Hauls`, etc.  
  - Fielding stats: `Catches_Taken`, `Stumpings`

## 🛠️ Tools & Libraries
The following libraries are used in the project:
- **pandas** → Data loading, cleaning, transformation  
- **numpy** → Numerical operations and statistics  
- **matplotlib** → Data visualization  
- **seaborn** → Enhanced plots and graphs  

## 🔎 Steps & Methodology
1. **Data Loading**  
   - Imported dataset using Pandas (`read_csv`).  

2. **Data Cleaning & Preprocessing**  
   - Removed special characters from `Highest_Score`.  
   - Converted relevant columns to numeric datatypes.  
   - Handled missing values using appropriate techniques.  

3. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics (`info`, `describe`).  
   - Checking null values.  
   - Calculating averages, medians, strike rates, and player comparisons.  

4. **Insights Generation**  
   - Identified players with **above average runs**.  
   - Found **Top 10 Run Scorers**.  
   - Compared batting strike rates and averages.  
   - Analyzed bowling performances (economy, wickets).  

5. **Data Visualization**  
   - Plotted **bar charts, histograms, and scatter plots** using Matplotlib & Seaborn.  
   - Visualized top scorers, strike rate distributions, and key performance metrics.  

## 📊 Key Results
- Calculated mean and median batting strike rates.  
- Identified top run scorers and consistent batsmen.  
- Highlighted players performing above the tournament average.  
- Bowling analysis showed most economical bowlers and top wicket takers.  
