# HTML Cheat Sheet

This cheat sheet will provide a short overview of HTML elements,  attributes, and syntax. Quick guide for web development offering easy access to commonly used tags and their respective functions.

### Main Root
The **\<html> element** represents the root (top-level element) of an HTML document also called the document element. All other elements must be descendants of this element. <br><br>
`<html>...</html>`<br>
### Boilerplate HTML Layout
```
<!DOCTYPE html>
<html lang="en">

  <head>
    <!-- Description of the document -->
    <meta charset="UTF-8">
    <title>
    <title>ArcticFoxDev</title>
  </head>

  <body>
    <!-- your content goes here -->
    <p>Welcome to my world</p>
  </body>

</html>
```
### Headings 
HTML heading tags **(\<h1> to \<h6>)** are used to define headings and subheadings on your webpage. <br>
The **\<h1> tag** is typically reserved for the page's main title, while the others denote subheadings in descending order of importance.<br><br>
|**Heading Tags**|**Description**|**Syntax**|
|---|---|---|
|***\<div>***|Block element that defines a division in HTML document|\<div>...<br>\</div>|
|***\<span>***|Inline element used to mark up a part of text or document|\<span>...<br>\</span>|
|***\<p>***|Used ot represent a paragraph|\<p>...<br>\</p>|
|***\<pre>***|Represents pre-formatted text to present exactly as written in the HTML file|\<pre>...<br>\</pre>|
|***\<code>***|Used to represent source codes|\<code>...<br>\</code>|
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ArcticFoxDev</title>
    <meta name="keywords" content="meta tags, metadata">
    <meta name="description" content="geeksforgeeks is a computer science portal.">
    <style type="text/css">
      body{
        background-color: blue;
      }
      h1{
        color: black;
        font-family: arial;
      }
    </style>
  </head>

  <body>
    <p>
      GeeksforGeeks is a
      <!-- Span Tag Begins -->
      <span style="color:red;font-weight:bolder;">
        computer science</span> portal for
      <span style="background-color:lightgreen;">
        geeks</span>
      <!-- Span Tag Ends -->
      <!-- Pre Tag Begins -->
      <pre>
        This
        is  a pre tag.
      </pre>
    </p>
    <!-- HTML pre tag ends here -->
    <!-- code Tag Starts Heres -->
    <code>
    </code>
  </body>
</html>
```
