# reading 03
#### 07 April 2020

- https://medium.com/@1sherlynn/javascript-templating-language-and-engine-mustache-js-with-node-and-express-f4c2530e73b2
the curly brackets {} are referred to as mustaches when being used a place holder, for example {{ name }} will hold the place for the name value until it is given, when it is given it will take the place of teh palce holder. mustache is not a templating engine, to use it you must download files to reference. 

- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
using flex will order the elements in the flex container with a single directional layout. because they will all try to be inline, you can break that with flex wrap, whch will fill the line until it runs out and will fill below. you can use the value safe to ensure that you do not lose data to the edge of the screen where you cannot scroll to. justify-content aligns the items within the box, only when there is more than one line of elements.

- https://flexboxfroggy.com/
complete, answer 24 : 

#### bookmark
- https://github.com/janl/mustache.js

## code 
- mustache place holder 
Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });

- flex boxes 
.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
row (default): left to right in ltr; right to left in rtl
row-reverse: right to left in ltr; left to right in rtl
column: same as row but top to bottom
column-reverse: same as row-reverse but bottom to top