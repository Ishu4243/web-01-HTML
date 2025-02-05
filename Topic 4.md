# HTML Formatting and Listing

## Formatting Text in HTML
HTML provides several ways to format text, including specifying the **font name, type, and size**.

### Font Name, Type, and Size
Although the `<font>` tag was used in older versions of HTML, it is now obsolete. Instead, we use **CSS** to control fonts. Below are modern ways to apply font formatting.

#### Example: Changing Font Name, Type, and Size Using CSS
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .custom-font {
            font-family: Arial, sans-serif; /* Font Name */
            font-size: 20px; /* Font Size */
            font-weight: bold; /* Font Type (bold, italic, normal) */
        }
    </style>
</head>
<body>
    <p class="custom-font">This is a formatted text with Arial font, bold type, and size 20px.</p>
</body>
</html>
```

### Other Text Formatting Tags
| Tag | Description | Example |
|------|-------------|----------|
| `<b>` | Bold text | `<b>Bold Text</b>` |
| `<i>` | Italic text | `<i>Italic Text</i>` |
| `<u>` | Underlined text | `<u>Underlined Text</u>` |
| `<small>` | Small text | `<small>Small Text</small>` |
| `<mark>` | Highlighted text | `<mark>Highlighted Text</mark>` |
| `<del>` | Strikethrough text | `<del>Deleted Text</del>` |
| `<sup>` | Superscript | `x<sup>2</sup>` (x²) |
| `<sub>` | Subscript | `H<sub>2</sub>O` (H₂O) |
| `<strong>` | Important text (bold) | `<strong>Important!</strong>` |
| `<em>` | Emphasized text (italic) | `<em>Emphasized</em>` |

#### Example: Using Text Formatting Tags
```html
<p>This is <b>bold</b>, <i>italic</i>, and <u>underlined</u> text.</p>
<p>This is <mark>highlighted</mark> text.</p>
<p>E=mc<sup>2</sup> and H<sub>2</sub>O are examples of superscript and subscript.</p>
<p><del>Old Price: $100</del> New Price: $80</p>
```

---

## HTML Lists
HTML supports three types of lists: **Ordered List (`<ol>`), Unordered List (`<ul>`), and Definition List (`<dl>`)**.

### Ordered List (`<ol>`)
An **ordered list** is a numbered list where each item is numbered sequentially.

#### Example: Creating an Ordered List
```html
<!DOCTYPE html>
<html>
<body>
    <h3>Steps to Bake a Cake</h3>
    <ol>
        <li>Preheat the oven.</li>
        <li>Mix the ingredients.</li>
        <li>Pour the batter into a pan.</li>
        <li>Bake for 30 minutes.</li>
        <li>Let it cool and serve.</li>
    </ol>
</body>
</html>
```

### Unordered List (`<ul>`)
An **unordered list** is a bullet-point list without numbering.

#### Example: Creating an Unordered List
```html
<!DOCTYPE html>
<html>
<body>
    <h3>Grocery List</h3>
    <ul>
        <li>Milk</li>
        <li>Bread</li>
        <li>Eggs</li>
        <li>Butter</li>
    </ul>
</body>
</html>
```

### Definition List (`<dl>`) 
A **definition list** consists of terms and their descriptions.

#### Example: Creating a Definition List
```html
<!DOCTYPE html>
<html>
<body>
    <h3>Web Development Terms</h3>
    <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language, used to create web pages.</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets, used for styling web pages.</dd>
        <dt>JavaScript</dt>
        <dd>A scripting language for making web pages interactive.</dd>
    </dl>
</body>
</html>
```

---

## Conclusion
In this guide, we covered:
✔ Formatting text using font name, type, and size with CSS.  
✔ Various text formatting tags like `<b>`, `<i>`, `<u>`, and `<mark>`.  
✔ Creating ordered lists (`<ol>`), unordered lists (`<ul>`), and definition lists (`<dl>`).  

By using these techniques, you can create well-structured and visually appealing web pages. 🚀

