---
layout: essay
type: essay
title: Cool Coding
date: 2017-01-09
labels:
  - Software Engineering
  - ICS314
---
Since I was a freshmen in Computer Science, I've always wondered how people coded "professionally." To elaborate on this question, I was curious as to how the coding conventions I did in school differs from the coding style from professional software engineers and professional software developers. <br><br>
I knew that it was important to comment my code so that others see what my methods return and whatnot. I knew that for Java, constants should be in CAPS (like ```public static final int SPEED```), and I knew that all "normal" variables start with lower case (like ```public int conversionFactor```). <br><br>
It wasn't until I took ICS 314 (Software Engineering) that I found out about "coding standards" or the way "cool people" code (and by cool, I mean the people that work at [Google](https://github.com/google/styleguide) and in other professional environments).

## What are "coding standards"?
<img class="ui medium right floated image" src="../images/standards.png">
Coding standards are set rules and conventions that code must follow in order for it to be "standard." Some examples of popular coding standards for JavaScript are [Airbnb's](https://github.com/airbnb/javascript) and [Google's](https://google.github.io/styleguide/jsguide.html) style guides.<br><br>
Some common coding conventions defined in these guides are variable declaration. <br>
For example, in both Airbnb's and Google's JavaScript style guides, it the use of ```var``` and encourages the use of ```let``` for variables that will be reasigned and ```const``` for variables that won't be assigned. <br><br>

## How to use coding standards?
For JavaScript, a coding standard and style guide's rules can be implemented and "enforced" by linting utilities such as [ESLint](http://eslint.org/) and [JSHint](http://jshint.com/). Whenever a piece of code doesn't follow a set style guide's rules, an error or "red-swiggly" will appear.<br><br>
<img height=500 width=500 src="../images/lint.png">
These linting utilities can be thrown onto an IDE like [IntelliJ IDEA](https://www.jetbrains.com/idea/) or a text editor like [Sublime Text](https://www.sublimetext.com/). Some IDEs won't allow the code to run if it does not follow the specified coding standard.<br><br>

## How helpful are coding standards?
Based on what I have experienced so far in ICS 314 with coding standards, I definitely feel that coding standards can help a programmer learn a language and utilize that language in the most efficient way possible. <br><br>
Anyone can write a for-loop like ```int i = 0; i < someNumber; i++)``` in any programming language like C++ or Java, but certain coding standards and style guide's like [Airbnb's](https://github.com/airbnb/javascript#iterators--nope) discourage the use of iterators and encourage the use of high-order function like ```for-in``` and ```for-of``` to go through arrays and objects. 








Coding standards are something that simply cannot be enforced but rather emphasized. Ultimately, I feel that the question of whether or not to follow a coding standard is up to the programmer (or rather where the programer works at or if the specific project the programmer is doing requires a certain standard of code).

## My Github experience
As someone who has used the configuration management in the form of Github for two years, I feel that Github is a very useful tool. During my sophomore year, when I was first introduced to Github and git in a professional environment at [Blue Startups](http://bluestartups.com/), I found that it was a very useful tool for me to collaborate with other software engineers, software developers, and a UI designer in my team. It also proved very handy in a scrum-agile development environment. 
<br><br>
Configuration management is awesome. It allows anyone to work on their code from anywhere. I could be working in the US and push my code to Github and then work on it three weeks later in Vietnam. It's just that awesome. Because of Github's huge user base and its commitment to open-source development, it has become an industry standard. Nowadays, every resume has Github profile on it-- from seasoned professionals to young college students.

<img class="ui medium left floated image" src="../images/repo.png">
From using Github for two years, I have never had any problems using configuration management aside from pushing into the wrong branch. Know which the correct branch to push a collaborative project to is important. 
<br><br>
Although it is easy to uncommit changes and roll back to a previous commit like nothing happened, it becomes a huge hassle to do so on large scale development teams. While using Git on the command is great for complex operations, [Github Desktop](https://desktop.github.com/) provides an easy way for users to merge and deploy projects on a GUI. 
<br><br>

## Conclusion
In short, Github is a wonderful hosting service that allows users to share their code and allow for collaborative development.<br>
With its growth and features, it is not rare to see a Git repository link on a techical resume as it has become an industry standard in the field of software. <br>
It is something that should be in every software developer or software engineer's toolkit. <br>


