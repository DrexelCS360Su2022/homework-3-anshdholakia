# CS 360 Project 1 Part I: The Metacircular Evaluator

Collaborators:

Please put anything else you would like us to know here.

## Problem 5: Homework statistics

Please let us know how much time you spent on each problem. You may enter time using any format described [here](https://github.com/wroberts/pytimeparse).

Problem 1: 45 mins
It took sometime to go over the program and look at each function. Doing so, it took a lot of time and effort. But after going over each function, I got to understand that adding the symbols to the list of primitives will do the job. But for the last (error) part, I was having some trouble and aborting the evaluator after printing the message. But I did that by just printing the message as we had to abort the evaluator but not the program.

Problem 2: 30 mins
This was quite easy but the add function was tricky since the last element which was not evaluated had to be printed out. After some trials and watchign the flow of the evaluator, I created two base cases that could exit when the list was about to go null.

Problem 3: 1h40m
This took a lot of time as we had to keep on sending the first elements of the list till we reach the end i.e. the procedure. I made two functions, get-vars and get-vals to get a list of the variables and values. After that, 

Problem 4: 2h30m
In this question, I thought to make a delay function which would return a lambda procedure that would not be evaluated. Then I made a force function that evaluated the lambda. The reasons it took a while is because I tried to make the delay function take in parameters whereas I had to make it return a lambda function which takes in the parameters instead