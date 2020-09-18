# Mchezopesa-Football-Outcome-Prediction

# Overview

Mchezopesa Limited wishes to build prediction model to help with football predictions. The main focus shall be:
**Research Question:** Can we predict the result of a game between Team 1 and Team 2, based on which Team is playing at home or away, and on whether or not the game is friendly (include rank in your training).

The input for this analysis will include data on Home team, Away team, Tournament type (World cup, Friendly, Other)

The two possible approached while addressing this question shall include:
1. **Polynomial Approach** - Here we shall predict the number of goals by the home team scores and number of goals by the away team
2. **Logistic Approach** - Where we shall figure of from the home team's pespective whether a game is a Win, Loss or a Draw (W, L, D)

NOTE:
A more detailed explanation and history of the rankings is available here: https://en.wikipedia.org/wiki/FIFA_World_Rankings

An explanation of the ranking procedure is available here: https://www.fifa.com/fifa-world-ranking/procedure/men

## Dataset Columns

Some features are available on the FIFA ranking page here: https://www.fifa.com/fifa-world-ranking/ranking-table/men/

- Rank
- Country Abbreviation
- Total Points
- Previous Points
- Rank Change
- Average Previous Years Points
- Average Previous Years Points Weighted (50%)
- Average 2 Years Ago Points
- Average 2 Years Ago Points Weighted (30%)
- Average 3 Years Ago Points
- Average 3 Years Ago Points Weighted (20%)
- Confederation
- Date - date of the match
- Home_team - the name of the home team
- Away_team - the name of the away team
- Home_score - full-time home team score including extra time, not including penalty-shootouts
- Away_score - full-time away team score including extra time, not including penalty-shootouts
- Tournament - the name of the tournament
- City - the name of the city/town/administrative unit where the match was played
- Country - the name of the country where the match was played
- Neutral - TRUE/FALSE column indicating whether the match was played at a neutral venue


# Assessment Expectation

In order to work on the above problem, you need to do the following: 
1. Define the question, the metric for success, the context, experimental design taken and the appropriateness of the available data to answer the given question
2. Expected flow for the assessment:
- Perform your EDA
- Perform any necessary feature engineering 
- Check of multicollinearity
- Start building the model
- Cross-validate the model
- Compute RMSE
- Create residual plots for your models, and assess their heteroscedasticity using Bartlett’s test           
3. Perform appropriate regressions on the data including your justification
4. Challenge your solution by providing insights on how you can make improvements.

## Datasets
The data set used for this project has been included in the files uploaded

## Author
Qadipo
