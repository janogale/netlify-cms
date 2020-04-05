---
templateKey: blog-post
title: React Prerequisites and 4 ES6 Things to Know
posteddate: 2020-04-05T06:42:20.761Z
closingdate: 2020-04-05T06:42:20.804Z
description: >
  JavaScript has come a long way in the past decade, especially with the ES6
  update.
featuredpost: true
featuredimage: /img/es6.jpeg
tags:
  - ES6
  - React js
---
<!--StartFragment-->

Knowledge of ES6 is important when building React applications. ES6 brought a lot of cool syntax changes to JavaScript that make writing JavaScript much easier.

## [Terminal](https://scotch.io/starters/react/react-prerequisites-and-4-es6-things-to-know#toc-terminal)

In order to use the React CLI (create-react-app), it is encouraged to learn the command line. This is how we’ll start applications with create-react-app and also start development on our projects.

The main commands you’ll need to know:

* `ls`: list everything in your current folder
* `cd <name>`: choose a folder to go into
* `mkdir <name>`: create a folder

Here’s some good resources:

* [Codecademy](https://www.codecademy.com/courses/learn-the-command-line/lessons/navigation/exercises/your-first-command)
* [Galvanize](https://blog.galvanize.com/how-to-use-the-terminal-command-line/)

## [4 Main ES6 Features to Know](https://scotch.io/starters/react/react-prerequisites-and-4-es6-things-to-know#toc-4-main-es6-features-to-know)

While ES6 (JavaScript's major update in 2015) came with many syntax updates, there are**4 main syntax updates to know**that are used heavily in React.

## [1. let and const in addition to var](https://scotch.io/starters/react/react-prerequisites-and-4-es6-things-to-know#toc-1-let-and-const-in-addition-to-var)

Up until now, you would declare variables in JavaScript using`var`. ES6 introduced two new ways to declare variables with`const`and`let`. Here are the main differences:

* **const**: This variable**can not**be reassigned. JavaScript will throw an error if we try to reassign a new value
* **let**: This variable**can**be reassigned. This is similar to`var`

**Why does this matter?**`const`allows us to quickly see that a variable should stay constant; it will not be reassigned.`let`tells us that we are going to change the value of this. It gives a little more indicator of what the variable will do than`var`.

<!--EndFragment-->