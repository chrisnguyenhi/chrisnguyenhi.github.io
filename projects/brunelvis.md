---
layout: project
type: project
image: images/bruneldot.png
title: Brunel Visualizations
permalink: projects/brunelvis
date: 2016
labels:
  - Java
  - Brunel
  - HTML
  - CSS
  - JavaScript
  - Data Visualization

summary: A series of data visualizations in Java using the Brunel Visualization grammar by IBM.
---
This project is a series of data visualizations using the Brunel Visualization grammar. For this project, I acquired basic data visualization skills and learn how to use large datasets to answer questions such as "What is the Major with the highest employment numbers?" or "Which Marvel character has made the most appearances?" Being able to work with an open-source visualization library was also a major plus to me as well.

First, I created a data visualization of the employment number by college major from 2011-2012. The [dataset](https://raw.githubusercontent.com/fivethirtyeight/data/master/college-majors/all-ages.csv) (courtesy of [Five Thirty Eight](https://fivethirtyeight.com/)) contained the employment status and college major of college graduates of all ages from 2011-2012. 

From this dataset, a bubble chart sorted by employment number and colored by major category (Computers & Mathematics, Education, Engineering, etc.) was made using the [Brunel Visualization](https://developer.ibm.com/open/openprojects/brunel-visualization/) language for Java. 

The BrunelVis program I made creates an HTML file containing the visualization results once a CSV file is passed in. The larger the bubble, the higher the employment number is for each major. From here, we see that Business Management and Administration has the most employment. 

<img src="/images/output.png" width="700" height="500" class="ui huge floated rounded image">

A similar data visualization was made in ``marvel.java`` with a different and larger [dataset](https://raw.githubusercontent.com/fivethirtyeight/data/master/comic-characters/marvel-wikia-data.csv) containing the information of Marvel Characters scraped off [Marvel Wikia](http://marvel.wikia.com/wiki/Marvel_Database) courtesy of [Five Thirty Eight](https://fivethirtyeight.com/). 

<img src="/images/large.png" width="700" height="600" class="ui huge floated rounded image">

This visualization was also a bubble chart of appearances colored by the character's allignment (good, evil, neutral, and ?). The larger the bubble, the more the number of appearances. From here, we see that the top 3 characters who have made the most appearances are Iron Man, Spider Man, and Captain America. 

For more information and the code repository, please check out the Github link below! 

Source: <a href="https://github.com/chrisnguyenhi/brunelvis"><i class="large github icon"></i>BrunelVis</a>
