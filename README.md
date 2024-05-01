# Exploratory Data Analysis in Python using pandas


## Overview
This repository contains a Jupyter notebook where Exploratory Data Analysis (EDA) is performed using pandas. The dataset used consists of web scraped NBA player statistics from the 2018-2019 season.

## Data Source
The data was scraped from [basketball-reference.com](https://www.basketball-reference.com/leagues/NBA_2019_per_game.html) and includes the "2018-19 NBA Player Stats: Per Game" data.

## Data Retrieval and Cleaning
The following steps were taken to retrieve and clean the data:

1. Data was retrieved from the provided URL using pandas.
2. Data cleaning was performed to remove unnecessary rows and columns.
3. Missing values were replaced with 0.
4. The 'Rk' column was dropped from the DataFrame.
5. The cleaned data was saved to a CSV file named 'nba2019.csv'.

## Analysis
Several analyses were conducted on the dataset, including:

- Reviewing data dimensions.
- Checking for missing values.
- Overview of data types.
- Finding players with the highest points per game (PTS), three-point field goals per game (3P), and assists per game (AST).
- Identifying players who scored more than 20 points per game.
- Finding the player with the highest points per game for the LA Lakers.

## Usage
You can run the provided Jupyter notebook to reproduce the analysis or use the cleaned dataset for further analysis.

## Dependencies and tools
- python
- pandas
- Jupyter Notebook
- matplotlib
- seaborn

## Author
Andrea Anom

---



