# Readings: CSS Layout

1. Flexbox is designed for one-dimensional content. Explain what this means.
* The Flexible Box Layout Model (flexbox) is a layout model designed for one-dimensional content. It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

2. Explain the difference between the main axis and cross axis.
*  The main axis is the one set by your `flex-direction` property. If that is `row` your main axis is along the row, if it is `column` your main axis is along the column.
*  The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.
 [EXAMPLE](https://user-images.githubusercontent.com/112366173/191542482-dbf268f5-f19c-4fb1-a71a-c38f6cdc8d50.svg)

3. How can using certain properties of flexbox negatively impact accessibility?
* You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility.
* The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

## [CSS Layout - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

1. What are some advantages of using flexbox over float?
* The following simple layout designs are either difficult or impossible to achieve with such tools in any kind of convenient, flexible way:

* Vertically centering a block of content inside its parent.
* Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
* Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.
* As you'll see in subsequent sections, flexbox makes a lot of layout tasks much easier.

2. How does this topic connect with your long term goals?
* this will allow me to have items displayed n the screen in a more organized and plesent thing to vies ovr a broken down basic md file or manualy breaking sections in the html side of vs
