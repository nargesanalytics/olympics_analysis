# Olympic Games EDA

## Overview
This repository contains an Exploratory Data Analysis (EDA) exercise on 120 years of Olympic games data (1896 to 2016). The dataset includes information about athletes, their performances, and medal results.


## Environment

This project was developed using the Kaggle environment. You can find the original Kaggle notebook [https://www.kaggle.com/code/nargeshaghparast/olympics]



## Dataset
I'll be working with the athlete_events.csv file, where each row corresponds to an individual athlete competing in an Olympic event.
The dataset includes information such as athlete details, team, NOC code, year, season, sport, event, and medal results.

## Objective
Examine and clean the dataset.
Explore distributions of single numerical and categorical features through summary statistics and visual plots.
Investigate relationships between multiple features using statistical analysis and visualizations.

# Getting Started
## Prerequisites
Python (or any preferred programming language for data analysis)
Pandas, Matplotlib, Seaborn libraries
Jupyter Notebook (optional) 

## Installation
- pip install matplotlib , seaborn,  pandas

## Exploratory Data Analysis
- Data Examination and Cleaning: Open and explore the dataset, document any cleaning steps taken.

- Single Feature Distributions: Analyze and visualize distributions of single numerical and categorical features. Use summary statistics, histograms, and bar plots.

- Relationship Exploration: Investigate relationships between multiple features. Utilize scatter plots, box plots, and correlation analysis to understand patterns and trends.

## Usage
Provide information on how others can use your EDA findings. Include code snippets for loading the data into a Pandas DataFrame and running the analysis.
- import pandas as pd
- import seaborn as sns

# Load dataset
- df = pd.read_csv('athlete_events.csv')

# Acknowledgments
- Original dataset source: 120 years of Olympic history
