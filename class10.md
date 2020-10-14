# Error Handling & Debugging on JavaScript

 Javascript processes one line of code at a time, so when a statement needs data from another function, it will pile the new function op top of current task.
 There is an order of execution that must be understood in order to find the source of an error. Some tasks cannot be implemented until another statement or function has been run. There are different types of execution contexts, then each function creates a new execution context which corresponds to variable scope;

Execution Function | Variable Scope
--------------------|------------------
**Global Context** ; is a code that is in the script, but not in a function. Only one can be present on a page. | **Global Scope** ; when a variable is declared outside a function, it can be used anywhere because it has global scope.
**Function Context** ; is a code that is being run inside  function, and both have their own function context | **Function-Level Scope** ; when a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

 JavaScript can help you learn how to find the errors in your code, which will also teach you how to write scripts that deal with potential errors gracefully.
 There are three different types of helper tools that JavaScript has.

## I. The Console,Dev Tools & Common Problems

The *console* and *dev* are tools built in the browser that can help retrace the errors. Error objects can help you find where your mistakes are and browsers have tools to help you read them.

![Table Error Objects & Properties](/img/errors.png)
![Syntax & Referrence Errors](/img/syntax-errors.png)
![Type & Range Errors](/img/errors2.png)


*Common problems* are sources of errors, and how to solve them.

## II. Handling Errors

Once the error is pin pointed out, there are two ways to deal with them;

1. Debug the script to fix the errors, by eleminating potential causes of an error
2. Handle errors gracefully using try(specify the code
that you think might throw an exception within the try block.), catch(if the try code block throws an exception, catch steps in with an alternative set of code.), and fina1ly(The contents of the fi na11y code block will run either way - whether the try block succeeded or failed.) statements.

### A Debugging Workflow

To narrow down where the problem might be, one should look for clues;

- Identify where is the problem
- identify what exactly is the problem
