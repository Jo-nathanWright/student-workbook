# Day 16 - INTRO TO ASYNCHRONOUS CODE

## Daily Questions
- What are some of the signs and causes of Callback Hell?
    - Signs:
        - Pyramid Shaped Code
        - The Last couple of lines of code are taken up by }).
    - Causes:
        - When you try to write `JS` in a way where execution happens visually from top to bottom.
- What does the asynchronous mean and how are callbacks involved?
    - `Takes some time`
    - Callbacks wait on that Asynchronous and then call the function

- Summarize the 3 ways to avoid / fix Callback Hell

    **1.** Keep Your code shallow
    - This means to spilt up your functions to be more readable and to call them correctly.

    **2.** Modularize
    - This is using the `JS module` system to seperate like code into differnet `JS Files` that call to each other.

    **3.** Handle every Error
    - This is having fall back errors that can go off when A code pulled doesn't return. Is useful due to the fact that it will not break the code, it will just shut down the section that didn't work.

## Afternoon Challenge
[Trivia](https://github.com/Jo-nathanWright/Trivia)