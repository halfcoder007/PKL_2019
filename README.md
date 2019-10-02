# PKL_2019
Pro Kabaddi 2019

# Predict the winner of the tournament
Bengal Warriors

# Predict the the top team in the points table after the completion of league matches
Delhi Dabangs

# Predict the team with the highest points for successful raids
Delhi Dabangs

# Predict the team with the highest points for successful tackles
UP Yoddha

# Predict the team with the highest super-performance total
Bengal Warriors

# Predict the player with the highest SUCCESSFUL RAID percentage
Pawan Kumar Sehrawat

# Predict the player with the highest SUCCESSFUL TACKLE percentage
Nitesh Kumar	

# Data Sets used
1. Player_Stat_Season 7 : Player related stats for Season 7
2. Team_Stats_Season 7_30th morning : Team related data for all the Seasons 
3. 2019_Pro_Kabaddi : Season 7 match Results and Team Leaderboard
4. kabbadi_fixtures : Season 7 fixtures to predict the rest match results

# Data Cleansing and Preparation
1. Nulls were removed
2. Outliers were treated
3. Normalization were done
4. Dummy variables were created for categorical data

# Data Visualization
1. Data and Type driven plots were created.
2. Heatmaps were created to see the relationship of the variables

# Approach
1. Predict the Winner : Based on current seasons leaderboard and Head-Head collision results.
2. Top the Leaderboard : Current leaderboard position and matches left.
3. Team Total Successful raids/tackles : Current raids/tackles + Avg successful raids/tackles * Matches to be played(Based on prediction   which teams will play the playoffs and finals)
4. Player Successful raid/tackle % : Based on current successful raid/tackle % .Assuming the number of matches played doesn't make any impact as it is =  (No. of successfull raids/tacles) / (Total no. of raids/tackles) * 100

# Model Selection
For predicting match results we have taken in account the current season match results and wins of the team.
We have divided the dataset into Train and Test data set.
Since, predicting the match result is classification problem
We have tested the score with below models
1. Logistic Regression
2. Random Forest
3. Decision Tree

Based on the score we have selected Random Forest and predicted the match results of upcoming matches as well as playoff matches.


