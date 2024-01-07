# Predicting the Likelihood of Winning in DoTA 2

## Game Overview:
Dota 2, short for Defense of the Ancients 2, is a multiplayer online battle arena (MOBA) game developed and published by Valve Corporation.
It stands as one of the most popular and enduring titles in the genre, known for its complex gameplay mechanics, strategic depth, and a massive, passionate player community.

## Game Strategy:
The game revolves around two teams of five players each, who compete to destroy the opposing team's Ancient, a heavily guarded structure located within their base. The strategic depth of Dota 2 lies in team composition, itemization, map control, and the coordination of complex strategies among teammates.
Hero selection in Dota 2 is a critical aspect that significantly influences the outcome of a game. The game's roster boasts over 120 heroes, each with unique abilities, attributes, and roles. The selection of heroes not only reflects individual player preferences but also plays a pivotal role in shaping team dynamics and strategy.However there are many other aspects of the game such as teamwork, adaptablity,strategy and the skill-levels of the players which have a larger impact than hero selection, which makes it difficult to predict the winner from hero selection alone.

## Prjoect Details:
In this project I attempted to predict the winners of a match of dota based on their hero selections, i.e which playable characters they chose in the match. This is a binary classification problem. I tried and compared different classification models like Logistic Regression, Naive Bayes and Random Forest Classifiers. 
The dataset I used is present in this repository and was sourced from [here](https://archive.ics.uci.edu/dataset/367/dota2+games+results).

## Result:
Model | Accuracy | Precision | Recall | F1 Score
| --- | --- | --- | --- | --- |
Logistic Regression | 0.58020 | 0.59759 | 0.65722 | 0.62598
Naive Bayes | 0.54688 | 0.58650 | 0.51636 | 0.54920
Random Forest | 0.55815 | 0.57400 | 0.67248 | 0.61935
