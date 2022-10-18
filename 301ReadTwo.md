# [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093) 

### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
* based on the graph the `render` happens before the `componentDidMount`

### What is the very first thing to happen in the lifecycle of React?
* mounting the constructor is the first thing don in react.

### Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`
* `constructor`, `render`, `React Updates`, `componentDidMount`, `componentWillUnmount`

### What does `componentDidMount` do?
* This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in `componentWillUnmount()`.


# [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

### What types of things can you pass in the props?
* arguments to a function. pass the props that you want to give to it where you want it to start at. passing thing like you would to a normal function.
* stores user name and password. allows to change and re render.

### What is the big difference between props and state?
* props pass into a componat and state happens within the component. props set up the initial value of state

### When do we re-render our application?
* when you change the state, this is the only way to get the application to re render

### What are some examples of things that we could store in state?
* username, values, passwords, 

## Bookmark and Review
[React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
[React Docs - handling events](https://reactjs.org/docs/handling-events.html)
[React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
[React Bootstrap Documentation](https://react-bootstrap.github.io/)
[Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
[Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
[Netlify](https://www.netlify.com/)
