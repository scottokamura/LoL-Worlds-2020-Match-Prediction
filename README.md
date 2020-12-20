# 2020 League of Legends World Championship Tournament Match Winner Prediction

## Introduction
### Objective

League of Legends is an online multiplayer game with 115 million active players as of October 2020. The professional League of Legends esport has grown all over the world with major companies such as SK Telecom (the largest telecommunications company in South Korea) and NBA franchises like the Golden State Warriors and the Houston Rockets investing in North American teams. The world championship tournament boasts a total prize pool of $2.225 million with additional sponsorships from companies such as MasterCard, State Farm, and Louis Vuitton. In this project, I am attempting to use match data collected during the summer season playoffs as well as the round-robin phase of Worlds to predict the winner of the tournament's knockout stage.

### Summary of Approach
1. Determine the target audience
    - fans who want to accurately predict who may win the tournament, based on data
    - coaches to see the most important features/stats that will win games
2. Clean dataset
   - drop outliers
   - transform data if necessary (log, squared, etc)
   - condense data so each entry represents a match between 2 teams
       - including stats for each respective team
   - create dataframe with average stats over x games
   - check and correct correlating columns
3. Identify categorical and continuous variables
   - create dummy variables for categorical variables
4. Create pipelines for different models
    - compare baseline model results
5. Parameter tuning
    - use GridSearchCV to determine best parameters for each model
6. Compare models post-grid search
    - use accuracy, f1, auc scores to determine best model

### Methods and Technologies Used
1. Python libraries
2. Pandas, numpy
3. Matplotlib, seaborn
4. Scikit-learn, xgboost


## How to Use Repository
1. Fork and clone this repository
2. Open 'LoL Worlds 2020.ipynb'

### Additional Contents
1. Slide deck presentation ('presentation.pdf')
2. Related blog on     (https://scottokamura.github.io/data_science_non-technical_skill_slideshows)
3. Data taken from Oracle's Elixir (https://oracleselixir.com/tools/downloads)
