# Javascript

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. Read more about JavaScript.
This section is dedicated to the JavaScript language itself, and not the parts that are specific to Web pages or other host environments. For information about APIs that are specific to Web pages, please see Web APIs and DOM.
The standards for JavaScript are the ECMAScript Language Specification (ECMA-262) and the ECMAScript Internationalization API specification (ECMA-402). As soon as one browser implements a feature, we try to document it. This means that cases where some proposals for new ECMAScript features have already been implemented in browsers, documentation and examples in MDN articles may use some of those new features. Most of the time, this happens between the stages 3 and 4, and is usually before the spec is officially published.
Do not confuse JavaScript with the Java programming language. Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, semantics, and use.

One of the cornerstones of modern web application is the behind-the-scenes, asynchronous data communication between the server and the JavaScript code running in the browsers. While in Ajax, the X stands for XML, in reality many applications send data formatted as JSON. In most cases it is more convenient than sending XML.

All the code that is relevant to sending the asynchronous request was placed in a function called ajax_get. This function expects two parameters. The first one is the URL we request. It can be a URL like http://somesite.com/some/page, or it can be without the hostname just /some/page if we want to send the request to the same server where our JavaScript code came from. In either case we can also send parameters by attaching them after the requested URL. Something like this: http://somesite.com/some/page?fname=Foo&lname=Bar

The second parameter is expected to be a function which will be called when the response arrives from the server.

Just to quickly go over the function: First we create an *XMLHttpRequest()* object. Then we attach a function call to *onreadystatechange* attribute of the object. This function will be executed when the successful response arrives. Then we call *open*, this is where we use the *url* and finally we *send* the request

The 3 important lines are the following:
" <input id="task"><button id="add">Add</button> "
" <div id="todos"></div> "
" <script src="todo.js"></script> "

At first we have an *input* element where we'll be able to enter text and it has a button that we'll be able to click.

In the second row we have an empty *div* element. We are going to display the current list in that element.

Finally we load an external JavaScript file called *todo.js*

The reason we load the JavaScript file at the end is that we wanted to make sure the other elements are already in the browser by the time the JavaScript file is loaded and by the time it starts to run.

**examples/js/todo.html**

' <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
</head>
<body>
<input id="task"><button id="add">Add</button>
<hr>
<div id="todos"></div>
 
<script src="todo.js"></script>
</body>
</html> "

**Use Strict**- You can include a string "*use strict*"; at the beginning of a file or the beginning of a function and that will turn on the strict mode for the whole file or for that specific function, respectively. Because the construct is a string literal and because JavaScript has the strange behavior of disregarding string literals floating around the code, this snippet will be disregarded in any browser that does not support it. Which is not that interesting any more as by today virtually every browser on the market supports it.
**examples/js/add_2_numbers_fixed.js**

 "use strict";
function add(x, y) {
    return x + y;
}
console.log(add(2, 3));      // 5
console.log(add(-1, 1));     // 0
 
console.log(add(1, 1, 1));   // 2 "

Open JavaScript Console of Chrome on MS Windows
Ctrl-Shift-J

## 4 Ways to Declare a JavaScript Variable:
-Using var - variables
-Using let - 
-Using const
-Using nothing

**When to Use JavaScript var?**
Always declare JavaScript variables with var,let, orconst.
The var keyword is used in all JavaScript code from 1995 to 2015.
The let and const keywords were added to JavaScript in 2015.
If you want your code to run in older browser, you must use var.

**When to Use JavaScript const?**
If you want a general rule: always declare variables with const.
If you think the value of the variable can change, use let.
In this example, price1, price2, and total, are variables:

JavaScript Identifiers
All JavaScript variables must be identified with unique names.

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

#The general rules for constructing names for variables (unique identifiers) are:

* Names can contain letters, digits, underscores, and dollar signs.
*Names must begin with a letter
*Names can also begin with $ and _ (but we will not use it in this tutorial)
*Names are case sensitive (y and Y are different variables)
*Reserved words (like JavaScript keywords) cannot be used as names

