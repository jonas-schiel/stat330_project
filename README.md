# NCAA Basketball Win Percentage Analysis

## Overview
This project analyzes NCAA Division I men's basketball data (2013–2024) to identify 
which in-game statistics most strongly predict team win percentage. Using multiple 
linear regression and AIC-based best subsets selection, we developed a model with 
an adjusted R² of 0.82.

## Key Findings
- Defensive effective field goal percentage was the strongest predictor of win percentage
- Turnover rate and steal rate were also highly significant predictors
- The final model contained 9 predictors selected via AIC best subsets and 
  validated through cross-validation
- Applied to BYU's 2025 season: model predicted 77% win rate vs. actual 72%

## Methods
- Multiple linear regression (MLR)
- AIC and BIC best subsets selection
- LASSO regression
- Cross-validation for out-of-sample performance (PMSE)
- VIF analysis for multicollinearity diagnostics

## Files
- `stat330_proj.pdf` — Full written report with results and interpretation
- `analysis.R` — R code for data cleaning, modeling, and diagnostics

## Data
College Basketball Dataset compiled by Andrew Sundberg, available on Kaggle. 
Covers NCAA Division I seasons 2013–2019 and 2021–2025 (2020 excluded due to 
COVID-19).

## Authors
Jonas Schiel & James Rainey — BYU Statistics Department, April 2025
