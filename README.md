Flexbox-examples
================

#### Sources
https://css-tricks.com/snippets/css/a-guide-to-flexbox/

https://css-tricks.com/designing-a-product-page-layout-with-flexbox/

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes

https://css-tricks.com/dont-overthink-flexbox-grids/

#### Parent Container
```
display: flex

flex-direction: row | row-reverse | column | column-reverse;
flex-wrap: nowrap | wrap | wrap-reverse;
flex-flow: <‘flex-direction’> || <‘flex-wrap’>

justify-content: flex-start | flex-end | center | space-between | space-around;
align-items: flex-start | flex-end | center | baseline | stretch;
align-content: flex-start | flex-end | center | space-between | space-around | stretch;
```
#### Item Children
```
order: <integer>;

flex-grow: <number>;
flex-shrink: <number>;
flex-basis: <length> | auto;
flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]

align-self: auto | flex-start | flex-end | center | baseline | stretch;
```