# Analysis_Everpeak_

Urban Mobility & Economic Productivity Analysis in LATAM

📌 # Project Overview

This project analyzes the relationship between urban mobility and economic productivity in major Latin American (LATAM) cities. Using traffic congestion and economic indicators datasets, the study explores whether mobility conditions such as congestion, travel delays, and traffic intensity are associated with economic performance indicators like GDP per capita, unemployment, and population.

The main objective is to identify which cities may present stronger opportunities for future investment in transport infrastructure based on mobility efficiency and economic productivity.

🎯 # Objectives
Clean and prepare urban mobility and economic datasets.
Analyze traffic congestion patterns across major LATAM cities.
Explore the relationship between mobility indicators and economic productivity.
Visualize trends and correlations between traffic and economic variables.
Generate a clean and reproducible dataset for future analysis.

📂 Datasets Used
1. TomTom Traffic Dataset

Contains urban mobility and traffic congestion metrics, including:

Traffic Index
Traffic Delay
Traffic Congestion Levels
Jam Length (km)
Jam Count
Update Time

2. OECD City Economy Dataset

Contains economic and demographic indicators such as:

GDP per capita
Unemployment percentage
Population
PM2.5 air pollution levels
Year
🛠️ Technologies & Libraries

The project was developed in Python using the following libraries:

pandas
numpy
matplotlib
seaborn

Environment:

Jupyter Notebook

🔄 Project Workflow

1. Data Loading & Exploration
Imported mobility and economic datasets.
Reviewed data structure, columns, and data types.
Identified missing values and formatting inconsistencies.
2. Data Cleaning & Preparation
Standardized column names using snake_case.
Converted date columns to datetime format.
Corrected numeric columns stored as strings.
Filtered records for the year 2024.
3. Mobility Analysis
Calculated annual traffic averages by city.
Measured congestion and delay patterns.
Identified the cities with the highest congestion levels.
4. Data Integration
Merged mobility and economic datasets using city and year as keys.
Created a unified dataset for analysis.
5. Visualization & Insights

Generated visualizations including:

Boxplots
Histograms
Scatterplots
Comparative city charts

These visualizations helped identify trends between congestion levels and economic indicators.

📊 Key Findings
Mexico City presented the highest average traffic congestion among the analyzed cities.
No strong linear relationship was observed between GDP per capita and traffic congestion.
Some cities with high GDP per capita showed low congestion levels, while others presented severe mobility problems.
Certain lower-income cities also experienced high congestion, suggesting that mobility challenges are influenced by multiple factors beyond economic productivity.
