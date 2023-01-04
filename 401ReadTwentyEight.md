# Component Lifecycle / `useEffect` Hook

## [effects hook](https://reactjs.org/docs/hooks-effect.html)
- What purpose does `useEffect` serve in a function component compared to its counterpart(s) in class components?
* By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates.

- When using the useEffect Hook: 

* What does useEffect do?
React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates.

* Why is `useEffect` called inside a component?
Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don’t need a special API to read it — it’s already in the function scope.

* Why is `useEffect` called inside a component?

* Explain the importance of properly implementing effects with Cleanup
For example, we might want to set up a subscription to some external data source. In that case, it is important to clean up so that we don’t introduce a memory leak! 

