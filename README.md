# International Football Tactical & Home-Advantage Analytics (2000–Present)

**Module 05: Data Science Mini Project** | Codomax Digital Solutions Data Science Internship

## Overview
An end-to-end exploratory and statistical analysis of over 20,000 modern international football matches using a real-world public dataset (`martj42/international_results`). Rather than stopping at descriptive counts, this project tests home-field advantage statistically and applies K-Means clustering to segment national teams into tactical tiers.

## Key Findings
- **Quantified Home Advantage:** Teams playing in true home venues win significantly more often than designated "home" teams at neutral venues ($p < 0.001$ via Welch's t-test).
- **Competitive vs. Friendly Dynamics:** Competitive tournament matches exhibit noticeably lower scoring rates than international friendlies, reflecting tighter defensive structures.
- **Tactical Team Clustering:** K-Means segmentation on goals scored per game, goals conceded per game, and win rate cleanly partitions national sides into four distinct performance tiers.

## Tech Stack
- **Data Manipulation:** Pandas, NumPy
- **Statistical Testing & ML:** SciPy (`ttest_ind`), Scikit-learn (`StandardScaler`, `KMeans`)
- **Visualization:** Matplotlib, Seaborn

## View the Notebook
- **Interactive / Full Outputs:** [Open in Google Colab](https://colab.research.google.com/github/CodeWizPri/football-match-efficiency-analysis/blob/main/football_analytics_mini_project.ipynb)
