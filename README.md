
# Netflix Visual Analytics Dashboard

This repository contains a Tableau dashboard project that explores the Netflix content catalog using visual analytics.

## Repository Contents

- netflix_titles.csv – Raw dataset downloaded from Kaggle
- data_preprocessing.ipynb – Python notebook used to clean and restructure the dataset
- netflix_data.xlsx – Final structured dataset with 3 sheets: movies, directors, actors
- Tableau Dashboards (.twbx) – Multiple interactive dashboards exploring various themes

## Data Preparation Workflow

The raw dataset was processed using data_preprocessing.ipynb:
- Cleaned missing values in key fields (director, cast, country, rating, etc.)
- Extracted main_genre, duration_value, and duration_type
- Converted date_added to datetime and derived year_added and month_added
- Normalized multiple actors and directors into separate rows
- Output saved as netflix_data.xlsx

## Dashboards Overview

1. Netflix_Content_Overview.twbx  
   Type distribution, genre mix, rating spread, upload trends, country-level stats

2. Duration_Insights.twbx  
   Histogram and box plot of movie durations across genres

3. Genre_Analysis.twbx  
   Most popular genres, genre vs rating heatmap, and regional genre breakdown

4. Geographic_Distribution.twbx  
   Top content-producing countries with bar and map visualizations

5. Director_Trends_Explorer.twbx  
   Most prolific directors, genre specialization, and director activity timeline

6. Director_Region_and_Ratings_Distribution.twbx  
   Directors segmented by country and content rating

7. Actors_Popularity_and_Roles.twbx  
   Actor frequency, genre preferences, and year-wise participation

8. Actor_Audience_and_Region_Analysis.twbx  
   Actor distribution across maturity ratings and countries

9. Netflix_Cast_Creator_Overview.twbx  
   Combined insights of actor-director collaborations, genre overlaps, and timelines

## Tools Used

- Python (Pandas, Jupyter Notebook)
- Tableau Public/Desktop

## How to Use

1. Open any .twbx file in Tableau Public or Tableau Desktop
2. Interact with filters and charts to explore trends by genre, year, country, rating, actor, and director

## Attribution

- Dataset Source: Netflix Titles – Kaggle
- Dataset link: https://www.kaggle.com/datasets/shivamb/netflix-shows?select=netflix_titles.csv
- Created by: Anagha Raveendra
