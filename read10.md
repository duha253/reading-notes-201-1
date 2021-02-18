# Error Handling and Debugging Tips 

1- **Experienced developers use a variety of techniques to simplify their coding and maintenance efforts. Some of the tricks are general programming styles and conventions, while others are specific to the characteristics of Visual Basic (VB6) and Microsoft Office/Access VBA**.

Hopefully, by adopting such "best practices" techniques, you'll be able to write code that's easier to write, debug, and understand. Not only can you reduce bugs during development, you can also significantly reduce the effort required to replicate and fix bugs your users encounter.
A consistent coding style is critical for efficient application development in multi-developer environments. It also increases the chance that future developers can understand your work to fix or enhance it.

## Introduction

 ** Debugging is one of the most important skills for a developer. Software development is all about writing code, making mistakes, and fixing them. Strong debugging skills minimizes the development cycle by allowing developers to pinpoint bugs quicker, make fixes that actually address the problems encountered, and verify the modifications are correct. This is particularly important as the code gets more complex**.

Debugging doesn't end when the application is shipped. Having the proper error handling in place is critical to providing quick support when users encounter crashes. At the very least you want to verify it's a problem in your application, and if so, as much information as possible so you can minimize the need for user recall on how to reproduce the bug.

## Debugging Goals

1. Fixing Bugs
The most common use of the debugger is to diagnose the code when a crash is encountered. If no error handling is in place, when an Access application crashes, you or your user are prompted with an End, Debug message box
Analysis During Development
Another important use of the debugger is during system development to verify the code is working correctly even if a crash doesn't occur, or to narrow down the situations where a crash occurs. .

2. Supporting Deployed Applications
By including a consistent error handler design with a central error handler, you can deploy applications that document the crashes your users encounter. This is particularly important if you have many remote customers and can't easily go to the offending desktop when the user calls. 


## Basic Error Handling
Professional applications need to include error handling to trap unexpected errors. By using a consistent error handler, you can make sure that when crashes occur, the user is properly informed and your program exits gracefully. Basic error handling just hides the default behavior and exits the program. Advanced error handling can include all sorts of features such as saving information about the cause of the error and the environment at the time, attempts to address the problem, and information for the user on what they need to do next.

Microsoft Access RuntimeMicrosoft Access Runtime
If you are deploying Microsoft Access databases with the free runtime version (to users who don't own Microsoft Access), the developer environment doesn't exist. In such situations, you need to have an error handling system in place to capture errors and gracefully exit your program should it crash. 

If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
Debugging is the process of finding errors. It involves a process of deduction.
The console helps narrow down the area in which the error is located, so you can try to find the exact error.
JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback. 
