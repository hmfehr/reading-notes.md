# Express REST API

## Review: ES6 Classes

1. Classes are a template for creating `____`.
Classes are a template for creating objects.

2. Can a class declaration be hoisted?
yes in js they can be hoisted

3. How would you describe a constructor and contextual “this” to a non-technical friend?
it assigns the this you are using and adds value to it


## Using Express Routing


1. Within Express, what does routing refer to?
refers to how an application’s endpoints (URIs) respond to client requests

2. What is the difference between a route path and a route method?
A route method is derived from one of the HTTP methods, and is attached to an instance of the express class. Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.

3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?
 With multiple callback functions, it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback.



## Express Routing

1. What is an Express Router?
Router is like a mini-Express application. It doesn’t bring in views or settings but provides us with the routing APIs like `.use`, `.get`, `.param`, and `route`fff.

2. By what mean do we initialize `express.Router()` in an express server?
Using the Router, we are allowed to make our applications more modular and flexible than ever before by creating multiple instances of the Router and applying them accordingly. Now we’ll take a look at how we can use middleware to handle requests.

3. What do we use route middleware for?
Route middleware in Express is a way to do something before a request is processed. This could be things like checking if a user is authenticated, logging data for analytics, or anything else we’d like to do before we actually spit out information to our user.
















































