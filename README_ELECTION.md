# 🗳️ Indian Election Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/) 
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-green)](https://pandas.pydata.org/) 
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A data cleaning and exploration project analyzing trends from India's election datasets.

---

## 📚 Table of Contents

- [Project Overview](#-project-overview)
- [Technologies Used](#-technologies-used)
- [Project Workflow](#-project-workflow)
- [Dataset Details](#-dataset-details)
- [How to Run](#-how-to-run)
- [Key Insights](#-key-insights)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 🔥 Project Overview

This project focuses on analyzing and preparing **Indian Election Data** to:
- Clean messy real-world datasets.
- Understand voting patterns across gender and reservation categories.
- Prepare for further advanced electoral data analytics.

---

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** - For data manipulation and preprocessing
- **Jupyter Notebook** - For interactive exploration

---

## 🧩 Project Workflow

1. **Data Importing** 📥
   - Load the election dataset (`Indian_election_dataset.csv`).

2. **Data Cleaning** 🧹
   - Drop irrelevant columns: `pc_no`, `pc_name`, `partyabbre`.
   - Remove duplicate entries.
   - Rename columns for better readability.
   - Convert year to integer type.
   - Handle missing values in `reservation_category`.
   - Standardize gender representation (`F` ➔ `Female`).

3. **Exploratory Data Analysis (EDA)** 🔎
   - Sampled random entries to check data quality.
   - Analyzed distribution across states, genders, reservation categories.

---

## 📁 Dataset Details

The dataset includes:
- **State name**
- **Candidate gender**
- **Party affiliation**
- **Total votes polled**
- **Winning status**
- **Reservation categories**
- **Election year**

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/aure-lius/indian-election-analysis
   ```

2. Navigate to the project directory:
   ```bash
   cd election-data-analysis
   ```

3. Install necessary dependencies:
   ```bash
   pip install pandas jupyter
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## 📈 Key Insights

- Uttar Pradesh has the highest number of political parties participating in elections, followed by Bihar and Maharashtra.

- Indian National Congress historically dominated the elections, followed by Bharatiya Janata Party (BJP) and Bahujan Samaj Party (BSP).

- Total voters based on gender show that:

    Male voters significantly outnumber female voters across all years.

    A small number of voters are categorized under "O" (other/unknown gender).

- Voter turnout over years has been consistently increasing, indicating growing electoral participation.

- Reservation categories such as SC, ST, and OTHERS have seen steady representation in the total voter base over the decades.

---

## 🎯 Future Enhancements

- Analyze winning margins across states.
- Visualize trends using interactive dashboards (Plotly, Dash).
- Predict candidate winning chances using Machine Learning models.

---

## 👩‍💻 Author

- **Your Name**  
  [GitHub Profile](https://github.com/aure-lius)

---

⭐ If you liked this project, consider giving it a star! ⭐