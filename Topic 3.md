# Basic Page Formatting in HTML  

## Introduction  
HTML provides various formatting elements to style text and structure content on a webpage. This guide covers essential formatting techniques, their usage, and examples.

---

##  Bold or Italicized Text  

### **Bold Text (`<b>` and `<strong>`)**  
- `<b>` makes text bold but does not convey importance.  
- `<strong>` makes text bold and conveys importance for accessibility.  

```html
<p>This is <b>bold</b> text.</p>
<p>This is <strong>important</strong> text.</p>
```

### *Italicized Text (`<i>` and `<em>`)*
- `<i>` italicizes text for styling purposes.  
- `<em>` italicizes and emphasizes text (useful for screen readers).  

```html
<p>This is <i>italicized</i> text.</p>
<p>This is <em>emphasized</em> text.</p>
```

---

## Strikethrough (Strike Out Text)  

### **Strike Out (`<s>` and `<del>`)**
- `<s>` visually strikes out text (for stylistic purposes).  
- `<del>` represents deleted text (useful for document revision).  

```html
<p>This is <s>struck through</s> text.</p>
<p>This is <del>deleted</del> text.</p>
```

---

##  Superscript and Subscript Text  

### **Superscript (`<sup>`)**
- Used to display text **above** the normal line (e.g., exponents, ordinal numbers).  

### **Subscript (`<sub>`)**
- Used to display text **below** the normal line (e.g., chemical formulas).  

```html
<p>E = mc<sup>2</sup></p>
<p>H<sub>2</sub>O is the chemical formula for water.</p>
```

---

## Blockquotes  

### **Blockquote (`<blockquote>`)**
- Used for quoting text from another source.  
- Can be styled with `align="center"` to center the quote.  

```html
<blockquote align="center">
    "The only way to do great work is to love what you do." - Steve Jobs
</blockquote>
```

---

## Adding Comments  

### **HTML Comments (`<!-- -->`)**  
- Comments are ignored by the browser but help document the code.  

```html
<!-- This is a comment -->
<p>This is a paragraph.</p>
```

---

##  Changing Font Size  

### **Font Size (`font-size`)**
- The `style` attribute with `font-size` controls text size.  

```html
<p style="font-size: 20px;">This text is 20px in size.</p>
<p style="font-size: 14px;">This text is 14px in size.</p>
```

---

## Changing Text Color  

### **Text Color (`color`)**  
- The `color` attribute changes text color.  

```html
<p style="color: red;">This text is red.</p>
<p style="color: blue;">This text is blue.</p>
```

---

##  Changing Background Color  

### **Background Color (`background-color`)**
- The `bgcolor` attribute (deprecated) or `style="background-color"` changes the background.  

```html
<body style="background-color: lightgray;">
    <p>This page has a light gray background.</p>
</body>
```

---

## Emphasizing Text  

### **Emphasis (`<em>`)**
- Used to stress important words in a sentence.  

```html
<p>This is an <em>important</em> message.</p>
```

---

##  Centering Text  

### **Centering (`text-align`)**
- The `<center>` tag (deprecated) can center text, but `text-align` is preferred.  

```html
<p style="text-align: center;">This text is centered.</p>
```

---

## Underlining Text  

### **Underline (`<u>`)**
- Used to underline text for emphasis.  

```html
<p>This is an <u>underlined</u> word.</p>
```

---
# HTML Text Formatting Assignment

## Objective
The goal of this assignment is to help students apply various text formatting techniques in HTML to improve their understanding of structuring and styling content on a webpage.

## Instructions
Create a webpage that demonstrates the following formatting techniques using HTML. Ensure that your webpage is well-structured, easy to navigate, and styled appropriately.

## Tasks

### 1. Introduction Section
- Create a header with the title "HTML Text Formatting" using an appropriate heading tag.
- Write a short introductory paragraph about text formatting in HTML.

### 2. Bold and Italic Text
- In a paragraph, use both `<b>` and `<strong>` to emphasize text. For example, use `<b>` for the word “HTML” and `<strong>` for the word “important”.
- In another paragraph, use both `<i>` and `<em>` to style text, and highlight their differences.

### 3. Strikethrough Text
- Use the `<s>` tag to demonstrate a strike-through effect on an outdated text.
- Use the `<del>` tag to represent deleted text and explain its purpose in revision.

### 4. Superscript and Subscript
- Create a sentence that uses the `<sup>` tag for an exponent (e.g., “E = mc²”).
- Create another sentence using the `<sub>` tag to show a chemical formula (e.g., “H₂O”).

### 5. Blockquote
- Insert a blockquote from a famous person or a quote of your choice. Center the blockquote and add a citation to the source.

### 6. Comments
- Add a comment at the top of your HTML code explaining what the page is about. Also, add a comment near each section of the page to explain the formatting used.

### 7. Font Size and Color
- Change the font size and color of the text using the `style` attribute. Use different sizes (e.g., 16px, 20px, 24px) and colors (e.g., red, blue, green) to create variation in the page.

### 8. Background Color
- Apply a background color to the entire webpage and use a contrasting text color to ensure readability.

### 9. Text Emphasis
- Highlight an important word or phrase using the `<em>` tag, demonstrating how it emphasizes text.

### 10. Text Centering
- Center a heading or paragraph on the page using `text-align: center;` in the style attribute.

### 11. Underline Text
- Underline a word in a sentence to emphasize it using the `<u>` tag.

Deliverables
- A single HTML file with all the sections formatted as requested.
- Ensure that all formatting is applied correctly, and the page is visually appealing and well-structured.


---

Good luck, and have fun experimenting with HTML formatting! 🚀

