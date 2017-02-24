---
layout: essay
type: essay
title: Connecting U and I with UI Frameworks
date: 2017-02-23
labels:
  - UI Frameworks
  - Software Engineering
  - HTML
  - ICS314
---

<img class="ui large left floated image" src="../images/ui.png">

UI Frameworks definitely make life a lot easier. For a developer like me who does not prefer to spend hours and hours on resizing circles or creating icons on Photoshop, UI Frameworks are the way to go. Some popular UI Frameworks include [Twitter Bootstrap](http://getbootstrap.com/2.3.2/), [Materialize CSS](http://materializecss.com/), and [Semantic UI](http://semantic-ui.com/). To start talking about UI Frameworks, it is important to talk about what an UI, what a UI framework is, and what's great about UI Frameworks (in this case for the front-end). Actually, this entire page and site is powered by the UI framework, Semantic UI-- a framework that uses natural language to make code "self-explanatory."

## So what is a UI? 
UI stands for User Interface. UIs are what allows the user and a computer system to interact with each other. Someone who is doing [User Interface Design](https://www.usability.gov/what-and-why/user-interface-design.html) implies that he or she is designing an interface that can allow users or clients to interfact with a system or software easily and intuitively.

## So what are UI Frameworks? 
The technical definition of a framework (or more specifically, a [software framework](http://info.cimetrix.com/blog/bid/22339/What-is-a-Software-Framework-And-why-should-you-like-em)) is similar to a library. A software library contains objects and methods that can be instantiated and used in a custom application. Of course, you need to know which objects to instantiate and which methods to call. A framework, allows the user to implement the objects and methods that are custom to his or her application and they are instantiated and invoked by the framework. This makes life way easier because instead of making objects and icons from scratch, a front-end UI framework can allow users to easily do things like resize images, rotate icons, or divide a page up to columns (or at least with Semantic UI anyway). <br><br>
<img class="ui medium right floated image" src="../images/icons.png">
From the perspective of someone who is purely a software engineer or software developer with minimal design experience, UI frameworks allow users to be able to roll out awesome looking websites and applications without the need to focus on CSS stylesheets too much. This gives software engineers and software developers more time to focus on the pure action, functionality, and features as opposed to worrying about resizing a background image on photoshop and throwing it into the code. <br><br>
Several UI frameworks ui frameworks actually have built-in code for icons to allow users to make social media buttons easily without having the need to worry about resizing the icon on any external photo editor. With one line of code, someone can just make a Facebook icon or Amazon icon easily. The cool thing I have found with certain front-end UI frameworks is that some of them are mobile-responsive, so users will not need to worry about radically changing the content in their code and making three versions of the same site for a desktop computer, a smartphone and an iPad. 

## What is Semantic UI?

I have rotated through frameworks here and there but I have never used Semantic UI before taking ICS 314 (Software Engineering). Semantic UI from my experience is an easy-to-use UI framework for the front-end that allows for easy front-end development with its intuitive code base and natural language usage. It is also pretty easy to install on the [NPM](http://semantic-ui.com/introduction/getting-started.html).

## What is this "natural language" you speak of?

<img class="ui large left floated image" src="../images/natural.png">
One of the things that Semantic UI is known for is natural language. The classes in Semantic UI uses syntax from natural languages like noun/modifier relationships, word order, and plurality to link concepts intuitively. If you want a button, you can just use the ```ui button``` class to create a button. Yep. It's just that easy. Plus it looks pretty nice.<br><br>


## Learning UI Frameworks 
Like learning a new library or a new programming language, learning a new framework can be extremely hard. It is definitely a struggle to find out which methods lead to what, but so far Semantic UI's idea of having classes using natural language syntax makes it a lot easier to use this framework to its full (or 3/4's) capacity.  
<br><br>
So why take the time to learn a UI framework? Well, you could argue the time that it takes for a developer to spend on learning a new framework could be the same or less than the time it takes to do the same thing using just pure HTML, CSS, and JavaScript. So ultimately, it all depends on the person. Personally, I am not skilled in Photoshop nor want to muck up things in my stylesheet to fix up an icon or image, so for me, I would want to take the time to learn a UI framework to use less Photoshop as possible.
<br><br>
As a software engineering student that has used Semantic UI and heavy HTML, CSS, and JavaScript in the past for front-end development, I can see why UI frameworks exist. Given the opportunity, I would definitely want to spend the least amount of time as possible on creating a user interface and still want it to look cool and engaging. Semantic UI is something that is definitely useful for front-end development due to how "readable" and "straightforward" the code is thanks to natural language.


##




One of key comparisons that people make with JavaScript with how different it is to Java. The first thing that sticks out to me is declaring variables.

In Java, declaring a string and an integer looks like this:
<br>
```
int myInt = 10;
String myString = "This is Java.";
```
<br>
While doing the same thing in JavaScript looks like this: 
<br>
```
let myInt = 10;
let myString = "This is JavaScript."
```
<br>
Notice how in Java, the variables need to be specified as a String and an int while in JavaScript, we can use let for both a string and an integer. As a programmer who started off with C and Java, this is mindblowing (though I guess the people who started off with [Fortran](http://www.fortran.com/) felt the same way when they first tried Java). 

In a way, being able to declare variables like this is pretty cool because it allows the programmer to skip the small details and focus on the logic of their code. The only thing they would have to worry about is whether or not their variables are ``const`` (constants) or not. As a side note, you'll probably see a lot of JavaScript code online using ``var`` as opposed to ``const`` or ``let`` and this is can end up with errors in the long run according to the [AirBnB JavaScript guide](https://github.com/airbnb/javascript#types).

## JavaScript in ICS 314 (Software Engineering)

Although I have done work with JavaScript in the past by using several JavaScript-supported APIs, [ICS 314](http://courses.ics.hawaii.edu/ics314s17/index.html) was my first time formally learning the language in a classroom setting. From my first week in the class, I learned how to do a lot of new things in JavaScript such as creating an object and accessing its properties. Being able to quickly add a property to an object without making a new one with new parameters was also something new to me. 

In ICS 314, there is a WOD (Work Out of the Day) every week where students are challenged to code a solution to a problem within a certain amount of time-- something known as "Athletic Software Engineering." I enjoy doing WODs because it is good practice for future interviews and it gives me practice in a programming language I am learning. This style of learning may be a little stressful but it is enjoyable because it challenges me to understand a problem and find the best optimal solution-- much like those problems found on [LeetCode](https://leetcode.com/problemset/draft/) which sometimes show up on actual tech interviews. 

## Conclusion: Is JavaScript Good or Bad?

JavaScript is pretty great. The best part of it to me is being able to easily declare variables and access properties inside an object. JavaScript also has a variety of different uses from web development to game development. I remember an IBM recruiter at a career fair telling me to put JavaScript before Java on my resume because a lot of companies nowadays are looking for JavaScript. From a Software Engineering perspective, I feel that JavaScript has room to grow. It is a great language that can interact with other languages such as PHP and HTML. From my knowledge, I can't see anyone progamming applications to do things like contour detection or train a classifer but it seems to be getting on that level since people are doing things like [binding OpenCV](https://github.com/peterbraden/node-opencv) or making a [Deep Learning library](http://cs.stanford.edu/people/karpathy/convnetjs/). JavaScript is something I will definitely continue to learn.