# Images :
You can control the size of an 
image using the width and 
height properties in CSS, just 
like you can for any other box. 
Specifying image sizes helps 
pages to load more smoothly 
because the HTML and CSS 
code will often load before the 
images, and telling the browser 
how much space to leave for an 
image allows it to render the rest 
of the page without waiting for 
the image to download.
You might think that your site 
is likely to have images of all 
different sizes, but a lot of sites 
use the same sized image across 
many of their pages. 
For example, an e-commerce site 
tends to show product photos 
at the same size. Or, if your site 
is designed on a grid, then you 
might have a selection of image 
sizes that are commonly used on 
all pages, such as:

* Small portrait: 220 x 360
* Small landscape: 330 x 210
* Feature photo: 620 x 400

Whenever you use consistently 
sized images across a site, 
you can use CSS to control 
the dimensions of the 
images, instead of putting the 
dimensions in the HTML
## Aligning inages : 

Rather than using the <img>
element's align attribute, web 
page authors are increasingly 
using the float property to align 
images. There are two ways that 
this is commonly achieved:

1. **The float property** is added 
to the class that was created to 
represent the size of the image 
(such as the small class in our 
example).
2. **New classes are created** with 
names such as align-left or 
align-right to align the images 
to the left or right of the page. 
These class names are used in 
addition to classes that indicate 
the size of the image.
In this example you can see the 
align-left and align-right
classes used to align the image.
It is also common to add a 
margin to the image to ensure 
that the text does not touch their 
edges.
## Centering images :

By default, images are inline 
elements. This means that they 
flow within the surrounding text. 
In order to center an image, it 
should be turned into a blocklevel element using the display
property with a value of block. 
Once it has been made into a 
block-level element, there are 
two common ways in which you 
can horizontally center an image:

1. On the containing element, 
you can use the text-align
property with a value of center.
2. On the image itself, you can 
use the use the margin property 
and set the values of the left and 
right margins to auto.

You can specify class names 
that allow any element to be 
centered, in the same way that 
you can for the dimensions or 
alignment of images.
The techniques for specifying 
image size and alignment of 
images can also be used with 
the HTML5 <figure> element, 
