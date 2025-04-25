# Go/No-Go Test Error Rate vs. Daily Notification Load

## Project Overview
This project investigates whether the number of daily smartphone notifications affects cognitive control, specifically in the context of response inhibition measured through the Go/No-Go task. The main objective is to explore if higher notification load leads to a higher error rate and slower reaction times, indicating reduced inhibitory control.

## Motivation
In daily life, people are exposed to dozens or even hundreds of notifications, causing frequent task-switching and distractions. This study is motivated by the hypothesis that such interruptions could negatively impact cognitive functions like focus and self-control. The Go/No-Go test is used as a standardized tool to measure these effects.

## Objectives & Hypotheses

- To analyze the relationship between daily notification count and Go/No-Go task performance.
- To investigate whether higher notification loads are linked to increased error rates or slower reaction times.
- To explore whether there are any delayed effects (e.g., yesterday's notifications affecting today's performance).

### Hypotheses
- H₀: Notification count has no significant effect on commission error rate.
- H₁: Higher notification count is associated with increased commission error rate.

## Dataset Description

- **Notification Data**: To be collected using iPhone's Screen Time feature, aggregated on a daily basis.
- **Go/No-Go Test Data**: The task will be conducted using online tools such as PsyToolkit, Gorilla, or similar browser-based platforms that are compatible with Windows.
- **Additional Variables**: Self-reported mood score (1–5), Caffeine (mg)

## Planned Methodology

1. Daily logging of notification counts and test performance over 45 days
2. Data preprocessing, merging, and basic validation
3. Exploratory Data Analysis (EDA): distribution, trends, and correlations
4. Statistical analysis:
   - Correlation coefficients (Pearson, Spearman)
   - Linear and multiple regression models
   - Optional lag analysis (e.g., day t vs. day t+1)
   - Optional binary classification (e.g., high vs. low error days)

## Next Steps

- Set up data collection templates and scripts
- Start daily task tracking and logging
- Begin exploratory analysis after 1–2 weeks of data
- Progressively refine models with feedback and insights

## Tools and Environment

Data will be processed using Python and browser-based Go/No-Go tools

Analysis and visualization tools may include:
- pandas
- matplotlib
- seaborn
- scikit-learn
- scipy
Some of the workflow will be developed collaboratively with the assistance of ChatGPT
All code, documentation, and results will be organized and published via a GitHub repository

## Repository Structure (planned)

- `data` folder – processed CSV files (e.g., combined_data.csv)
- `notebooks`: data_process.ipynb(data conversion & merging) ,data_visualization.ipynb(EDA, visualization & hypothesis testing)
- `modeling.ipynb` – regression and classification models
- `README.md` – project documentation
- `requirements.txt` – dependency list
