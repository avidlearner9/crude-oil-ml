# crude-oil-ml
Machine learning analysis of crude oil market regimes and volatility using market, energy fundamental, and macroeconomic data
## Overview

This project investigates the application of machine-learning methods to crude-oil market analysis, with a focus on volatility forecasting and market trend identification.

This analysis will combine historical WTI crude-oil prices with energy-market fundamentals and macroeconomic indicators to examine whether these variables contain useful information about future market conditions.

## Research Questions

Can machine-learning models improve forecasts of short-term crude-oil volatility relative to simple statistical baselines?

Can machine-learning methods identify meaningful regimes in the crude-oil market?

## Motivation

Over the past year, trading futures has given me first-hand exposure to the complexity and unpredictability of financial markets. Although the experience can be stressful, I have become increasingly fascinated by the difficulty of understanding why markets behave as they do and how rapidly conditions can change.

With plans to pursue further study in data science and machine learning, I wanted to use this project to challenge my technical abilities and investigate a subject I genuinely find interesting. Crude oil provides a relevant case given my experience with futures and previous academic exposure to energy markets. I want to explore whether machine-learning techniques can reveal useful patterns in volatility and market regimes, and whether those insights have practical value for understanding and managing market risk.

## Project Status

**Status: In Progress — October 2026**

### Completed
- Collected six datasets from the U.S. Energy Information Administration (EIA) and Federal Reserve Economic Data (FRED), spanning as far back as 70 years but most likely being restricted to around 30 years.
- Created a Jupyter notebook documenting data sources and initial inspection.
- Cleaned and validated WTI crude-oil prices and U.S. commercial crude-oil inventory data using Pandas.
- Standardised column names, converted data types and checked for missing values and duplicate dates.
- Exported cleaned datasets to `data/processed/`.

### In Progress / Planned
- Clean the remaining energy-market and macroeconomic datasets.
- Align daily and weekly observations into a consistent time-series dataset.
- Perform exploratory data analysis and visualise the relationships between all the datasets.
- Design features for market-regime identification and volatility analysis.
- Develop machine-learning models using chronological train-test splits and appropriate analytical comparisons.