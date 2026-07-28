# Project Bank

## A-Share Volume Factor Research

**Tools:** Python, pandas, NumPy, Spyder  
**Focus:** Factor engineering, information coefficient analysis, cross-sectional ranking, backtesting

- Investigated whether trading volume contains predictive information for future A-share excess returns.
- Constructed a log-volume factor from daily trading volume and standardized cross-sectional factor values using z-scores.
- Merged factor observations with 5-day and 20-day excess-return data by stock identifier and evaluated predictive relationships using correlation-based information coefficients.
- Ranked securities by factor values and compared top- and bottom-quantile returns in a simple long–short backtest.
- Documented a broader research workflow covering factor selection, multi-factor combination, portfolio construction, and performance evaluation.

### Limits and Defense

- Current evidence supports a learning/research prototype, not a production investment strategy.
- Do not claim out-of-sample profitability until time-series testing, transaction costs, survivorship bias, and look-ahead bias are addressed.
- Be ready to explain why log volume and z-score standardization were used.

## Exploring Global CO2 Emissions and Energy Trends

**Course:** STAT 436 Statistical Data Visualization  
**Tools:** R, Shiny, ggplot2, tidyverse  
**Data:** Our World in Data CO2 and Greenhouse Gas Emissions dataset

- Contributed to an interactive exploratory dashboard for comparing country- and region-level emissions and energy patterns across years.
- Worked with a dataset containing 50,411 observations, 79 variables, and records spanning 1750–2024.
- Designed a reactive bubble-scatter module in which year and metric selectors update the data, axis labels, included countries, fitted trend, and correlation summary.
- Added controls for comparing energy use per person, CO2 per person, population, GDP, and other measures while keeping the analysis descriptive rather than causal.
- Removed aggregate OWID rows, distinguished missing values from true zeros, and documented the 2023–2024 GDP-data availability gap.
- Coordinated module handoff through a standalone `app.R` for testing and a reusable module file for integration into the group application.

### Limits and Defense

- Do not imply causal effects between energy use, GDP, population, and emissions.
- Explain why aggregate regions were removed from country-level correlations.
- Explain Shiny reactivity: user inputs trigger filtered data, then plots and summaries re-render from the same reactive state.

## Brazilian E-Commerce Customer Satisfaction Visualization

**Tools:** R, tidyverse, ggplot2, patchwork  
**Data:** Olist Brazilian E-Commerce dataset

- Investigated the guiding question, “What factors drive customer satisfaction in Brazilian e-commerce?”
- Joined order, review, order-item, product, and product-category translation tables for analysis.
- Built a coordinated multi-panel visualization with consistent encodings and an integrated narrative rather than disconnected charts.
- Used annotations and panel layout to help viewers compare review outcomes with order and product characteristics.

### Limits and Defense

- Present findings as associations, not causal drivers, unless a causal design is added.
- Explain join keys, duplicate-order risks, and the unit of analysis.

## AI Emotional-Support Chatbot

**Program:** Alibaba Global Dreamer Program — AI Innovation Track  
**Tools:** Tongyi LLM, prompt and conversation-flow design, scenario labeling

- Built an AI-assisted emotional-support chatbot prototype around more than 500 labeled emotional-conflict scenarios.
- Connected user research and scenario taxonomy to prompt design, conversation flows, and iterative evaluation.
- Evaluated responses against project-defined user-experience criteria.

### Limits and Defense

- Do not claim that the model was trained from scratch.
- Do not present the product as medical or clinical care.

## Statistical Optimization Exercises

**Course:** STAT 305 R for Statistics III  
**Tools:** R, numerical optimization, gradient descent, Nelder–Mead, BFGS

- Implemented one- and multi-dimensional optimization workflows in R.
- Compared gradient descent, Nelder–Mead, and BFGS on a two-variable concentration surface and evaluated convergence behavior.
- Visualized objective functions and interpreted numerical solutions in the context of the underlying problem.

