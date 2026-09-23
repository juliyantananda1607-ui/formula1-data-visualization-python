# Formula 1 Data Visualization with Python

## Project Overview

This project explores Formula 1 racing data using Python, with a focus on data exploration, data cleaning, and data visualization.

The dataset contains Formula 1 race information from 1950 to 2024, including race results, qualifying performance, circuits, drivers, pit stops, and lap times.

The main analysis focuses on the relationship between pole position and race victory, with the following research question:

> Does starting from pole position increase the likelihood of winning a Formula 1 race?

The project analyzes 305 races between 2010 and 2024 with complete qualifying and race result data.

---

## Objectives

The objectives of this project are:

1. Explore the structure and characteristics of Formula 1 data.
2. Identify missing values, inconsistent data types, and potential outliers.
3. Analyze pole position performance across different circuits.
4. Compare the top and bottom circuits based on pole position win rate.
5. Explore pit stop duration changes over time.
6. Calculate the overall relationship between pole position and race victory.
7. Communicate the findings through clear and interpretable visualizations.

---

## Dataset

The dataset contains several tables related to Formula 1 races.

### 1. Races Data

The races dataset contains information about Formula 1 race events.

Main columns:

```text
raceId
year
round
circuitId
name
date
time
url
fp1_date
fp1_time
fp2_date
fp2_time
fp3_date
fp3_time
quali_date
quali_time
sprint_date
sprint_time```

## Visualizations

### 1. Circuit-by-Circuit Pole Position Win Rate
### 2. Top 5 vs Bottom 5 Circuits
### 3. Pit Stop Duration Evolution Over Time
### 4. Overall Pole Position Win Rate
![Circuit Pole Win Rate](visualizations/circuit_pole_win_rate.png)

---

## Key Findings

The analysis covers 305 races from 2010 to 2024.

- 157 races were won by drivers starting from pole position.
- 148 races were won by drivers starting from a non-pole position.
- 51.5% of analyzed races were won from pole position.
- 48.5% were won from a non-pole starting position.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

formula1-data-visualization/
│
├── data/
├── notebooks/
├── visualizations/
├── README.md
└── requirements.txt

## Author

Ni Putu Juliyant Ananda Rika Pangastuti

Data Visualization with Python
