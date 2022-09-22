# Readings: Forms and JS Events

1. Why are forms so important in web development?
* Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
* Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

3. List 5 form elements and explain their importance.

1. All forms start with a <form> element, like this: `<form action="/my-handling-form-page" method="post">…</form>`
2. Our contact form is not complex: the data entry portion contains three text fields, each with a corresponding <label>:

* The input field for the name is a single-line text field.
* The input field for the e-mail is an input of type email: a single-line text field that accepts only e-mail addresses.
* The input field for the message is a `<textarea>`; a multiline text field.
* ex: `<form action="/my-handling-form-page" method="post">
  <ul>
    <li>
      <label for="name">Name:</label>
      <input type="text" id="name" name="user_name" />
    </li>
    <li>
      <label for="mail">E-mail:</label>
      <input type="email" id="mail" name="user_email" />
    </li>
    <li>
      <label for="msg">Message:</label>
      <textarea id="msg" name="user_message"></textarea>
    </li>
  </ul>
</form>`
  
  3. The `<button>` element
  * The markup for our form is almost complete; we just need to add a button to allow the user to send, or "submit", their data once they have filled out the form. This is done by using the `<button>` element; add the following just above the closing `</ul>` tag:
  `<li class="button">
  <button type="submit">Send your message</button>
</li>`
  
  ## Learn JS
  
  1. How would you describe events to a non-technical friend?
* Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.
  2. When using the addEventListener() method, what 2 arguments will you need to provide?
* The recommended mechanism for adding event handlers in web pages is the addEventListener() method:
  `const btn = document.querySelector('button');

function random(number) {
  return Math.floor(Math.random() * (number+1));
}

btn.addEventListener('click', () => {
  const rndCol = `rgb(${random(255)}, ${random(255)}, ${random(255)})`;
  document.body.style.backgroundColor = rndCol;
});`

  3. Describe the event object. Why is the target within the event object useful?
* Sometimes, inside an event handler function, you'll see a parameter specified with a name such as `event`, `evt`, or `e`. This is called the *event object*, and it is automatically passed to event handlers to provide extra features and information. For example, let's rewrite our random color example again slightly:
  const btn = document.querySelector('button');

function random(number) {
  return Math.floor(Math.random() * (number+1));
}

function bgChange(e) {
  const rndCol = `rgb(${random(255)}, ${random(255)}, ${random(255)})`;
  e.target.style.backgroundColor = rndCol;
  console.log(e);
}

btn.addEventListener('click', bgChange);`

  4. What is the difference between event bubbling and event capturing?
 * Event bubbling and capture are terms that describe phases in how the browser handles events targeted at nested elements.
  `<div id="container">
  <button>Click me!</button>
</div>
<pre id="output"></pre>`

  
  

  
