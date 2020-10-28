# Error Handling & Debugging

This chapters talks about The console & Dev Tools, Common Problems and Handling Errors. 

### Order of Execution
To find the source of an error, it helps to know how scripts are processed.  The order in which statements are executed can be comples; some tasks cannot complete until another statement or function has been run: 

### Execution Contents

### The Stack 
The JavaScript interpreter process one line of code at a time.  When a statement needs data from another function, it stacks (or piles) the new function on top of the current task. 

### Execution Context & Hoisting
Each time a script enters a new execution context, there are two phases of activity: 
  1)  Prepare
  2)  Execute

Understanding Scope
Understanding Errors
Error Objects
How to Deal With Errors
A Debugging Workflow
Browser Dev Tools & Javascript Console
How to Look at Errors in Chrome
How to Look at Errors in FireFox
Typing in the Console in Chrome
Typing in the Console in FireFox
Writing from the Script to the Console
Logging Data to the Console
More Console Methods
Grouping Messages
Writing Tabular Data
Writing on a Condition 
Breakpoints 
Stepping Through Code
Contitional Breakpoints
Debugger Keyword
Handling Exceptions
Try, Catch, Finally
Throwing Errors
Throw Error for NaN
Debugging Tips
Common Errors

## Summary Error Handling & Debugging
* If you understand execution contents (which have two stages) and stacks, you are more likely to find the error in your code. 

* Debugging is the process of finding errors.  It involves a process of deduction. 

* The console helps narrow down the area in which the error is located, so you can try to find the exact error. 

* JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 

* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.  Use them to give your users helpful feedback. 