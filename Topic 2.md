# Introduction to HTML

## What is HTML?
HTML (HyperText Markup Language) is the standard language for creating web pages. It structures web content using elements represented by tags.

## Why HTML?
- Forms the backbone of web pages
- Supported by all browsers
- Works with CSS & JavaScript for styling and interactivity

## Creating HTML Documents
An HTML document is a text file with an `.html` extension. It contains structured content using HTML tags.

## Setting Up a Document
A basic HTML document starts with:
```html
<!DOCTYPE html>
<html>
<head>
    <title>My First HTML Page</title>
</head>
<body>
    <h1>Welcome to HTML</h1>
</body>
</html>
```

## Basic Structure Tags
- `<html>`: Root element
- `<head>`: Metadata and links to stylesheets
- `<title>`: Defines page title
- `<body>`: Contains visible content

## Viewing a Document in a Browser
1. Save file with `.html` extension
2. Open with a web browser (Chrome, Firefox, Edge)

## Introduction to HTML Versions
- **HTML4** (1997) – Older version, used with XHTML
- **HTML5** (2014) – Latest version, supports multimedia, better semantics

## What is a Doctype & Why?
The `<!DOCTYPE html>` declaration tells the browser to use HTML5 mode for correct rendering.

## Introduction to HTML Elements
### What is an Element?
An element consists of an opening tag, content, and closing tag:
```html
<p>This is a paragraph.</p>
```
### Why Use Elements?
- Structure content properly
- Improve accessibility

## HTML Element Structure
```html
<tagname>Content</tagname>
```
Example:
```html
<h1>Heading Example</h1>
```

## Nesting Elements
Elements can be nested inside each other:
```html
<div>
    <p>This is a paragraph inside a div.</p>
</div>
```

## Meta Tags & Attributes
- `<meta charset="UTF-8">`: Defines character encoding
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Responsive design

## HTML Attributes
### What Are They & Why?
Attributes provide additional information about an element.

### How to Use Attributes?
They go inside the opening tag:
```html
<p align="center">Centered Text</p>
```

### Examples of Attributes:
- `bgcolor`: Sets background color
- `text`: Defines text color
- `align`: Aligns text

## Basic HTML Structure Example
```html
<!DOCTYPE html>
<html>
<head>
    <title>Example Page</title>
</head>
<body bgcolor="lightblue" text="black">
    <h1 align="center">Welcome</h1>
    <p>This is a simple paragraph.</p>
</body>
</html>
```

## Preformatted Text
Use `<pre>` to display text with spacing preserved:
```html
<pre>
This   text
    keeps   its format.
</pre>
```

## Adding Headings
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
```

## Centering Text
```html
<center>This text is centered.</center>
```

## Aligning Text
```html
<p align="right">This text is right-aligned.</p>
```

## Inserting Special Characters
```html
&copy; &lt; &gt; &amp;
```

## Comments in HTML
```html
<!-- This is a comment -->
```

## Advanced Body Elements
### `<div>`
A block-level container for grouping elements:
```html
<div>
    <h2>Title</h2>
    <p>Some text.</p>
</div>
```
### `<blockquote>`
Defines a blockquote:
```html
<blockquote>"This is a blockquote."</blockquote>
```
### `<address>`
Defines contact information:
```html
<address>
    Written by John Doe.<br>
    Visit us at: example.com
</address>
```

---
 
 # HTML     Assignment

## Objective  
This assignment will help you understand key HTML elements and attributes, including:  
- Elements: `<html>`, `<head>`, `<body>`, `<div>`, `<blockquote>`, `<address>`, `<pre>`  
- Attributes: `bgcolor`, `text`, `align`  

## Instructions  

1. **Create an HTML file** named `index.html`.  
2. **Structure your page using the following elements:**  

   - Start with `<!DOCTYPE html>` to define the document type.  
   - Use `<html>` as the root element.  
   - Inside `<head>`, include a `<title>` with a meaningful title.  
   - Inside `<body>`, apply the `bgcolor`, `text`, and `align` attributes.  
   - Use **two `<div>` elements** to group content and apply `align` attributes.  
   - Add a **blockquote** (`<blockquote>`) with a famous quote, aligned to the center.  
   - Use the **`<address>` element** to display a fictional contact address.  
   - Add **preformatted text** (`<pre>`) to display text exactly as written, including spaces and line breaks.  

## Example Structure  

```html
<!DOCTYPE html>
<html>
<head>
    <title>My HTML Assignment</title>
</head>
<body bgcolor="lightblue" text="darkblue" align="center">
    
    <div align="left">
        <h1>Welcome to My Webpage</h1>
        <p>This is a simple webpage demonstrating HTML elements and attributes.</p>
    </div>

    <div align="right">
        <h2>Blockquote Example</h2>
        <blockquote align="center">
            "The only limit to our realization of tomorrow is our doubts of today." - Franklin D. Roosevelt
        </blockquote>
    </div>

    <h2>Contact Information</h2>
    <address>
        123 Web Street, HTML City, CodeLand 45678<br>
        Email: example@email.com<br>
        Phone: +123-456-7890
    </address>

    <h2>Preformatted Text Example</h2>
    <pre>
        Name:       John Doe
        Age:        25
        Occupation: Web Developer
    </pre>

</body>
</html>
