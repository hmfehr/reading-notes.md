# [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)


### What is the `single responsibility principle` and how does it apply to components?
* Break The UI Into A Component Hierarchy
* Use the same techniques for deciding if you should create a new function or object.
* A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

### What does it mean to build a ‘static’ version of your application?
* To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.
* At the end of this step, you’ll have a library of reusable components that render your data model. 

### Once you have a static application, what do you need to add?
* The components will only have `render()` methods since this is a static version of your app. The component at the top of the hierarchy `(FilterableProductTable)` will take your data model as a prop. If you make a change to your underlying data model and call `root.render()` again, the UI will be updated. You can see how your UI is updated and where to make changes. React’s one-way data flow (also called one-way binding) keeps everything modular and fast.

### What are the three questions you can ask to determine if something is state?
* Is it passed in from a parent via props? If so, it probably isn’t state.
* Does it remain unchanged over time? If so, it probably isn’t state.
* Can you compute it based on any other state or props in your component? If so, it isn’t state.

### How can you identify where state needs to live?
* Identify every component that renders something based on that state.
* Find a common owner component (a single component above all the components that need the state in the hierarchy).
* Either the common owner or another component higher up in the hierarchy should own the state.
* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


# [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)


### What is a “higher-order function”?
* Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. Since we have already seen that functions are regular values, there is nothing particularly remarkable about the fact that such functions exist. The term comes from mathematics, where the distinction between functions and other values is taken more seriously.

* Higher-order functions allow us to abstract over actions, not just values. They come in several forms. For example, we can have functions that create new functions.

### vExplore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
* allows you to create a new functions bassed on if something is greater then or then 10, and creating a new funcion based on the results

### Explain how either map or reduce operates, with regards to higher-order functions.
* The map method transforms an array by applying a function to all of its elements and building a new array from the returned values.
* 

