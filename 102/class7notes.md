# PROGRAMING WITH JS

## CONTROL FLOW
* The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.

For example, the above excerpt might be inside a function that runs when the user clicks the Submit button for the form. The function could also include a loop, which iterates through all of the fields in the form, checking each one in turn. Looking back at the code in the if and else sections, the lines promptUser and submitForm could also be calls to other functions in the script. As you can see, control structures can dictate complex flows of processing even with only a few lines of code.

* Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

### JavaScript Functions

* A JavaScript function is a block of code designed to perform a particular task.

* A JavaScript function is executed when "something" invokes it (calls it).

### JavaScript Function Syntax

* A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

* Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

* The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)


**The code to be executed, by the function, is placed inside curly brackets: {}**
" function name(parameter1, parameter2, parameter3) {
  // code to be executed
} "

* Function parameters are listed inside the parentheses () in the function definition.

* Function arguments are the values received by the function when it is invoked.

* Inside the function, the arguments (the parameters) behave as local variables.

## Function Invocation

**The code inside the function will execute when "something" invokes (calls) the function:**

* When an event occurs (when a user clicks a button)
* When it is invoked (called) from JavaScript code
* Automatically (self invoked)

## Function Return

When JavaScript reaches a return statement, the function will stop executing.

**The () Operator Invokes the Function**
