# Readings: HTML Lists, Control Flow with JS, and the CSS Box Model

The `<ol>` HTML element represents an ordered list of items — typically rendered as a numbered list.
*ex;* `<ol>
  <li>Mix flour, baking powder, sugar, and salt.</li>
  <li>In another bowl, mix eggs, milk, and oil.</li>
  <li>Stir both mixtures together.</li>
  <li>Fill muffin tray 3/4 full.</li>
  <li>Bake for 20 minutes.</li>
</ol>`

*output;* 
1. Mix flour, baking powder, sugar, and salt.
2. In another bowl, mix eggs, milk, and oil.
3. Stir both mixtures together.
4. Fill muffin tray 3/4 full.
5. Bake for 20 minutes.

* When should you use an unordered list in your HTML document?
when you want to do a buleted list.
* How do you change the bullet style of unordered list items?
This attribute sets the bullet style for the list. The values defined under HTML3.2 and the transitional version of HTML 4.0/4.01 are:

1. circle
2. disc
3. square
4. A fourth bullet type has been defined in the WebTV interface, but not all browsers support it: `triangle.`

* When should you use an ordered list vs an unorder list in your HTML document?
you should use an ordered list when you want to use a numarical number system or a general bulleted list to signify priority.
* Describe two ways you can change the numbers on list items provided by an ordered list?
Attributes
This element also accepts the global attributes.

`reversed`
This Boolean attribute specifies that the list's items are in reverse order. Items will be numbered from high to low.

`start`
An integer to start counting from for the list items. Always an Arabic numeral (1, 2, 3, etc.), even when the numbering type is letters or Roman numerals. For example, to start numbering elements from the letter "d" or the Roman numeral "iv," use start="4".

`type`
Sets the numbering type:

a. for lowercase letters
A. for uppercase letters
i. for lowercase Roman numerals
I. for uppercase Roman numerals
1. for numbers (default)
The specified type is used for the entire list unless a different type attribute is used on an enclosed <li> element.
  
  ## Box Modle
  -The CSS box model as a whole applies to block boxes and defines how the different parts of a box — margin, border, padding, and content — work together to create a box that you can see on a page. Inline boxes use just some of the behavior defined in the box model.
  
  If a box has an outer display type of block, then:

The box will break onto a new line.
The `width` and `height` properties are respected.
Padding, margin and border will cause other elements to be pushed away from the box.
The box will extend in the inline direction to fill the space available in its container. In most cases, the box will become as wide as its container, filling up 100% of the space available.
  
  ### Margin
The margin is an invisible space around your box. It pushes other elements away from the box. Margins can have positive or negative values. Setting a negative margin on one side of your box can cause it to overlap other things on the page. Whether you are using the standard or alternative box model, the margin is always added after the size of the visible box has been calculated.

- We can control all margins of an element at once using the margin property, or each side individually using the equivalent longhand properties:

`margin-top`
`margin-right`
`margin-bottom`
`margin-left`
  
  ### Padding
  
  The padding sits between the border and the content area and is used to push the content away from the border. Unlike margins, you cannot have a negative padding. Any background applied to your element will display behind the padding.

The padding property controls the padding on all sides of an element. To control each side individually, use these longhand properties:

`padding-top`
`padding-right`
`padding-bottom`
`padding-left`
  
  ## Arrays
  
- Arrays are generally described as "list-like objects"; they are basically single objects that contain multiple values stored in a list. Array objects can be stored in variables and dealt with in much the same way as any other type of value, the difference being that we can access each value inside the list individually, and do super useful and efficient things with the list, like loop through it and do the same thing to every value. Maybe we've got a series of product items and their prices stored in an array, and we want to loop through them all and print them out on an invoice, while totaling all the prices together and printing out the total price at the bottom.
  
 - Arrays consist of square brackets and items that are separated by commas.
  
  
  
  
  
  
  
  
  
  
  
  
  
  
