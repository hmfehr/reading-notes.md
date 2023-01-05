# Advanced State with Reducers

## [Advanced State with Reducers](https://reactjs.org/docs/hooks-reference.html#usereducer)
* Name an alternative to the `useState` Hook.
- `(state, action) => newState`, and returns the current state paired with a `dispatch` method.

* Why might the `useReducer` Hook be preferable to the `useState` Hook?
- `useReducer` is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.

* What are two ways to set the initial state?
`  const [state, dispatch] = useReducer(
    reducer,
    {count: initialCount}
  );`
  
  **`function init(initialCount) {
  return {count: initialCount};
}**

function reducer(state, action) {
  switch (action.type) {
    case 'increment':
      return {count: state.count + 1};
    case 'decrement':
      return {count: state.count - 1};
    case 'reset':
      return init(action.payload);
    default:
      throw new Error();
  }
}

function Counter({initialCount}) {
  const [state, dispatch] = useReducer(reducer, initialCount, init);
  return (
    <>
      Count: {state.count}
      <button
        onClick={() => dispatch({type: 'reset', payload: initialCount})}>
        Reset
      </button>
      <button onClick={() => dispatch({type: 'decrement'})}>-</button>
      <button onClick={() => dispatch({type: 'increment'})}>+</button>
    </>
  );
}
`


##[Ultimate Guide to useReducer](https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/)
* In terms of state, what does `useReducer` expect to receive as a parameter?
- The reducer function itself accepts two parameters and returns one value. The first parameter is the current state, and the second is the action. The state is the data we are manipulating. The reducer function receives an action, which is executed by a `dispatch` function:

* What does `useReducer` return?
- useReducer returns an array that holds the current state value and a `dispatchmethod` that logically achieves the same goal as `setState`, updating the state.

* Explain `dispatch` to a non-technical recruiter.
- dispatch is a short hand for redux and to return the functions
