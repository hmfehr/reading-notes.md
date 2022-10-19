# [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

### What does .map() return?
* The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

### If I want to loop through an array and display each value in JSX, how do I do that in React?
* You can build collections of elements and include them in JSX using curly braces {}.

### Each list item needs a unique ____.
* A “key” is a special string attribute you need to include when creating lists of elements

### What is the purpose of a key?
* Keys help React identify which items have changed, are added, or are removed.

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

### What is the spread operator?
* The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

### List 4 things that the spread operator can do.
* Copying an array
* Concatenating or combining arrays
* Using Math functions
* Using an array as arguments
* Adding an item to a list
* Adding to state in React
* Combining objects
* Converting NodeList to an array      

### Give an example of using the spread operator to combine two arrays.
* `const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩`

### Give an example of using the spread operator to add a new item to an array.
* 
`const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]`

### Give an example of using the spread operator to combine two objects into one.
* 
