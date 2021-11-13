# <span style="color:blue"> Epsilon and Delta </span>
### Course project for **CSE230 - Principles of Programming Languages**

<br>

## <span style="color:blue"> Overview </span>
Our project, Delta, is a debugger for a simplified programming language, Epsilon. Epsilon is a high level, dynamically typed, imperative programming language with support for first class functions and closures.

<br>

## <span style="color:blue"> Components </span>
The project will involve several components -
- A Lexer and Parser for Epsilon. This will be built using either Parsec or a combination of Alex and Happy, and will convert text files into code for the interpreter to run.
- An Interpreter/Evaluator that walks through the AST generated by the Parser to evaluate statements/expressions in the source code.
- The command line debugger Delta, which provides a command line interface that allows the user to set breakpoints in the source code and uses the interpreter to step through the code until a breakpoint is hit.

<br>

## <span style="color:blue"> User Guide </span>
The user will have the following options:
- Debug line by line on encountering the breakpoint
- Evaluate the current breakpoint and proceed to the next breakpoint

<br>

## T<span style="color:blue"> entative "Final" Product </span>
The result of our project will be an interpreter for Epsilon which allows the user to break the interpreter at selected points in the program, at which point they will be able to view the current state and stack trace, step forward in the program’s execution either one step at a time or run until the next breakpoint**. To do this, we will need to use the brick library, as well as some parser library --- we’re uncertain whether Parsec or the combination of Alex and Happy would be better right now. Ideally, Delta will also support breaking whenever a chosen variable changes.

<br>

## <span style="color:blue"> Epsilon and Beyond </span>
* Triggers on a variable's value change.
* This may be further extended to be a time-travelling debugger, essentially somehow go “X” number of steps back into the execution of the program.
* Extending the language to add more features derived from other modern languages.

## <span style="color:blue"> Team </span>
> Daniel Kleber,
> Abhishek C. Sharma,
> Hema Thota,
> Utkarsh Vashishtha
