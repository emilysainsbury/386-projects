---
layout: post
title:  "Web Scraping in Python"
date:   2022-10-21
author: Emily Sainsbury
description: Extracting a table from the web
image: /assets/images/film-stocks.jpg
---

# Ethics
For this project, I wanted to pull data from Wikipedia since the information is open to the public. Since Wikipedia is so available to the public and I'm only pulling once for one table, I felt like I wasn't implementing any unethical webscraping practices.

# What We're Looking At
The dataset that I'm scraping contains infromation on every actor that has ever been nominated for an Academy Award. It has the number of nominations, number of wins, and the title of the first film they were nominated for. I love movies and thought this would be a fun dataset to explore.

In the link at the bottom of this post is my respository for this project. So far it just has the web scraping code and the dataset. 

# The Process
Reading in the data for this project was very simple. I'm using the pandas function "read_html()" to read in all the tables from the wikipedia page. Then, since I only wanted the second table on the page I selected that table and stored it as a dataframe. 

![Test Image](https://raw.githubusercontent.com/emilysainsbury/stat386-projects/main/assets/images/scrapingCode.png)


# What's Next
Moving forward I'm going to do an exploritory data analysis on this dataset. We'll see which actor has had the most nominations, the ratio of nominations to wins, and who has won the most awards. Should be interesting!
