### D Nicol homework ###

# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?

Debugging provides information at certain lines to determine what information is being made available at that point, this allows the user the opportunity to determine if it is running correctly at the point. The purpose of the breakpoint is to insert a point or line at which the app will pause and return the information needed to assess whats going on at that point.

2. Does the line of code on a breakpoint run when you start debugging?

No it pauses before what is in that line is ran.

3. How do we debug the next line of code?

To debug the next line of code you use the step over function in the debugger console which will take you down a line.

4. What does the step into command do?

Once the debugger has been ran it will highlight the line in blue and feedback information based on the values and properties. Should you wish to further investigate you use the step into command from the console. This command take you to where the error maybe. So in the example given the highlighted line is a method to deal the cards, the step into command takes us from the game test to the game class specifically where the deal method is called.

5. What is the difference between evaluate expression and evaluate code fragment?

The evaluate expression tool allows us to run and evaluate java code such as calling methods on instances of objects. The evaluate expression tool evaluates a single expression whereas the evaluate code fragment tools allows the user to add lines of code and run multiple lines with temporary variables 'live' to assess the outcomes.

### End ###
