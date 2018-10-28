# NBA Players of the Week - Exploratory and Explanatory Visualizations
Created: 10/27/2018<br>
Latest Update: 10/28/2018<br>
By: Can Bekleyici - bekleydata.com<br>

## Introduction
For this project, I explored a <a href="https://www.kaggle.com/jacobbaruch/nba-player-of-the-week">dataset from kaggle</a>, which contains every Player of the Week awarded between the NBA seasons 1984/85 and 2017/18. After shortly assessing and cleaning the dataset, I started exploring the data by using a variety of visualisations and techniques (as feature engineering). Upon finishing the exploration, I polished the visualizations for presentation purposes and turned them into slide decks.

## Key Findings
The visual exploration of the dataset revealed, that players in the position of a guard have been chosen the most times as 'Player of the Week' in the NBA. The body mass index (bmi) of each awarded player have been the highest on average for Forward-Centers and the lowest on average for Shooting-Guards. Players that have been drafted more recently tend to have a higher bmi on average than players that have been drafted 10-50 years ago. Despite the overall trend of higher bmi's for the high performing players, the bmi's of Guards (G), Centers (C), and Power-Forwards (PF) have actually decreased more recently.

## Prerequisite
### Files that are included (among others):
<ul><li><code>nba_data_exploratory.ipynb</code> - The main code for this project as a jupyter notebook</li>
  <li><code>nba_data_explanatory.ipynb</code> - A polished version of the main code with explanatory visualizations</li>
  <li><code>nba_data_explanatory.slides.html</code> - A Slide Deck for this project</li>
  <li><code>environment.yaml</code> - The environment file for this project</li>
  <li><code>requirements.txt</code> - All packages and their versions listed in a txt-file</li>
  <li><code>NBA_player_of_the_week.csv</code> - Original dataset from kaggle</li>
  <li><code>output_toggle.tpl</code> - A script for hiding code in the nbconvert slide decks</li></ul>

### Installation:
In order to run the project on your local <code>Anaconda</code>, download all the files and run `nba_data_exploratory.ipynb` on your jupyter notebook. Note that in order to run all the cells, you will have to fill to respective parts with your own twitter api keys.

### Without Installation:
You can just view the complete analysis and the used code from the included HTML files `nba_data_exploratory.html` or from the built-in ipynb reader in github without any prerequisitions.
