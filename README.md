# calculator-js

This is my take on the calculator as a part of the curiculum of The odin Project.

Main logic:

global variables:
firstNum = ""
secondNum = ""
result = ""
operator = ""

// Event listener on buttons => poulate display with,
// Store Display Value in firstNum

// Event listener on operators:
// if operator = "" (which at first will be the case) : transfer value of num1 to num2, then empty num1 and set operator as e.target
// Store again firstNum from the display
// At this point firstNum, secondNum and operator have correct values. => perform operation => store in variable result => store in secondNum so that once operation is finished, the next one can be chained on the result of the previous one

Had real fun with this project! A lot of edge cases to pay attention to, once basic functionality is implemented.

//// CODE REFACTOR UPDATE (CLASS)
After completing The Odin Project's chapter about classes I decided to revisit my calculator and try to refactor the code in order to make it cleaner, organise my code better and to implement an interface using classes.

I find that the code is indeed better organised and much easier to understand, but I could't impact edge cases as much as I did in my first project. Will try to revisit when I get more experience with classes.
