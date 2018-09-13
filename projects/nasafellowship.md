---
layout: project
type: project
image: images/lro.jpg
title: NASA Fellowship Project - Diviner Mapping
permalink: projects/nasafellowship
date: 2017
labels:
  - Python
  - AWS
  - Multiprocessing
  - NASA
summary: NASA Space Grant Fellowship Project to map potential ice deposits using data from the Lunar Reconnaissance Orbiter (LRO).
---

On the moon, there are regions that are cold enough to host long-lasting deposits of water ice. These regions with long-lasting water ice deposits are known as “cold traps.” Throughout my Fall 2017 and Spring 2018 fellowship period, I worked with Diviner data from the NASA Lunar Reconnaissance Orbiter.

Diviner is a NASA instrument that measures day and night surface temperatures of the lunar surface.
Since July 2009, the Diviner has produced one dataset for every 10 minutes of every day with each data file containing 800,000+ lines of data.
The goal of my project was to create scalable tools that read and process temperature data in parallel, so scientific analysis can proceed more rapidly.

<img src="/images/lro.jpg" width="700" height="400" class="ui huge floated rounded image">

Thanks to the funding and support from the NASA Space Grant program, I was able to use multiple Amazon Web Services cloud configurations to host Diviner data.
In addition, I used Python multiprocessing modules to allow parallel reads to Diviner data and reduced I/O operations by 85% (6570 hours per year of data).
Along with creating data processing tools to work with Diviner data, I also created maps of peak temperature based on a larger dataset to visualize where cold traps can be found on the Moon.

<img src="/images/lrocomp.png" width="700" height="400" class="ui huge floated rounded image">
<br><br>

  <div class="ui message">
    <div class="header">Cold trap comparison for 2009 (left) and 2010-2016 (right). The cold traps in the 2009 temperature map are larger than the ones from the 2010-2016 temperature map.</div>
  </div>


Ultimately, I was able to achieve a 28MB/sec read time with my data processing tools and discovered that the cold traps on the Moon are shrinking.
Based on a comparison and visualization of peak temperatures on the Moon from 2009 and 2010-2016, it was evident that cold traps on the Moon shrink with time.
Smaller cold traps imply that the temperature of the Moon has been increasing as the moon undergoes small orbital changes (lunar precession) every year.

This project has taught me the importance using multiprocessing and writing efficient code to decrease bottlenecks and costs because of the large volume of data the Diviner produces daily.
In addition, I also developed my project management skills as I had complete control of the project timeline, scope, and cost constraints to ensure monthly project progress and delivery.
