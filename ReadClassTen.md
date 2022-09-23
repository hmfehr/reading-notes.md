# Readings: Debugging

## What Went Wrong? Troubleshooting JavaScript.
1. Name some key differences between a Syntax Error and a Logic Error.
* Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!
* Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
* the problems Im personally facing are syntex errors in my code causing me not to properly run my dom or possible thats where the issue is happening

3. How will this topic continue to influence your long term goals?
* this topic makes me want to learn how to de bugg because i fee that itll help me understand the js its self.

## The JavaScript Debugger
1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
* The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.

2. Define what a breakpoint is.
*Watch expressions and breakpoints
The right-hand pane shows a list of the watch expressions you have added and breakpoints you have set.

In the image, the first section, Watch expressions, shows that the listItems variable has been added. You can expand the list to view the values in the array.

The next section, Breakpoints, lists the breakpoints set on the page. In example.js, a breakpoint has been set on the statement listItems.push(inputNewItem.value);

The final two sections only appear when the code is running.

3. What is the call stack?
* The Call stack section shows you what code was executed to get to the current line. You can see that the code is in the function that handles a mouse click, and that the code is currently paused on the breakpoint.

The final section, Scopes, shows what values are visible from various points within your code. For example, in the image below, you can see the objects available to the code in the addItemClick function.
