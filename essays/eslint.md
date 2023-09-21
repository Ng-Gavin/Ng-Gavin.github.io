---
layout: essay
type: essay
title: "Importance of standards"
# All dates must be YYYY-MM-DD format!
date: 2023-09-21
published: true
labels:
  - Software Engineering
  - Reflection
  - Javascript
  - ESLint
---

<img width="200px" class="rounded float-start pe-4" src="../img/eslint/eslint.png">

## Hazards Without Standards

Being unable to read someone else’s code because of how disorganized it is sometimes makes it take more than double the usual amount of time needed to comprehend it. Additionally, this doesn’t only apply to code written by someone else. When I haven’t touched a piece of code I’ve written in a long time, I’ve probably forgotten much of how that code functions. Comments are great for getting a general idea of how it works but if I want to fully understand it again, I need to reread it line by line. Having inconsistencies in the formatting of the code or it being vastly different from how I currently format code, makes for an unpleasant experience.

## Standard Benefits

Coding standards are a great way to solve this issue. By implementing it as an industry standard, everyone’s code is formatted the same way. Also, having a coding standard ensures that formatting for all the code you write is consistent. This makes it easy to spot common patterns in code making the reading process faster. This allows someone to easily adapt the code as it’s written without taking time to reformat the code to meet the standard.

## Experiencing ESLint

The coding standard that I’ve started using recently is ESLint within the IntelliJ IDE. At first, it was a bit tricky getting my code to not trigger any errors enforced by the coding standard. Most of this was due to me coding differently and having my own way of writing code. Another issue was just not knowing the details of the ESLint coding standard. However, it got much easier as I played around with it and started writing more code with it.

## Additional Benefits

Another benefit of using IntelliJ with ESLint is that it not only shows me errors in my formatting but also triggers warnings of logical errors. What’s great about this is that it shows me these errors in the writing process without the need to compile and build the project first. A couple of great examples are that it will give me errors if a function doesn’t have returns in reachable places and will tell me if I have unused functions or variables. These are some great benefits when making code that might take a long time to compile and build.
