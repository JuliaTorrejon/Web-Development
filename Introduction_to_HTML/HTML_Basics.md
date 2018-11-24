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
### Span

You could make any element look like a top level heading. Consider the following:

``` html
<span style="font-size: 32px; margin: 21px 0;">Is this a top level heading?</span>
```

This is a <span> element. It has no semantics. You use it to wrap content when you want to apply CSS to it (or do something to it with JavaScript) without giving it any extra meaning (You'll find out more about these later on in the course.) We've applied some CSS to it to make it look like a top level heading, but since it has no semantic value, it will not get any of the extra benefits described above. It is a good idea to use the relevant HTML element for the job.

### Div

The HTML Content Division element `<div>` is the generic container for flow content. It has no effect on the content or layout until styled using CSS.

``` html
<div>
  <p>Any kind of content here. Such as
  &lt;p&gt;, &lt;table&gt;. You name it!</p>
</div>
```

### Links

``` html
<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>
```
### Comment 

``` html
<!-- metadata -->
```
