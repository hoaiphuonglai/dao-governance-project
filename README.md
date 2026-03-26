# DAO governance-project
## Overview
This repository contains the code, data, and analyses conducted as part of my research on governance in Decentralized Autonomous Organizations (DAOs). The project investigates under what conditions DAO governance becomes more centralized, despite their decentralized design, using Ethereum-based DAO data and applying frameworks from Transaction Cost Economics (TCE).

The repository includes scripts for data collection, processing, and analysis of DAO governance proposals, voting behavior, and participation patterns.

## Repository Structure
```
code/
├── dao-data-scraping/            # Submodule: scripts to collect DAO governance data from Ethereum
├── blockchain-sentiment/         # Submodule: sentiment analysis on DAO discussions
├── analysis/                     # R scripts for econometric models and analysis
    ├── fixed_effects/            # Fixed effects and fractional logit models
    ├── mixed effects/            # Beta regression analyses
│   └── visualization/            # Graphs, plots, and summary tables
├── data/                         # Raw and processed datasets
```
## Key Contributions
1. **Data Collection** 
- Structured DAO data for analysis of proposal characteristics, uncertainty, participation, and voting concentration.

2. **Analysis**
- Examined the relationship between asset specificity, uncertainty, and governance centralization.
- Applied Transaction Cost Economics (TCE) to interpret DAO governance choices.
- Implemented fixed-effects, hierarchical, and mixed regression models to study DAO participation dynamics.
- Performed sentiment analysis on DAO discussions using forum and social media data.

3. **Insights**
- Empirical evidence on how certain conditions influence the degree of decentralization in DAOs.
- Evaluation of methodological choices for measuring decentralization and participation.
