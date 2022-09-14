Absolute lengths(px, mm, in, cm)
Relative lengths(Units specify a length relative to another length property)
* em (relative to the font-size of the element, usually 16px)
---If the parent font-size is 16px and the child is calling for 1em === 16px
---2em === 32px
* vw (viewport width) 75vw == 75% of the viewport width
* vh (viewport height)100vh == 100% of the viewport hight
* percentage 100% is how much space the parent provides the child element
 width: 100% !== width: 100vw
 height: 100% !== height: 100vw