---
layout: post
title:  "Is the Academy Awards Biased?"
date:   2022-11-18
author: Emily Sainsbury
description: Exploratory Analysis of Actors Nominated For Academy Awards
image: /assets/images/film-stocks.jpg
---

# Overview

In my most recent post, I explained that I would be doing an analysis on actors who have been nominated for Academy Awards. This dataset contains nominations for lead and supporting roles in motion pictures, and includes the number of nominations and wins for each actor. It does not list the year or film for every single nomination or win. Instead, it lists the year and film for the first time the actor was nominated. If they have won a nomination it will list the year and film for the first time they won and award. 

# A Few Quick Figures

The actor who has won the most Academy Awards is Katherine Hepburn, with 4 wins (from 12 nominations). 

The actor with the most nominations is Meryl Streep, who was nominated 21 times and won 3 times. 

The youngest actor to be nominated was Justin Henry, who was 8 years old at the time he was nominated. The youngest actor to win was Tatum O'Neal, who was 10 years old at the time she won.

This list has a total of 954 actors, with roughly 50% being male and 50% being female. As a note, there is one transgender actor in this list. At the time of their nomination they identified as female, and since they now identify them as male I've listed them as male for this analysis. 

# What Are We Looking For?
Below are the questions I hope to answer in my analysis:

What is the effect of gender on number of nominations/wins?

What is the effect of age* on the number of nominations/wins?

What is the effect of number of nominations on number of wins?

*Age at first nomination 

# Exploratory Analysis

I haven't done any deep analysis yet, but I've plotted a few things that will give us an idea of what the data has to tell us. First, lets look at the effect that gender has. 

## Gender

First I wanted to know if more female actors have been nominated in recent years than at the beginning of the academy awards. I've found this to not be the case. As shown in the chart below, the spread and mean of birth years are roughly the same for male and female actors. Note that the oldest birth year for an actor nominated for an Academy Award was a woman, who is May Robson born in 1858. 

INSERT IMAGE HERE

Are more nominations given to men or women? The answer is again no, as shown by the charts below. We can see that the spread is roughly the same for men and women.

INSERT IMAGE HERE

## Age

It makes sense that the younger you are the first time you're nominated for an award, the more likely you are to have more nominations in total over the course of your career. Let's see if this is the case.

INSERT IMAGE HERE

As we can see, actors who are nominated for the first time around their 20s to 40s seem to the be most likely to have a high number of nominations. We can also see actors are nominated as young as 8 years old to in their 80s. It looks like no matter how old someone is, they could still get nominated for an Academy Award. 

Let's take a look at that same chart, but we'll distinguish between men an women and see if there's a trend. 

INSERT IMAGE HERE

Just by eyeballing it, it looks like women are more likely to get their first nomination at a younger age than men. The average age at first nomination overall is 38. For just men it's 41 and for just women it is 35. In further analysis I will test to see if the difference is significant. 


## Number of Nominations

Does getting nominated more often make you more likely to win? Meryl Streep might argue no, since she's been nominated nearly twice as many times as Katharine Hepburn, yet Hepburn still has more wins. Let's see what the data has to say. 

There are usually 5 nominations per winner, meaning that if you've been nominated you probably have 4 competitors, giving you a 20% chance. Is that truly the case? Possibly.

Let's look at it this way: only about 32% of actors who have been nominated have won an award. So you could say that the odds of you winning if you've been nominated are 1 in 3.

If we only look at actors who have one at least once, the average number of times that they have been nominated is 2.6 times. 







