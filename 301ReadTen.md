# [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

### What is a ‘call’?
*  The call stack maintains a record of the position of each stack frame. It knows the next function to be executed (and will remove it after execution). This is what makes code execution in JavaScript synchronous.

### How many ‘calls’ can happen at once?
* 1

### What does LIFO mean?
* Last In, First Out data structure.
* LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
* 1. It is single-threaded. Meaning it can only do one thing at a time.
* 2. Code execution is synchronous.
* 3. A function invocation creates a stack frame that occupies a temporary memory.
* 4. It works as a LIFO — Last In, First Out data structure.


### What causes a Stack Overflow?
* A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

# [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

### What is a ‘reference error’?
* This is also a common thing when using const and let, they are hoisted like var and function but there is a time between the hoisting and being declared so when you try to access them a reference error occurs, the fact that this happens to let and const is called Temporal Dead Zone (TDZ).

### What is a ‘syntax error’?
* occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

### What is a ‘range error’?
* Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up. An array for instance cannot have a negative length, why would you mess with the array length? Some people use it to set an array to empty, something of the likes of

### What is a ‘type error’?
* This is probably the most frequent error in JS, trying to access a property/method thinking that bar is of the type object when in reality, since it hasn’t been declared yet, it’s undefined which doesn’t have any baz available.

The fix is simple, just make sure that bar exists before trying to access it, either by creating bar or by checking for undefined.

### What is a breakpoint?
* You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. In this example the breakpoint will point stop when the index reaches 40.

### What does the word ‘debugger’ do in your code?
* To debug your JS code, the easiest and maybe the most common way its to simply console.log() the variables you want to check or, by using chrome developer tools, open your page with your JS code (press cmd+o in macOS or Ctrl+o in Windows) and choose your file to debug, click the line you wanna debug and refresh your page again (F5).
