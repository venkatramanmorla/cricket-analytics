📂 Dataset Description

This repository contains four Excel datasets (.xls files) generated during the web scraping, cleaning, and feature engineering stages of this cricket analytics project.
All datasets are stored inside the data/ folder.

1. men_players_raw.xls

Raw dataset scraped from the BCCI website for Men’s Players.

Includes:

Player name

Role (batter/bowler/all-rounder)

Batting statistics

Bowling statistics

Basic player details extracted directly from web pages

This is the initial unprocessed dataset.

2. women_players_raw.xls

Raw dataset scraped from the BCCI website for Women’s Players.

Includes:

Player profile details

Batting records

Bowling figures

Match-level performance data

Used along with men’s raw data for merging.

3. combined_cleaned_data.xls

This is the cleaned and merged dataset created by combining the men’s and women’s raw datasets.

Cleaning steps applied:

Removed duplicate players

Standardized column names

Fixed inconsistencies in role, team, and match fields

Handled missing or invalid values

Combined both datasets into one unified table

Used for univariate and bivariate analysis.

4. added_features_odi_stats.xls

The final feature-engineered dataset used for EDA and visual insights.

Added features include:

Strike Rate Category

Batting Average Category

Experience Level (based on matches played)

Matches Played Grouping

Derived performance ratios

This dataset is used for correlation analysis, multivariate visualizations, and generating insights.
