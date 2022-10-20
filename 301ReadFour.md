# [React Docs - Forms]()

### What is a ‘Controlled Component’?
* We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.
* In HTML, form elements such as `<input>`, `<textarea>`, and `<select>` typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with `setState()`.
  
### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
* you want to wait for them to submit because it allows the user to make changes or fix something befor it being stored.

### How do we target what the user is entering if we have an event handler on an input field?
* When you need to handle multiple controlled `input` elements, you can add a `name` attribute to each element and let the handler function choose what to do based on the value of `event.target.name`.

# [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

### Why would we use a ternary operator?
* to simply write true or salse statements into one liners.

### Rewrite the following statement using a ternary statement:
* `if(x===y){
  console.log(true);
} else {
  console.log(false);
}`

`x===y ? 'true' : 'false'`;
