# global-covid-health-expenditure-analysis

# Global COVID-19 and Health Expenditure Analysis

This project explores country-level COVID-19 outcomes in relation to healthcare expenditure, income group, and regional differences. The analysis combines data cleaning, exploratory data analysis (EDA), visualizations, and an exploratory modeling section to study associations with deaths per million.

## Objective

The goal of this project is to examine how COVID-19 indicators vary across countries and to explore whether healthcare expenditure and other country-level variables are associated with different mortality outcomes.

## Dataset

- Source file: `data/covid.csv`
- Unit of analysis: country-level observations
- Main variables used:
  - total cases
  - total deaths
  - total cases per million
  - total deaths per million
  - healthcare expenditure
  - income group
  - country / regional indicators

## Project Structure

```bash
global-covid-health-expenditure-analysis/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── covid.csv
├── notebooks/
│   └── EDA_latest_covid_19.ipynb
└── images/
