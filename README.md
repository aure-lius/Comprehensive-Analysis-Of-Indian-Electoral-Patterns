# 🌍 Comprehensive Analysis Of Indian Electoral Patterns

[![Tableau](https://img.shields.io/badge/Visualization-Tableau-blue)](https://www.tableau.com/) 
[![Python](https://img.shields.io/badge/Python-Pandas-green)](https://pandas.pydata.org/) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An interactive Tableau dashboard analyzing historical Indian election trends from 1977 to 2019. This project combines data cleaning, data aggregation, and compelling visualizations to showcase voter turnout patterns, gender participation, reservation category distribution, and party performances.

---

## 🔍 Problem Statement

Election data in India is massive and complex. To drive better political insights, strategic decision-making, and public awareness, there is a strong need to:
- Visualize turnout trends over decades.
- Analyze gender-based voter patterns.
- Track party performance over time.
- Understand reservation-based voter distribution.

---

## 🌟 Objective

- Clean and prepare the Indian election dataset for analysis.
- Build an interactive and dynamic Tableau dashboard.
- Derive actionable insights from voter and election trends.

---

## 📂 Dataset Information

| Field | Description |
|:---|:---|
| state | Name of Indian state |
| year | Election year (1977-2019) |
| reservation_category | GEN, SC, ST, or OTHERS |
| cand_sex | Gender of candidate (Male/Female) |
| party_name | Political party name |
| tot_vot_poll | Total votes polled |
| electors | Total registered electors |

Data Source: `election_cleaned_data.csv`

---

## 📝 Data Preparation

- Removed duplicates and irrelevant columns.
- Standardized gender labels.
- Filled missing values logically.
- Created calculated fields:
  - **Voter Turnout %** = (Total Votes Polled / Total Electors) * 100

---

## 📊 Dashboard Features & Insights

**KPIs:**
- Total Electors
- Total Votes Polled
- Voter Turnout %

**Visualizations:**
- **Voter Turnout % Over Years** (Line Chart)
- **Gender-wise Voter Distribution** (Stacked Area Chart)
- **Top 10 Political Parties by Votes** (Bar Chart)
- **Reservation Category Vote Share** (Stacked Bar Chart)
- **State-wise Voter Turnout Map** (Choropleth Map)

**Interactive Filters:**
- Year
- State
- Gender
- Reservation Category
- Party Name

**Key Insights:**
- Steady rise in voter turnout over the decades.
- Male voter participation remains higher, but female turnout is rising.
- Certain states consistently show higher turnout.
- Top political parties dominating different periods are highlighted.

---

## 🛠️ Tools and Technologies Used

- **Python (Pandas)**: Data cleaning and preprocessing.
- **Tableau Public**: Dashboard building and visualization.
- **Jupyter Notebook**: Initial exploratory data analysis.

---

## 🚀 How to Use This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/aure-lius/indian-election-analysis
   ```
2. Open `election data dashboard.twb` in Tableau Public.
3. Connect the dashboard to `election_cleaned_data.csv` if necessary.
4. Explore the dynamic filters and insights!

---

## 🏆 Future Enhancements

- Add winning margins analysis.
- Incorporate candidate-level demographic data (education, criminal records).
- Integrate predictive modeling (voter turnout prediction).
- Host the dashboard online (Tableau Public / AWS).

---

## 👨‍💻 Author

- **Mankirat Singh Kang**
- [LinkedIn](https://www.linkedin.com/in/mankirat-singh-78678b137) | [GitHub](https://github.com/aure-lius)

---

✨ If you found this project helpful, feel free to star the repository! ⭐
