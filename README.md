# Project Title: Wrangle and Analyze Data from [@WeRateDogs](https://twitter.com/dog_rates)

## Files
1. [Main Project File](wrangle_act.ipynb): Every data analysis step is documented in this file, from gathering data to analyzing and visualizing data
2. [Act Report](act_report.ipynb): This report contains a brief exploratory data analysis, based on three research questions and their respective visualizations
3. [Wrangle Report](wrangle_report.ipynb): In this document, there is a detailed walkthrough of my data wrangling efforts, which was the focus of this endeavor
4. `data/`: This folder contains the datasets used in the project, and a few screenshots from selected tweets I used in the Act Report.

## Description

This project was undertaken as part of Udacity's [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002).

For this project, the goal was to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning was required for "Wow!"-worthy analyses and visualizations.

For this project, the gathering data phase involved three datasets: 

1. `archive` table: contains the information WeRateDogs sent Udacity and I downloaded directly.

2. `fav_rt` table: contains the information I gathered from Tweepy. Namely, tweet ID, favorite count and retweet count. 

3. `image_prediction`table: WeRateDog's tweets were processed through a neural network that can identify dog breed. This dataset was downloaded programmatically.
