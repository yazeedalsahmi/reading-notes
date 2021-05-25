# Lists :
 HTML provides us with three different types:
1. **Ordered lists** are lists where each item in the list is 
numbered. For example, the list might be a set of steps for 
a recipe that must be performed in order, or a legal contract 
where each point needs to be identified by a section 
number.
The ordered list is created with the <ol> element.
Each item in the list is placed between an opening `<li>` tag 
and a closing` </li>` tag. (The listands for list item.)
2. **Unordered lists** are lists that begin with a bullet point 
(rather than characters that indicate order).
the unordered list is created with the <ul> element.Each item in the list is placed 
between an opening `<li>` tag and a closing `</li>` tag. (The li
stands for list item.
3. **Definition lists** are made up of a set of terms along with the 
definitions for each of those terms.
The definition list is created with the `<dl>` element and usually 
consists of a series of terms and their definitions.
Inside the `<dl>` element you will 
usually see pairs of `<dt>` and 
`<dd>` elements.`<dt>` This is used to contain the term being defined (the definition 
term).`<dd>` This is used to contain the 
definiti.
  
  # Boxes:
  1. *Box Dimensions :* By default a box is sized just big enough to hold its contents. To 
set your own dimensions for a box you can use the height and width properties.
 **example :**
  ````
  div.box {
height: 300px;
width: 300px; } //use pixels

p {
height: 75%;
width: 75%;} //use percentage
  ````
2. *Border :* Every box has a border (even if 
it is not visible or is specified to 
be 0 pixels wide). The border 
separates the edge of one box 
from another.
3. *Margin :* Margins sit outside the edge 
of the border. You can set the 
width of a margin to create a 
gap between the borders of two 
adjacent boxes.
4. *Padding :* Padding is the space between 
the border of a box and any 
content contained within it. 
Adding padding can increase the 
readability of its contents.
  
  
