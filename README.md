# web-dev `subrata mondal`
> my web dev journey, with notes and projects
## introduction
### what is html
* html is not a programming language
* html stands for **hypertext markup language**
* html is used for creating webpages and documents
* html is not for logic, javascript is

### html tags
* html tags indicate the begining and ending of an html element using angle brackets `<html element name>` 
* html tags usually comes in pairs `<opening tag>` `</closing tag`>
* some tags can close themselves
    * `<input>`, `<img>`, `<br>`, `<hr>`

### important html tags
* `<html>` `</html>` : the **root** of an html document
* `<head>` `</head>` : is for **metadata** 
  * used mainly for **SEO**
  * used for connecting files like **css**, **javascript**
  * `<title>` `</title>` : used for displaying **name** and **logo** in the browser tab

### html heading tags
* there are in total **6** level heading tags
  * `<h1> </h1>` : defines the top level heading
  * `<h2> </h2>` : defines the second level heading
  * `<h3> </h3>` : defines the third level heading
  * `<h4> </h4>` : defines the fourth level heading
  * `<h5> </h5>` : defines the fifth level heading
  * `<h6> </h6>` : defines the sixth level heading

### html paragraph tag
* `<p>` `</p>` : defines a paragraph

## html level elements
`inline vs block`

* **block elements** start on a new line and takes on all the width available
  * example: heading tag, paragraph tag, etc
  * `<div> </div>` : defines a division or a section
  * `<h1> </h1>` : defines the top level heading
  * `<p> </p>` : defines a paragraph

* **inline elements** do not start on a new line and only takes necessary width
  * `<button> </button>` : defines a clickable button
  * `<span> </span>` : defines a generic container for inline elements
  * `<a> </a>` : defines a hyperlink
  * `<b> </b>` : defines a bold text
  * `<i> </i>` : defines an italix text

### anchor tag
```html
<a href="https://google.com" target="_blank">frontend</a>
# https:// part is absolutely necessary for the hyperlink to work
```
* the **target** attribute decides where to open the link
  * `_blank` : opens link in a new tab



