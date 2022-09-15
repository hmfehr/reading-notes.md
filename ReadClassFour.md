# Readings: HTML Links, JS Functions, and Intro to CSS Layout

[HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

1. To create a basic link, we wrap text or other content inside what element?
*  `<p>
  I'm creating a link to
  <a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>.
</p>`

 
2.  The `href` attribute contains what information?
*  A basic link is created by wrapping the text or other content, see Block level links, inside an `<a>` element and using the `href` attribute, also known as a Hypertext Reference, or target, that contains the web address.
3. What are some ways we can ensure links on our pages are accessible to all readers?
* We can hover over the linked text to display the extention.


## CSS Layout: Normal Flow CSS Layout: Positioning

1. What is meant by “normal flow”?
* As detailed in the last lesson introducing layout, elements on a webpage lay out in normal flow if you haven't applied any CSS to change the way they behave. And, as we began to discover, you can change how elements behave either by adjusting their position in normal flow or by removing them from it altogether. Starting with a solid, well-structured document that's readable in normal flow is the best way to begin any webpage. It ensures that your content is readable even if the user's using a very limited browser or a device such as a screen reader that reads out the content of the page. In addition, since normal flow is designed to make a readable document, by starting in this way you're working with the document rather than struggling against it as you make changes to the layout.
2. What are a few differences between block-level and inline elements?
*By default, a block level element's content fills the available inline space of the parent element containing it and grows along the block dimension to accommodate its content. The size of Inline elements is just the size of their content. You can't set width or height on inline elements — they just sit inside the content of block level elements. If you want to control the size of an inline element in this manner, you need to set it to behave like a block level element (e.g., with `display: block;` or `display: inline-block;`, which mixes characteristics from both).
3. ___ positioning is the default for every html element.
*Static positioning is the default that every element gets. It just means "put the element into its normal position in the document flow."
4. Name a few advantages to using absolute positioning on an element.
* `position: absolute;` brings everything into a strict matching lyout.
5. What is a key difference between fixed positioning and absolute positioning?
* First of all, note that the gap where the positioned element should be in the document flow is no longer there — the first and third elements have closed together like it no longer exists! Well, in a way, this is true. An absolutely positioned element no longer exists in the normal document flow. Instead, it sits on its own layer separate from everything else. This is very useful: it means that we can create isolated UI features that don't interfere with the layout of other elements on the page. For example, popup information boxes, control menus, rollover panels, UI features that can be dragged and dropped anywhere on the page, and so on.

Second, notice that the position of the element has changed. This is because `top`, `bottom`, `left`, and `right` behave in a different way with absolute positioning. Rather than positioning the element based on its relative position within the normal document flow, they specify the distance the element should be from each of the containing element's sides. So in this case, we are saying that the absolutely positioned element should sit 30px from the top of the "containing element" and 30px from the left. (In this case, the "containing element" is the initial containing block. See the section below for more information)

## Functions – Reusable Blocks of Code

1. Describe the difference between a function declaration and a function invocation.
* Once you invoc your function you have to declar it to be alowed to run it. Both parts have to be included. Note: This form of creating a function is also known as function declaration. It is always hoisted, so you can call function above function definition and it will work fine.
2. What is the difference between a parameter and an argument?
* Some functions require parameters to be specified when you are invoking them — these are values that need to be included inside the function parentheses, which it needs to do its job properly. Note: Parameters are sometimes called arguments, properties, or even attributes.

# [6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
* While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language:

- Listening: hearing and interpreting the vocabulary
- Speaking: using the correct words to communicate an idea
- Reading: understanding what written language intends to convey
- Writing: producing from scratch a meaningful, well structured solution

i think this is important because it is making me see that this skill is always growing and learning. That understaning that knowing how important is to learn as a community to further develop skills.
pair programing seems to allow a smoother work flow when working with others to break down the work load, and allows to focus on the project!
