# Readings: Audio, Video, Images

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
* offer a convenient, easy way to host and consume videos, so you don't have to worry about the enormous bandwidth consumption.

2. Describe the use of the `src` and controls attributes in the `<video>` element.
* the `src` is like an `img` tag where the set up is a link for the video and or audio to play

3. Why is it important to have `fallback content` inside the `<video>` element?
* Its important to have a fallback incause the users browser doesnt support the `video` they have some way to access it

## [A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

1. How does Grid layout differ from Flex?
grid is a two dimenssiol grid based system. flex is a ondimentional that works well when used together

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
* Grid Line
The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.
* Grid Container
The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.
* Grid Item
The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.


## Responsive Images
1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
* A typical website may contain a header image and some content images below the header. The header image will likely span the whole of the width of the header, and the content image will fit somewhere inside the content column.

2. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.
* The standard <img> element traditionally only lets you point the browser to a single source file:

`<img src="elva-fairy-800w.jpg" alt="Elva dressed as a fairy" />`
* srcset defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma.
* sizes defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true 

3. How is srcset more helpful for responsive images than CSS or JavaScript?

