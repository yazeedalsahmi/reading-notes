# CSS (Cascading Style Sheets) :

**(Cascading Style Sheets)** is a *programming language* responsible for designing websites and making them look great
it can control exactly how HTML elements look in the browser, presenting your markup using whatever design you like.

![css](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1200px-CSS3_logo_and_wordmark.svg.png)
## CSS Used : 
CSS can be used for very basic document *text styling* — for example 
* changing the color and size of headings and links.
* It can be used to create layout — for example turning a single column of text into a layout with a main content area and a sidebar for related information. 
* It can even be used for effects such as animation. Have a look at the links in this paragraph for specific examples.
## How can write CSS ?
There three ways to write CSS :

1. **Inline** :
`<h1>style : property:value:</h1>` 
2. **internal** :
```
 <style>
header
{
  background color : red
}
</style>
```
3. **external**  : by create new file with exctintion CSS and write the code Inside then connect it with the html file .
by write in html file this code `<link rel="stylesheet"herf =:style.css>`

for example  :
```
h1 {
    color: red;
    font-size: 5em;
}

p {
    color: black;
}
```

## Some CSS syntax :
CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."

The following code shows a very simple CSS rule that would achieve the styling described above:
```
h1 {
    color: red;
    font-size: 5em;
}
```
The rule opens with a selector . This selects the HTML element that we are going to style. In this case we are styling level one headings `(<h1>)`.

We then have a set of curly braces `{ }`. Inside those will be one or more declarations, which take the form of property and value pairs. Each pair specifies a property of the element(s) we are selecting, then a value that we'd like to give the property.

Before the colon, we have the property, and after the colon, the value. CSS properties have different allowable values, depending on which property is being specified. In our example, we have the color property, which can take various color values. We also have the font-size property. This property can take various size units as a value.