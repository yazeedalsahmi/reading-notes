# HTML language
![HTML](https://xwww.mutah.edu.jo/yumna/what-is-html.jpg)
**HTML (Hypertext Markup Language)** is  a *programming markup language* used to structure web pages and web applications and their content, for example by modifying texts by specifying the headlines and modifying the line and making it bigger or Italic, adding images, tables, dropdowns, and hyperlinks are the basic building blocks of the web, Other technologies besides **HTML** are generally used to describe a web page's  appearance/presentation **(CSS)** orfunctionality/behavior **(JavaScript)**.

## Some codes in HTML :
### Headings
Heading elements allow you to specify that certain parts of your content are headings — or subheadings.  HTML contains 6 heading levels, <h1>–<h6>, you can add a heading like this:

`<h1>My main title</h1>`
`<h2>My top level heading</h2>`

### Lists
 Marking up lists always consists of at least 2 elements. The most common list types are ordered and unordered lists:

1. Unordered lists: are for lists where the order of the items doesn't matter, such as a shopping list. These are wrapped in a `<ul>` element.
2. Ordered lists : are for lists where the order of the items does matter, such as a recipe. These are wrapped in an `<ol>` element.
Each item inside the lists is put inside an `<li>` (list item) element.

For example, f we wanted to turn the part of the following paragraph fragment into a list :

````
<p>some programming language are: c++ ,pyhton,HTML  </p>
`````
We could modify the markup to this: 

```````
<p>some programming language are:</p>
<ul>
  <li>c++</li>
  <li>pyhton</li>
  <li>HTML</li>
</ul>
```````
### Links:
To add a link, we need to use a simple element — `<a> `— "a" being the short form for "anchor".Like this for example :
```
<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>
```