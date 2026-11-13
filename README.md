# Clustering Basketball Players by Performance Metrics

Unsupervised learning in R to group NBA players by their statistical profiles and see which metrics separate different player types.

## Overview

Coaches and analysts look at points, rebounds and assists, but similar players are hard to spot by eye. We clustered 50 NBA players from the 2023 season to find groups with similar profiles and identify the statistics that drive the split.

## What I did

- Standardized 6 variables for 50 NBA players in R, including an engineered points, rebounds and assists (PRA) metric, and explored distributions and correlations with summary statistics and visualizations
- Applied K-means and hierarchical clustering, selecting 2 clusters with the elbow method, and both methods produced identical groups separated mainly by minutes played, points and PRA

## Methods and tools

R, dplyr, corrplot, feature engineering, standardization, K-means clustering, hierarchical clustering, elbow method.

## Files

| File | Description |
|---|---|
| [code/basketball_clustering.ipynb](code/basketball_clustering.ipynb) | Notebook with the full analysis (R kernel) |
| [code/basketball_clustering.py](code/basketball_clustering.py) | Text export of the notebook |
| [docs/report.pdf](docs/report.pdf) | Project report |

The notebook reads `nba_players_2023.csv`, a table of season statistics for 50 NBA players. The file is not included here.

## Team

Batuhan Ok, Ceren Balay, Melek Melisa Akay, Doğa Güz, Necati Deniz Talay

ISE 412 Data Science for Industrial Engineers, Yeditepe University, Fall 2024. Assistant Prof. Dr. Emre Çelebi.
