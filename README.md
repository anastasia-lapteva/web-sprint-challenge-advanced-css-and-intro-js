# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from an object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Responsive Design, and JavaScript Basics.


## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with.

### Commits

Commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe accessibility on the web to someone new to programming?

Accessibility is the practice of making your websites usable by as many people as possible. This includes: people with visual impairments using a screen reader, people with hearing impairments using text alternatives, people with mobility impairments using keyboard accessibility over a mouse, people using mobile devices, people with slow network connections, etc.

2. Talk about 3 different things you can do to ensure your website is accessible. 

3 different things you can do to ensure website accessibility are: (1) use semantic HTML, (2) include proper alt text for images, and (3) give links unique and descriptive names.

(1) Utilizing semantic HTML helps screen reader users to navigate content.

(2) Utilizing alt text for images allows screen reader users to understand the message conveyed by the use of images on the page. An exception to this rule is when an image is used purely for decoration. In this scenario alt text can be left empty so that the screen reader user is not distracted from important content on the page.

(3) Utilizing unique and descriptive names for links allows screen reader users to scan for links. According to a google search, screen reader users often do not read the link within the context of the rest of the page. Using descriptive text properly explains the context of links to the screen reader user. For example, instead of saying "<Click here> to read about our company" you could say "To learn more about our company, read <About Us>" In this example I'm putting the links in angle brackets.

3. How would you explain the concept of a variable to someone new to programming?

I would explain that variables are containers that hold information. Their purpose is to label and store data that will be referenced and manipulated by a computer program. Much like "x" is a variable in math, "x" can be used as a variable in programming. What's even more helpful is that the programmer can use a descriptive name as a variable, so the program can be understood more clearly. For example, instead of using "x" as a variable, the programmer can use "firstName" as a variable. "firstName" is a placeholder that has a descriptive name, making it easy to understand that first names should be plugged into this variable.

4. What is the purpose of using functions in code?

Functions are a good alternative to having repeating blocks of code in a program. It is a portion of code that can be used over and over again. Values can be passed to a function using variables. Functions can also return values.

5. How do you access a key inside of an object inside of an array?

You can access a key inside of an object inside of an array using: (1) dot notation, or (2) bracket notation.

(1) Dot notation: array[index].key; array[index].method();

(2) Bracket notation: array[index]['key']; array[index]['method()'];

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

[X] 1. Fork the repo
[X] 2. Clone your forked version of the repo
[X] 3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
[X] 4. open the terminal in your vs code and type `npm install`
[X] 5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Ensure your website is responsive at 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.



## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

🦄 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-2-Study-Guide-16f656025c8744458addb068e6348101)


## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)


