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

    Accessibility on the web- it's important to remember that just like programs, everyone is built differently. We want the widest audience of people to be able to access and use our creations and that can't happen if they can't interact with it the only way possible for them. So we need to make sure our code is semantic enough for screen readers to tell people with visual impairments what's going on, we need to make sure the colors we choose are accessible to individuals who use different colors on their monitors, we need to make sure that our text can scale so that people who need to increase font size can do that, we also need to make sure our site looks good no matter what screen size is being used. If we don't do those things we're cutting off a huge number of people from our products.

2. Talk about 3 different things you can do to ensure your website is accessible. 

    Ensure your HTML is as semantic as possible- using tags like address, h1-h6, p etc as opposed to calling everything as a div
    Ensure that you use scalable measurement in your CSS files- rems and % as opposed to px
    Include a meta tag in your HTML so that the browser reading your code can properly scale it

3. How would you explain the concept of a variable to someone new to programming?

    Variables are essentially the building blocks of everything we code. They're what we use to store values so that you can reference them at any point in your code. Everything is a variable. Your name is a variable which stores the 'value' of yourself. If someone wanted to talk to you, they use your name, your variable. It lets you know that you're expected to respond in some manner.

4. What is the purpose of using functions in code?

    Functions allow you to write a rule for a block of code without actually having it do anything until the function itself is called. They let you apply the same rule to any variable that has the arguments needed to fill the parameters set by the function, as opposed to writing the same block of code for every variable in your dataset.

5. How do you access a key inside of an object inside of an array?

    Dot Notation - array[index].object.key 
    Bracket Notation -  array[index].object['key'] (must be used if the key name has a space present)

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
NOTE: tests will run in the JavaScript portion of this challenge only.
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


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





