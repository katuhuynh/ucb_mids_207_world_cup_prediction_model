# FIFA World Cup 2026 Prediction Model

## Overview

This project aims to build a machine learning model to predict match outcomes and tournament progression for the 2026 FIFA World Cup. By combining historical World Cup performance, international match results, and Elo ratings, we seek to develop a data-driven framework for forecasting team performance and simulating tournament outcomes.

## Objectives

- Predict the outcome of the current 2026 World Cup matches.
- Estimate the probability of teams advancing through each tournament stage.
- Simulate the full 2026 FIFA World Cup tournament.
- Identify the most influential factors driving international football success.

## Data Sources

### 1. FIFA World Cup Historical Data

Source: https://github.com/jfjelstul/worldcup

Key datasets:
- `matches.csv`
- `teams.csv`
- `tournaments.csv`
- `tournament_standings.csv`

These datasets provide historical World Cup match results, tournament information, and final standings.

### 2. International Football Results

Source: https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017

Key datasets:
- `results.csv`
- `shootouts.csv`
- `goalscorers.csv`

These datasets contain over a century of international football matches, enabling the creation of team form, head-to-head, and scoring-related features.

### 3. Elo Ratings

Source: [https://www.eloratings.net](https://www.kaggle.com/datasets/saifalnimri/international-football-elo-ratings)

Key dataset:
- `eloratings.csv`

Elo ratings provide a quantitative measure of team strength and are expected to be among the strongest predictors of match outcomes.

## Repository Structure

```text
.
├── data/
│   ├── matches.csv
│   ├── teams.csv
│   ├── tournaments.csv
│   ├── tournament_standings.csv
│   ├── results.csv
│   ├── shootouts.csv
│   ├── goalscorers.csv
│   └── eloratings.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│
