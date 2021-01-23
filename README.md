# How does the COVID-19 pandemic affect the home advantage in the Premier League?

This notebook aims to analyze whether playing at home without a crowd is still an advantage. Besides stastical models, predictive models based on past performances were also applied to see how the results could have looked like if COVID had not happened.

All code is shown in the [jupyter notebook](https://github.com/christopherkindl/premier-league/blob/main/Home-advantage-in-football-during-covid.ipynb).

## Features for predicition:

- HTGD (Home team goal difference)
- ATGD (Away team goal difference)
- DiffFormPts (Difference in form points)
- DiffPts (Difference in points)
- HTWinStreak4 (Home team 4 win streak)
- HTWinStreak3 (Home team 3 win streak)
- ATWinStreak4 (Away team 4 win streak)
- ATWinStreak3 (Away team 3 win streak)
- HTLossStreak4 (Home team 4 loss streak)
- HTLossStreak3 (Home team 3 loss streak)
- ATLossStreak4 (Away team 4 loss streak)
- ATLossStreak3 (Away team 3 loss streak)
- DiffLP (Difference in last year's standing)

## Applied models:

- Logistic regression
- Random forest
- Support vector classifier (SVC) model
- Naive bayes model
