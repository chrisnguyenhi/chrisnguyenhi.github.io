---
layout: project
type: project
image: images/output.png
title: Brunel Visualizations
permalink: projects/brunelvis
date: 2016
labels:
  - Java
  - Brunel
  - HTML
  - CSS
  - JavaScript

summary: A series of data visualization project in Java using the Brunel Visualization grammar made as a personal side-project.
---
A Java and Brunel powered data visualization of employment by college major from 2011-2012.
The [dataset](https://raw.githubusercontent.com/fivethirtyeight/data/master/college-majors/all-ages.csv) contained the employment status and college major of college graduates of all ages from 2011-2012. 

From this dataset, a bubble chart sorted by employment number and colored by major category (Computers & Mathematics, Education, Engineering, etc.) was made using the Brunel language. 

This program is written in Java using Brunel 2.0. After compiling, the program creates an HTML file containing the visualization results. The larger the bubble, the higher the employment number is for each major. 

<img src="/images/output.png" width="700" height="500">

A similar data visualization was made in ``marvel.java`` with a different and larger [dataset](https://raw.githubusercontent.com/fivethirtyeight/data/master/comic-characters/marvel-wikia-data.csv) containing the information of Marvel Characters scraped off [Marvel Wikia](http://marvel.wikia.com/wiki/Marvel_Database). 

<img src="/images/large.png" width="800" height="600">


This visualization was a bubble chart of appearances colored by the character's allignment (good, evil, neutral, and ?). The larger the bubble, the more the number of appearances.

For more information and the code repository, please check out the Github link below! 

Source: <a href="https://github.com/chrisnguyenhi/brunelvis"><i class="large github icon"></i>BrunelVis</a>
