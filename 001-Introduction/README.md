## 🔗 Introduction to JavaScript 
JavaScript is a powerful, versatile programming language primarily used to bring web pages to life by adding interactivity such as dynamic graphics, interactive forms, and real-time content updates. It was created in just 10 days in 1995 by Brendan Eich while he was working at Netscape Communications. Today, alongside HTML and CSS, it operates as one of the three core technologies of the World Wide Web and has expanded beyond the browser to power servers and mobile applications.

```javascript
console.log("Welcome to Javascript"); // It print the javascript on the Browser
 ```

## 🔗 Variables 
Variable are the Label Boxes which helps to Store the Information, For Example: a = 20 then a is a variable where a is storing the number or a is storing the 20 on it. There are three types of Variable 
i.e let, var and const.

```javascript
let currentScore = 0;     // We use let because the score will change
const playerName = "Sam"; // We use const because the name stays the same
currentScore = 10;  // Updating the score later in the game
```

## 1.  Declaration And Initialization

1. Declaration 

Declaration is the process of registering a variable name within a specific scope (like a function or a block). At this stage, you are telling the JavaScript engine: "I’m going to need a box with this name."
Syntax: You use keywords like var, let, or const.
The "Undefined" State: If you declare a variable with var or let but don't give it a value, JavaScript automatically assigns it the value of undefined.\

```javascript
let score; // Declaration
console.log(score); // Output: undefined
 ```
2. Initialization

 Initialization is the process of assigning an initial value to a variable for the first time. This is the moment you actually put something inside the "box" you created.

Syntax: You use the assignment operator (=).

```javascript 
score = 100; // Initialization
```



## 🔗 Comments

In JavaScript, comments are notes you leave in your code for yourself or other humans to read. The computer completely ignores them when running the program. They are incredibly useful for explaining what a complex piece of code does, leaving reminders, or temporarily turning off a piece of code while you are trying to fix a bug.

There are the two types of comments in javascript:

1. Single-line Comments

This comments is used in a just single line and it is represents by //.

```javascript
let currentScore = 0;     // This is a Single Line Comments.
```

2. Multi-Line Comments

If you have a longer explanation or want to disable a large chunk of code, use /* to start the comment and */ to end it. Anything between those symbols is ignored, even if it spans across many lines.

```javascript
/* This is a 
Double line comments */
```


