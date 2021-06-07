# Programming with JavaScript

This chapter describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more.


## Operators
JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.
- Assignment operators
- Comparison operators
- Arithmetic operators
- Bitwise operators
- Logical operators
- String operators
- Conditional (ternary) operator
- Comma operator
- Unary operators
- Relational operators

## Functions
Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

### Function declarations
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

- The name of the function.
- A list of parameters to the function, enclosed in parentheses and separated by commas.
- The JavaScript statements that define the function, enclosed in curly brackets, {...}.


### Function expressions
While the function declaration above is syntactically a statement, functions can also be created by a function expression.

### Calling functions
Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.


### Function parameters
Starting with ECMAScript 2015, there are two new kinds of parameters: default parameters and rest parameters.

** Default parameters**

In JavaScript, parameters of functions default to undefined. However, in some situations it might be useful to set a different default value. This is exactly what default parameters do.

Without default parameters (pre-ECMAScript 2015)
In the past, the general strategy for setting defaults was to test parameter values in the body of the function and assign a value if they are undefined.