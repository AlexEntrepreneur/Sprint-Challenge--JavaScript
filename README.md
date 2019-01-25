# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.
* `.forEach` iterates over a list and applies some operation with side effects to specified members of that list.
* `.map` creates a new list of the same size as the list it is called on, iterates over that list and transforms each member of that list in a specified way.

2. What is the difference between a function and a method?
* A function is code that performs operations on data. It has inputs (parameters and variables), can cause side-effects and can return outputs.
* A method is a function that is associated with some object. It is able to operate on data that is contained within the object.

3. What is closure?
* Closure is any function that exists inside (enclosed by) another function.

4. Describe the four rules of the 'this' keyword.
* Default Binding - When a function containing "this" is invoked globally, "this" will refer to the global "window" object or will be undefined in "use strict" mode.
* Implicit Binding - When a function is a method of some object, "this" will refer to that object when the function is invoked as a method.
* NEW Object Binding - When a constructor function is created and "this" is used in the body of the constructor function, "this" will refer to any object that is newly created from the constructor class.
* Explicit Binding - When an object is bound to a function using exampleFunction.bind(Object) and that function is called e.g. boundFunction(), "this" will refer to the specified "Object" passed to the bind method.

5. Why do we need super() in an extended class?
* Calling super() allows attributes from the parent class to be passed to the extended class. It passes the parent class's `this` and can pass specified attributes from the parent class.

### Git Set up

* [x] Fork the project into your GitHub user account
* [x] Clone the forked project into a directory on your machine
* [x] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
* [x] You are now ready to build this project with your preferred IDE

## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays.
* [x] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope.
* [x] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [x] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [x] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
