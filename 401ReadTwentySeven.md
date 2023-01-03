# `useState()` Hook

##  [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)
* What was the motivation for introducing Hooks?


* What changes are important regarding implementing Hooks versus Component Classes?


* Hooks allow you to reuse stateful logic without changing.
- Hooks allow you to reuse stateful logic without changing your component hierarchy. 

## [hooks api](https://reactjs.org/docs/hooks-overview.html)
* Name two rules imposed by React Hook usage.
- Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
- Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks 

* How would you identify a custom Hook and why might you create one?


## [the state hook](https://reactjs.org/docs/hooks-state.html)
* What is a Hook?
- A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.

* When would I use the `useState` Hook?
- If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component.

* If you were to add React state to a function component by declaring a state variable:


* What does calling `useState` do?
- It declares a “state variable”. Our variable is called count but we could call it anything else, like banana. This is a way to “preserve” some values between the function calls — useState is a new way to use the exact same capabilities that this.state provides in a class. Normally, variables “disappear” when the function exits but state variables are preserved by React.

* What do we pass to `useState` as an argument?
- The only argument to the useState() Hook is the initial state. Unlike with classes, the state doesn’t have to be an object. 

* What does `useState` return?
It returns a pair of values: the current state and a function that updates it. This is why we write `const [count, setCount] = useState()`. This is similar to `this.state.count` and `this.setState` in a class, except you get them in a pair.
