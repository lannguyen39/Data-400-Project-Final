# Data-400-Project-Final

# FROM STUDIO TO SCREEN:
Visualizing Anime Trends and Explaining the Unexpected
### By Lan Nguyen and Faye Le

## I. Introduction

Our group wanted to know whether the top 10000 anime has a trend in why some anime has a higher scoring than others, while trying to see if those factors predict can an anime has a higher score.

Here is what we did. 

## Dataset ##
The dataset is scraped from the website https://myanimelist.net/topanime.php. Dataset contain the top 10000 anime ranked on the 30th of October, 2024.


## Summary

### Numerical variable:
- Episode has no correlation with score or ranking.

### Categorical variable:

- F-Statistics Summary:
    - Genres: 27.51558

    - Type: 256.275017

    - Season: 2510.04939

    - Year: 181.525423

- Interpretation:
    - Strongest Predictor: Season (F-statistic: 2510.04939)

        - This indicates that the season in which an anime was released is the most influential predictor of its average score among the variables tested.

    - Weakest Predictor: Genres (F-statistic: 27.51558)

        - This suggests that the genre of an anime, while still statistically significant, has the least influence on its average score compared to the other variables.
     
### Limitation and implication:
1. Limitation:
The dataset has a limited number of variables, as well as the website constant ranking update. The dataset also did not contain information like comments, characters, and more; which could help predict the anime score better. There are also missing data throughout the dataset.

2. Implication
- For Anime Studios:
    - Rising competition: Newstudios producing high-quality anime signal increased fierce competition, requiring establised players to innovate to maintain market dominance.
- For Streaming platforms:
    - Predict Seasonal Demands: Fall and Spring dominate anime releases. Platforms can also optimize relsease schedule for these peak timeslot for maximum engagement.

