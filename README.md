# CSSLayoutChallenge
## Position
1. relative
- the space the element would have occupied in the normal flow is preserved as empty space.
- commonly used to create a “positioning context” for an absolutely positioned element.
Ex: `.container {postion: relative}`
2. absolute
- if the positioned element is not contained within another positioned element, then it will be placed relative to the initial containing block (created by the html element).
- if the element has an ancestor (i.e., is contained within an element) that has its position set to relative, absolute, or fixed, the element will be positioned relative to the edges of that element instead.
The actual position is specified with some combination of up to four offset properties: top, right, bottom, left.
Ex: `.child {position: absolute; left: 50px, right: 50px}`
