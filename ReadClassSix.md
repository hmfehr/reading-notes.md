# Problem Domain, Objects, and the DOM

How would you describe an object to a non-technical friend you grew up with?
*An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects). meaning that we can put the code we want into simplier lines to be called upon later.
What are some advantages to creating object literals?
The value of an object member can be pretty much anything — in our person object we've got a number, an array, and two functions. The first two items are data items, and are referred to as the object's properties. The last two items are functions that allow the object to do something with that data, and are referred to as the object's methods. An object like this is referred to as an object literal — we've literally written out the object contents as we've come to create it.
How do objects differ from arrays?
Objects represent a special data type that is mutable and can be used to store a collection of data (rather than just a single value). Arrays are a special type of variable that is also mutable and can also be used to store a list of values.
Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
bracket notation works like an array where you can call spacific itemes in the array.
Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?
using the object literal `this` allows you to use the same method definition for every object you create.
ex:
`const person1 = {
  name: 'Chris',
  introduceSelf() {
    console.log(`Hi! I'm ${this.name}.`);
  }
}

const person2 = {
  name: 'Deepti',
  introduceSelf() {
    console.log(`Hi! I'm ${this.name}.`);
  }
}`

What is the DOM?
* Is the data representation of the objects that comprise the structure and content of a document on the web.
Briefly describe the relationship between the DOM and JavaScript.
* it is written in JavaScript, but uses the DOM to access the document and its elements. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript.

The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node.js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node.js runtime.
