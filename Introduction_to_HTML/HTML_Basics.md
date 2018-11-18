### The General Rule

``` html
<tag name> Some content </tag name>
```

### Anatomy of an HTML Document

``` html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image">
  </body>
</html>
```
### Images

``` html
<img src="images/firefox-icon.png" alt="My test image">
```
### Headings

``` html
<h1>My main title</h1>
<h2>My top level heading</h2>
<h3>My subheading</h3>
<h4>My sub-subheading</h4>
```

### Paragraphs

``` html
<p>This is a single paragraph</p>
```

### Lists

- Unordered lists are for lists where the order of the items doesn't matter, like a shopping list. These are wrapped in a `<ul>` element.
- Ordered lists are for lists where the order of the items does matter, like a recipe. These are wrapped in an `<ol>` element.
Each item inside the lists is put inside an <li> (list item) element.

``` html
<p>At Mozilla, we’re a global community of</p>
    
<ul> 
  <li>technologists</li>
  <li>thinkers</li>
  <li>builders</li>
</ul>

<p>working together ... </p>
```

### Links

``` html
<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>
```
