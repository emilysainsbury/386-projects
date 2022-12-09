---
layout: post
title:  "Academy Award Nominations: A Data Story"
date:   2022-12-8
author: Emily Sainsbury
description: 
image: /assets/images/1900.png
---

# The Project
For this project, I found a dataset on Wikipedia that contained all of the actors who have ever been nominated for an Academy Award. I love movies and so I thought this would be a fun and interesting dataset to dive into. This dataset had the name of the actor, their gender, birth/death year, age, number of nominations, number of wins, film name, the year of their first nomination, and the year of their last nomination. 

This dataset was a little tricky because it only contained one row per actor, rather than one row per nomination. This means that if an actor was nominated multiple times we only know the first winning film role or first nomination. It also made it difficult for me to use the column that gives details on whether the nomination was for a lead role or supporting role. 

I did some cleaning on this dataset and added a few more variables during my exploratory analysis. At first I wanted to do analysis on the relationship between number of nominations and number of wins. I wanted to know if there were actors that get repeatedly nominated but never seem to win. After my analysis, I found another feature of the data to be more interesting.

# The Story
In the Academy Awards, an award is always given to the best lead/suppporting actors, best lead/supporting actresses, and there are a handful of nominations for each to keep things fair. I find it fascinating the way that men and women are treated in the film industry, and so I wanted to see if the data showed different treatment across genders. Here's what I found:

![Test Image](https://raw.githubusercontent.com/emilysainsbury/stat386-projects/main/assets/images/output.png)

The blue dots represent a male actor, and the orange dots represent a female actor. At a glance, we can see that the orange dots are clustered to the left and blue dots are more on the right. The average age of a female actor at their first nomination is 35, and for male actors the average is 41. In general, female actors are more likely to be nominated for the first time when they are younger and male actors are more likely to be nominated when they are older. 


# Project Refrences

Click [here](https://github.com/emilysainsbury/ActorsWebScraping) to see my respository for this project.







