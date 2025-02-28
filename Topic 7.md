# HTML Tables: A Comprehensive Guide

This document provides a detailed overview of HTML tables, covering essential elements and attributes.

## Introduction to Tables

HTML tables are used to present data in a structured, tabular format. They are invaluable for displaying information in rows and columns, making it easy to read and understand.

## Table Elements

The primary HTML elements used to create tables are:

* `<table>`: Defines the table itself.
* `<tr>`: Defines a table row.
* `<th>`: Defines a table header cell.
* `<td>`: Defines a table data cell.
* `<caption>`: Defines a table caption.

## Creating a Table

A basic HTML table is created using the `<table>`, `<tr>`, and `<td>` elements.

```html
<table>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
</table>
Adding a Border
To add a border to the table, use CSS. While the HTML border attribute exists, it is now deprecated. CSS provides much more control.
<style>
  table, th, td {
    border: 1px solid black;
    border-collapse: collapse; /* Optional, collapses borders */
  }
</style>
<table>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
</table>
Adding a Caption
The <caption> element is used to add a title or description to the table. It should be the first child of the <table> element.
  <table>
  <caption>Monthly Savings</caption>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>

Cells (<td>)
The <td> element defines a standard data cell within a table. It contains the content of the table.
  <tr>
  <td>Data 1</td>
  <td>Data 2</td>
</tr>
Rows (<tr>)
The <tr> element defines a row in the table. Each <tr> element contains one or more <td> or <th> elements.
  <tr>
  <td>Cell 1</td>
  <td>Cell 2</td>
</tr>
Headers (<th>)
The <th> element defines a header cell in the table. Header cells are typically used for column or row headings and are displayed in bold by default.
  <table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>
Cell Spans
Cell spans allow you to merge multiple cells into a single cell, either horizontally (using colspan) or vertically (using rowspan).
<table>
   
</table>
Vertical Span (rowspan)
<table>
  <tr>
    <th rowspan="2">Combined Header</th>
    <td>Data 1</td>
  </tr>
  <tr>
    <td>Data 2</td>
  </tr>
</table>