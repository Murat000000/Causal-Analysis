# Causal Relationship Between Gross Savings and External Debt

## Overview
This project examines the causal link between domestic gross savings and external debt levels. Using panel data from 60 countries over a 27-year period (1996–2022), the analysis aims to determine whether higher domestic savings effectively reduce a nation's reliance on foreign borrowing.

## Objectives
The primary goal of this study is to answer the question: **Does higher savings reduce a country’s external debt?**

Specifically, we aim to:
* Analyze the elasticity between gross savings and external debt stocks.
* Control for confounding macroeconomic factors such as GDP, trade openness, and inflation.
* Isolate causal mechanisms using econometric modeling to account for country-specific heterogeneity and global economic trends.

## Data Source
The data is sourced from the **World Bank’s World Development Indicators (WDI)**.
* **Sample:** 60 countries.
* **Time Period:** 1996–2022.
* **Preprocessing:** Data includes log transformations to handle skewness and adjustments to constant 2015 USD for comparability.

## Methodology
The analysis is conducted using Python within a Jupyter Notebook environment. The empirical framework includes:
1.  **Fixed Effects Model:** To control for unobserved country-specific factors (e.g., culture, institutions) and time-invariant variables.
2.  **First Differences Model:** Utilized as a robustness check to examine how short-term changes in savings correlate with debt fluctuations.
3.  **Heterogeneity Analysis:** Investigating how the relationship differs between high-income and low-income economies.

## Repository Structure
* `da4assignment2.ipynb`: The main Jupyter Notebook containing data cleaning, regression analysis, and code for visualizations.
* `term.docx`: The final report containing the full theoretical background, literature review, and detailed interpretation of findings.
* `*.csv`: Raw data files and series metadata sourced from the World Bank.
* `1.png`, `2.png`, `3.png`: Generated visualizations (histograms and distribution plots) used in the analysis.
