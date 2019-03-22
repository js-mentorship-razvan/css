# CSS
This repository contains CSS study notes

CSS (Cascading Style Sheets) is the language that specifies how documents/ web pages are presentet to users. With CSS you can design a web page to look exactly how you want. Let's see how it actually works. 

First of all, CSS can be implemented in the HTML document itself, but also in a separate document. Most of the time will be a separate document to keep things more clean and easy to manage. 

*CSS has two specific rules, _selectors_ and _properties_.*

_Selectors_ dictates which elements within the HTML document will be modified.

_Properties_ are then applied for selectors to update the document. These are basically like methods in JS. You can change the background color, resize text, tables and much more. 


*Css is very similiar to Objects in JavaScript language.*

To select a class element from HTML document, we use dot followed by it's name : `.insertnamehere`.

To select an id element from HTML document, we use hash symbol followed by it's name : `#insertnamehere`.

To select any other element, we just use the name from HTML document.

Let's learn some properties: 

- [`border`](https://developer.mozilla.org/en-US/docs/Web/CSS/border)  -sets the element's border;
- [`float`](https://developer.mozilla.org/en-US/docs/Web/CSS/float) -places an element of the left or right side of it's container and allows text and other elements to wrap around it.
- [`margin`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin) -sets the margin area on all four sides of an element(top, right, left, bottom);
- [`color`](https://developer.mozilla.org/en-US/docs/Web/CSS/color) -sets the color of an element's text;
- [`background-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-color) -sets the background color of an element;
- [`text-align`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align) -sets the alignment of a block element or table-cell box;
- [`padding`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding) -creates extra space _within_ an element, while in contrast, `margin` creates extra space _around_ an element. Padding can be used for all four sides of an element in this order: top, right, bottom, left. If we only set 3 values, this will execute like this: top, right+left and bottom.
- [`font`](https://developer.mozilla.org/en-US/docs/Web/CSS/font) - is a shorthand property for `font-style`, `font-variant`, `font-weight`, `font-size`, `line-height`, and `font-family`;
- [`height`](https://developer.mozilla.org/en-US/docs/Web/CSS/height) -specifies the height of an element;
- [`text`](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Text) -sets text manipulation. Is has many properties: `hanging-punctuation`, `hyphens`, `letter-spacing`, `line-break`, `overflow-wrap`, `tab-size`, `text-align`, `text-align-last`, `text-indent`, `text-justify`, `text-size-adjust`, `text-transform`, `white-space`, `word-break`, `word-spacing`.
- [`display`](https://developer.mozilla.org/en-US/docs/Web/CSS/display) -defines the _display type_ of an element;
- [`pseudo-class`](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Pseudo-classes_and_pseudo-elements) -is a keyword added at the end of a selector, preceded by a colon (`:`), used to specify _in which state_ that element is gonna be modified.


