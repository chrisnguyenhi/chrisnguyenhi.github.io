---
layout: project
type: project
image: images/output.png
title: Brunel Visualizations
permalink: projects/brunelvis
date: 2015
labels:
  - Java
  - Brunel
  - HTML
  - CSS
  - JavaScript

summary: A series of data visualization project in Java using the Brunel Visualization grammar.
---
<img src="/images/output.png" width="700" height="400">

A Java and Brunel Visualization powered data visualization of employment by college major from 2011-2012.
The dataset contained the employment status and college major of college graduates of all ages from 2011-2012. 

Dataset courtesy of [FiveThirtyEight](https://raw.githubusercontent.com/fivethirtyeight/data/master/college-majors/all-ages.csv)

From this dataset, a bubble chart sorted by employment number and colored by major category (Computers & Mathematics, Education, Engineering, etc.) was made using the Brunel language. 
The larger the bubble, the higher the employment number is for each major.
<br>
This program is written in Java using Brunel 2.0. After compiling, the program creates a html file containing the visualization results. 
<br><br>
Brunel Command: <br>
``data('https://raw.githubusercontent.com/fivethirtyeight/data/master/college-majors/all-ages.csv') bubble color(Major_category) size(Employed) title("Employment by Major from 2010-2012") sort(Employed) label(Major) tooltip(Major, #all) legends(none) style('.header{fill: black} .background {fill:#eef2f3}')
``
<br>
<br>
A similar data visualization was made in ``marvel.java`` with a much larger dataset containing the information of Marvel Characters found on Marvel Wikia. This visualization was a bubble chart of appearances colored by the character's allignment (good, evil, neutral, and ?). The larger the bubble, the more the number of appearances.

Dataset courtesy of [FiveThirtyEight](https://raw.githubusercontent.com/fivethirtyeight/data/master/comic-characters/marvel-wikia-data.csv)

<img src="/images/large.png" width="700" height="800">

For more information and the code repository, please check out the Github link below! 

Source: <a href="https://github.com/chrisnguyenhi/brunelvis"><i class="large github icon"></i>BrunelVis</a>
