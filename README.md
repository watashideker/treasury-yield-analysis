# Treasury Yield Analysis: Relationship with Macroeconomic Indicators

This repository contains an analysis of U.S. Treasury yields in relation to key macroeconomic indicators across three major economic events: the Dot-Com Bubble (1997–2004), the 2008 Financial Crisis (2006–2010), and the COVID-19 Pandemic (2019–2024). The study compares these periods to a relatively neutral period (2013–2018) to explore how Treasury yields respond to economic shocks and recoveries.

## Project Overview

The study examines:
- **Treasury Yields**: Short-term (6-month), medium-term (5-year), and long-term (10-year) yields.
- **Macroeconomic Indicators**:
  - Gross Domestic Product (GDP)
  - Inflation (CPI)
  - Federal Funds Rate
  - S&P 500 Index
  - Unemployment Rate

The analysis highlights:
- The influence of economic crises and policy interventions on Treasury yields.
- Predictive relationships between yields and macroeconomic indicators.
- The role of Federal Reserve policies in stabilizing financial markets.

## Methodology
1. **Data Collection**:
   - Sources: Federal Reserve Economic Data (FRED) and Yahoo Finance.
   - Data includes Treasury yields and key macroeconomic indicators.

2. **Analysis**:
   - Exploratory Data Analysis (EDA) to identify trends and anomalies.
   - Correlation analysis to evaluate relationships between variables.
   - Regression models (linear, lasso) and decision tree models to predict yields.

3. **Comparative Study**:
   - Comparisons across crisis periods and the neutral period (2013–2018) for insights into temporal variations.

## Key Findings
- **Dot-Com Bubble (1997–2004)**:
  - Yields dropped sharply during the market crash but gradually recovered with Federal Reserve rate hikes.
  - Strong correlation between yields and the Federal Funds Rate.
- **2008 Financial Crisis (2006–2010)**:
  - Historic lows in yields during the crisis due to rate cuts and quantitative easing.
  - Unemployment and inflation showed significant influence on medium- and long-term yields.
- **COVID-19 Pandemic (2019–2024)**:
  - Yields declined due to uncertainty but rebounded during recovery phases.
  - High volatility in short-term yields reflecting rapid policy changes.
- **Neutral Period (2013–2018)**:
  - Stable economic growth resulted in steady yield increases and weaker relationships with predictors.

## Repository Structure

.
├── data/
│   ├── treasury_yields.csv      # Processed Treasury yields data
│   ├── macro_indicators.csv     # Macroeconomic indicators
├── scripts/
│   ├── data_preprocessing.R     # Data cleaning and transformation
│   ├── correlation_analysis.R   # Correlation matrix generation
│   ├── regression_models.R      # Regression and decision tree models
├── results/
│   ├── figures/                 # Plots and visualizations
│   ├── tables/                  # Model summary tables
├── README.md                    # Project overview and instructions
├── LICENSE                      # License for the repository
Getting Started
Prerequisites
Programming Language: R
Libraries: quantmod, tidyverse, caret, randomForest
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/Treasury-Yield-Analysis.git
Install necessary R packages:
R
Copy code
install.packages(c("quantmod", "tidyverse", "caret", "randomForest"))
Usage
Load data using scripts in the data_preprocessing.R.
Run correlation and regression analysis scripts.
Visualize results using the figures/ folder.
Authors
Swapnil Pant
Hao Cai
Satvik Gurjar
License
This project is licensed under the MIT License.

Acknowledgments
Data sourced from FRED and Yahoo Finance.
Stevens Institute of Technology for academic guidance.
