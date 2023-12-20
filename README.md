Welcome to my Repository for my analysis on predicting KPI of professional soccer players!

There are 3 total Jupyter Notebooks for this project:

1. KPI_Prediction_Analysis.ipynb: This notebook created to perform separate machine learning algorithms, one for each position group in soccer: Attackers, Midfielders,
   and Defenders. These models utilized player data that was prepared in Data_Preparation.ipynb. Models created with the intention of predicting a selected KPI for specific
   player roles. Then, SHAP values were utilized to investigate feature importance and determine most influential features for each player position.

2. fbref_scrape.ipynb: Script created to scrape in-game statistics on professional soccer players from Fbref.com.
   Data from past three seasons was collected of players from 17 top professional soccer leagues around the world.

3. Data_Preparation.ipynb: This notebook merged player information dataset with scraped data from fbref_scrape.ipynb to prepare data for ML analysis.
   Also prepared the data by combining datasets containing information on individual seasons. Removed any redundant/unnecessary features and converted total
   count features to "/90" (Ex: Gls -> Gls/(number of 90s played)) where 90 minutes is considered a full game.

I have also included a slide show containing a summary of the project.
