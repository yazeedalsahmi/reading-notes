# CSS layout :

**Positioning Elements :**

Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.

1. **Normal Flow :** position:static In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow.
2. **Relative positioning :** position relative Relative positioning moves an element in relation to where it would have been in normal flow. For example, you can move it 10 pixels lower than it would have been in normal flow or 20% to the right. You can indicate that an element should be relatively positioned using the position property with a value of relative. You then use the offset properties (top or bottom and left or right) to indicate how far to move the element from where it would have been in normal flow. To move the box up or down, you can use either the top or bottom properties. To move the box horizontally, you can use either the left or right properties. The values of the box offset properties are usually given in pixels, percentages or ems.
3. **Absolute positioning:** When the position property 
is given a value of absolute, 
the box is taken out of normal 
flow and no longer affects the 
position of other elements on 
the page. (They act like it is not 
there.) 
The box offset properties (top
or bottom and left or right) 
specify where the element 
should appear in relation to its 
containing element.
4. **Fixed positioning :** Fixed positioning is a type 
of absolute positioning that 
requires the position property 
to have a value of fixed.
It positions the element in 
relation to the browser window. 
Therefore, when a user scrolls 
down the page, it stays in the 
exact same place. It is a good 



