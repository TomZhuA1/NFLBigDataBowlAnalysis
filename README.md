# NFL Tackling Analytics

## Project Overview

This project focuses on analyzing NFL tackling data to gain insights into player and team performances. The analysis includes exploratory data analysis (EDA), player and team-level analysis, tackling type and success factors, and the development of new metrics to evaluate tackling efficiency.

### Data Sources

The analysis utilizes several datasets:
- `tackles.csv`
- `games.csv`
- `plays.csv`
- `players.csv`
- `tracking_week_{i}.csv` for weeks 1 to 9

Data is mounted from Google Drive and processed using Python libraries including Pandas, NumPy, Matplotlib, and Seaborn.

## Key Features

### Exploratory Data Analysis (EDA)
- Identification of unique games, plays, and players.
- Analysis of the distribution of tackles, assists, and missed tackles.
- Exploration of player heights, weights, and their correlation with tackling efficiency.

### Player-Level Analysis
- Calculation of tackling efficiency and ranking of players based on various metrics.
- Investigation into how player attributes like height and weight impact tackling efficiency.

### Team-Level Analysis
- Examination of tackling proficiency among different teams.
- Analysis of total tackles and missed tackles for each team.

### Tackling Type and Success Factors
- Study of different types of tackles (e.g., open field tackles, gang tackles).
- Classification of play types based on play descriptions.

### New Metrics Development
- Creation of a class `nflBigData` for advanced data analysis.
- Implementation of methods to calculate downfield speed, downfield acceleration, distance to ball carrier, and yards forward.
- Development of a custom metric to evaluate the importance of tackles (yards saved).

### Visualizations
- Numerous plots and visualizations to support the analysis, including histograms, scatter plots, and heatmaps.

### Comparative Analysis
- Comparison of traditional tackling efficiency with the new yards saved metric.
- Visualization of player performance metrics for better understanding.


