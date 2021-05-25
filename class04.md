# Links :
Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify 
which page you want to link to using the href attribute.
  EX :
  <a href="www.google.com">google</a>
  * The text between the opening <a> tag and closing </a> tag is known as link text.
  * The value of the href attribute is the page that you want people to go to when they click on the link.
  ## Types of Links:
  1. Absolute URLs : Linking to Other Sites. ex:   <a href="www.google.com">google</a>
  2. Relative URL : Linking to Other Pages on the Same Site . ex :<a href="index.html">Home</a></li>

# Positioning Elements :
Block-level boxes start on a new line and act as the main building blocks 
of any layout, while inline boxes flow between surrounding text. You can 
control how much space each box takes up by setting the width of the 
boxes (and sometimes the height, too). To separate boxes, you can use 
borders, margins, padding, and background colors. 
1. Normal Flow : position:static
In normal flow, each block-level 
element sits on top of the next 
one. Since this is the default 
way in which browsers treat 
HTML elements, you do not 
need a CSS property to indicate 
that elements should appear 
in normal flow
2.  Relative positioning : position relative
Relative positioning moves an 
element in relation to where it 
would have been in normal flow.
For example, you can move it 10 
pixels lower than it would have 
been in normal flow or 20% to 
the right.
You can indicate that an element 
should be relatively positioned 
using the position property 
with a value of relative.
You then use the offset 
properties (top or bottom and 
left or right) to indicate how 
far to move the element from 
where it would have been in 
normal flow.
To move the box up or down, 
you can use either the top or 
bottom properties.
To move the box horizontally, 
you can use either the left or 
right properties.
The values of the box offset 
properties are usually given in 
pixels, percentages or ems.

  
