Premier League 16/17 Performance Analysis
Project Overview
This repository contains a Jupyter Notebook that analyzes a dataset of football matches. The goal is to uncover insights into team performance, venue impact, and defensive/goalkeeping efficiency using match-level statistics and betting odds data.

Key Features
Data Cleaning: Handling null values, removing redundant columns, and formatting date/time data for analysis.

League Table Generation: Automated calculation of total points (3 for a win, 1 for a draw) to reconstruct the final league standings.

Home vs. Away Analysis: Comparison of team performance depending on whether they played at home or away.

Defensive Metrics: Calculation of "Defense Efficiency" by analyzing goals conceded relative to shots on target faced.

Goalkeeper Analysis: Evaluation of keeper performance based on the average number of shots on target required to concede a goal.

Betting Data Exploration: Segmentation of match statistics from betting market data for specialized analysis.

Insights from the Analysis
Winner & Relegation: The analysis confirms Chelsea as the league winners, with Hull, Middlesbrough, and Sunderland relegated based on the points calculated from the dataset.

Goalkeeper Upgrades: Based on the efficiency metrics calculated in the notebook, the data suggests that top teams like Liverpool and Manchester City were underperforming in goal during this specific season relative to the shots they faced.

Technologies Used
Python 3.x

Pandas: For data manipulation and points calculation.

Seaborn & Matplotlib: For creating heatmaps and performance visualizations.

Jupyter Notebook: Environment for the analysis.

Installation & Usage
Clone this repository.

Ensure you have the required libraries installed:

Bash

pip install pandas seaborn matplotlib
Place the football.csv dataset in the project directory.

Open and run football analysis edited.ipynb in your Jupyter environment.

Dataset Description
The analysis uses a CSV file (football.csv) containing various match statistics including:

Full-time and half-time results.

Match stats: Shots, Shots on Target, Corners, Fouls, and Cards.

Betting odds from various bookmakers (Bet365, Pinnacle, etc.).
