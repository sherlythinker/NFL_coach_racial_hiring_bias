# What Race is Leadership?

This repository contains the data, code, and analysis for the project titled **"What Race is Leadership? A Statistical Approach to Evaluating Racial Equity in NFL Coach Hires"**. The project aims to uncover racial disparities in NFL coaching hires using advanced statistical methods.

## Project Overview

This study evaluates the effectiveness of the NFL’s Rooney Rule and explores systemic biases within coaching hires, focusing on three key hypotheses:
1. Career longevity is a strong indicator of coaching potential.
2. Career performance metrics are the best indicators of coaching potential.
3. Racial biases exist in the NFL's coaching hiring practices.

The analysis uses historical NFL data, which was cleaned and processed for the investigation. It also employs the **rethnicity** library to estimate racial identities based on names, and logistic regression models to predict coaching potential.

## Key Components

- **Data Cleaning and Processing**: JSON datasets converted to CSV format, aggregation of player performance metrics, and matching with coaching transition data.
- **Statistical Analysis**: Various statistical models were tested to identify the strongest predictors of coaching success. These models consider performance metrics such as career wins, losses, and ties.
- **Racial Bias Exploration**: Statistical methods are applied to compare the expected racial composition of coaches with the actual composition, highlighting underrepresentation of minority coaches.
  
## Methodology

The study includes:
- Data scraping from **Pro Football Reference** and processing through **Python scripts**.
- Application of **forward selection regression** to identify relevant predictors of coaching success.
- Imputation of racial identities using the **rethnicity** package.

## Key Findings

The study finds that career longevity is not a reliable predictor of a player's potential for coaching success, while resilience (measured by losses and ties) is a stronger indicator of that potential. The analysis also reveals significant racial disparities in the hiring of coaches, with a stark underrepresentation of Black coaches in the NFL.
