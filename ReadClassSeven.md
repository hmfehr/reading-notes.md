# Readings: Object-Oriented Programming, HTML Tables

## [Domain Moddling](https://github.com/codefellows/domain_modeling#domain-modeling)

### Explain why we need domain modeling.
*  A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. We need domain modleing to simplify and run better formatted js.

## [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

### Why should tables not be used for page layouts?
* table lay should not be used for page layouts, because we are able to style and format the looks of the page. tables use to be used for page layout and wouldstructure the lay out as a table. also Layout tables reduce accessibility for visually impaired users. Tables produce tag soup makes code too busy. Tables are not automatically responsive.

### List and describe 3 different semantic HTML elements used in an HTML `<table>`.
`<th>` is a tabe header. `colspan` and `rowspan`, `span` takes a unitless number value that specifies the number of columns you want the styling to apply to. you generally have to specify your styling information on every `<td>` or `<th>` in the column

## [Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

### What is a constructor and what are some advantages to using it?
* We would like a way to define the "shape" of an object — the set of methods and the properties it can have — and then create as many objects as we like, just updating the values for the properties that are different. this allows us t use and make chenges for a different time and be able to change around data.

### How does the term this differ when used in an object literal versus when used in a constructor?
* This works fine but is a bit long-winded: we have to create an empty object, initialize it, and return it. A better way is to use a constructor. A constructor is just a function called using the `new` keyword. When you call a constructor, it will:

* create a new object
* bind `this` to the new object, so you can refer to `this` in your constructor code
* run the code in the constructor
* return the new object.
EX: 
`function Person(name) {
  this.name = name;
  this.introduceSelf = function() {
    console.log(`Hi! I'm ${this.name}.`);
  }
}`
