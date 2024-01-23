<h1 align="center">Web Development</h1>
<p align="center">
  <img src="https://img.shields.io/badge/node-20.11.0-blue" alt="python@3.11.0">
  <img src="https://img.shields.io/badge/npm-10.2.4-moccasin" alt="pip@23.3.2">
  <img src="https://img.shields.io/badge/html-5-orange" alt="poetry@1.7.1">
  <img src="https://img.shields.io/badge/css-3-papayawhip" alt="pytest@7.4.4">
</p> 

> my web dev journey, with notes and projects

<h1 align="left">HTML</h1>

## HTML
### what is html
* html is not a programming language
* html stands for **hypertext markup language**
* html is used for creating webpages and documents
* html is not for logic, javascript is

### html tags
* html tags indicate the begining and ending of an html element using angle brackets `<html element name>` 
* html tags usually comes in pairs `<opening tag>` `</closing tag`>
* some tags can close themselves:
  ```html
   <input>, <img>, <br>, <hr>
  ```

### important html tags
* `<html>` `</html>` : the **root** of an html document
* `<head>` `</head>` : is for **metadata** 
  * used mainly for **SEO**
  * used for connecting files like **css**, **javascript**
  * `<title>` `</title>` : used for displaying **name** and **logo** in the browser tab

### html heading tags
* there are in total **6** level of heading tags
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


### html lists
There are two types of lists: `unordered` and `ordered`
`unordered list` : no numbering, uses bullet points to display each list item
```html
    <ul>
        <li>Good</li>
        <li>Better</li>
        <li>Best</li>
    </ul>
```
`ordered list` : uses numbering to display each list item
```html
    <ol>
        <li>Good</li>
        <li>Better</li>
        <li>Best</li>
    </ol>
```

### html navigation tag
```html
<nav> </nav>
```
* navigation tag is used to define a section of navigation links
* navigation tag is typically used to contain menus, lists of links, or other navigation-related content
* navigation tag helps in organizing and structuring navigation elements on a web page

### html main tag
```html
<main> </main>
```
* main tag defines the main content of a document
* main tag encloses the central content area of a webpage
* main tag typically excludes headers, footers, and sidebars

### html footer tag
```html
    <footer> </footer>
```
* footer tag represents the footer of a section or a page
* footer tag usually contains metadata, copyright information, contact details, or links to related documents
* footer tag provides a consistent way to include information that appears at the bottom of a webpage
* footer tag is often used to give users additional context or reference points

### html section tag
```html
<section> </section>
```
* section tag defines a section in a document
* section tag is used to group related content and typically has a heading
* section tag is helpful for structuring content and making it more semantically meaningful

### html image tag
```html
<img src="./assets/dashboard/design.png" alt="">
<img src="https://unsplash.com/cat1353" alt="">
```
* image tag is a **self closing** tag
* image tag is used to display visual content such as photos or graphics, into web pages
* image tag uses the `src`` attribute to specify the image file's source (URL or local file path)
* image tag has optional attributes including `alt` (alternative text) for accessibility and `width/height` for size control

## html form tag
```html
<form action="">
    <label for="">Email</label>
    <input type="email">

    <label for="">Password</label>
    <input type="password">
    <button>submit</button>
</form>
```
* form tag encloses input elements to create a user interactive form like login, submission
* form tag uses attributes like `action` (URL for form submission) and `method`` (HTTP method for sending data)
* form tag contains various input elements (e.g., text fields, checkboxes) and often a submit button
* form tag enables users to input data, which can be processed by the server upon submission
* form tag is key for user interaction, data collection, and user authentication on websites

### html input tag
```html
<input type="text">
```
* input tag is used for accepting user input
* input tag `types` include **text, password, checkbox, radio,** and more
* input tag uses attributes like **type** (input type), **name** (identifier for server-side processing), and placeholder (hint text)

### html label tag
```html
<label for="">Password</label>
<input type="password" name="subrata" placeholder="enter your password">
```
* label tag is used for creating a caption for a form element
* label tag uses the `for` and `id` attributes to link the caption to the form element, or nests the form element inside the label tag
* label tag allows the user to toggle the state of the form element by clicking or tapping on the caption

### html textarea tag
```html
<textarea name="review" id="" cols="30" rows="10"></textarea>
```
* textarea tag is used for creating a multi-line text input
* textarea tag uses the `rows` and `cols` attributes to specify the size of the input, or CSS to style it
* textarea tag uses attributes like `name` (identifier for server-side processing), `placeholder` (hint text), `readonly` (read-only mode), `required` (mandatory input), and `wrap` (text wrapping mode)


## CSS

### Intro to CSS
* CSS stands for Cascading Stylesheets
* CSS is used to style websites.

#### Methods for adding CSS to HTML
There are three methods of adding CSS to HTML
1. **Inline CSS**
Style directly in the HTML. (Inside HTML Tags in HTML file)
2. **Internal CSS**
Using `<style>` tags within an HTML file. (Inside HTML file.)
3. **External CSS (Recommended)**
Linking an external CSS file.

### CSS Common Properties
#### color
Sets the color of the text.

There are three ways to set color.
1. **Words**
Ex: red, green, blue, orange, etc.
2. **RGB**
rgb(0,0,0) represents `black`.

`RGB` stands for Red, Green, Blue.<br>
`RGBA` same as RGB but `A` is `Alpha` stands for `Opacity`.
3. **Hex**
#ff0000 represents `red`.
#### background-color
Sets the background-color of the element.
#### width
Sets the width of the element.
#### height
Sets the height of the element.
#### border
Sets a border around the element.
#### font-size
Sets the size of the element.
#### font-weight
Sets the font weight of the element.
#### font-family
Sets the font family of the weight.
### Specificity
### Box Model
### Complex Properties
### Media Queries
### Sudo Selectors
### Animations
### BEM 
