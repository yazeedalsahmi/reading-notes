# Html
HTML Describes the Structure of Pages
The HTML code  is made up of characters that live inside angled brackets — these are called HTML elements. 
Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag 
has an extra forward slash in it.) Each HTML element tells the browser 
something about the information that sits between its opening and closing tags.
some meanings of html tags:
* `<html></html>`: indicates that anything between it  is HTML code.
* `<body></body>`: tag indicates that anything between it should be shown inside the main browser window
* `<h1> </h1>` : main heading.
* `<p> </p>`: A paragraph of text.
* `<h2> </h2>`: sub-heading.
* `<head></head>` :This contains information about the page (rather than information that is shown within 
the main part of the browser window that is highlighted in blue on the opposite page).
 * `<title></title>` : The contents of the <title> element are either shown in the top of the browser, 
 above where you usually type in the URL of the page you want to visit, or on the tab for that page.
  * `<DOCTYPE html>` : declaration to tell a browser which version of HTML the page is using and 
  also help the browser to render a page correctly.
  * `<!-- -->` : to add comments in html.
  
 
## Attributes :
**Attributes** provide additional information about the contents of an element. They appear 
on the opening tag of the element and are made up of two parts: a name and a value, 
separated by an equals sign.
**The attribute name** indicates what kind of extra information you are supplying about the 
element's content. It should be written in lowercase.
**The value** is the information or setting for the attribute. It should be placed in double 
quotes. Different attributes can have different values.
example : <a herf = "www.google.com">name</a>
* `herf` : attribute name Specifies the location of the linked document
* *The value* is www.google.com.
  ### ID Attribute 
  *Every HTML element* can carry the id attribute. It is used to 
uniquely identify that element from other elements on the page. Its value should start with 
a letter or an underscore (not a number or any other character).It is important that no
 two elements on the same page have the same value for their id attributes (otherwise the value is 
no longer unique).
  ### Class Attribute :
  *Every HTML element* can also carry a class attribute. Sometimes, rather than uniquely 
identifying one element within a document, you will want a way to identify several elements 
as being different from the other elements on the page. For example, you might have 
some paragraphs of text that contain information that is more 
important than others and want to distinguish these elements, or 
you might want to differentiate between links that point to other 
pages on your own site and links that point to external sites. 
To do this you can use the class attribute. Its value 
should describe the class it belongs to. 
