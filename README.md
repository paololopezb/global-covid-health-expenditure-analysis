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

- `data/`: dataset used in the analysis
- `notebooks/`: Jupyter notebook for EDA and modeling

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- CatBoost

## Modeling Note

The modeling section in this notebook is exploratory. It is intended to examine associations between variables and should not be interpreted as a causal or production-ready predictive system.

## Author

Paolo Lopez
