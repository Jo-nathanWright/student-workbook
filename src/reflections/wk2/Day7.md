# Day 7 - JAVASCRIPT FUNCTIONS, OBJECTS, AND LOOPS

## Daily Questions

- What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
    - Function name (parameters) {}
        - This is a hoisted definition
    - Let name = function (parameters) {}
        - Has no name
    - Let name = (parameters) => {} 
        - Has a shorter syntax

- What is the difference between Parameters and Arguments?
    - Parameters are the names created in the function definition and are used to define a function
    - Arguments are the values the function receives from each parameter whenever that function is called

- What are higher order functions? Can you provide an example?
    - When a function accepts another function as a parameter, or returns a function
    - Array.prototype.map