# 📚 Code Study Notes
## HTML:
- HTML = <ins>"Hypertext Markup Language"</ins>
- HTML was invented by Sir Tim Berners-Lee in 1991 

 
 **What is the background behind "markup" ?**  
The origins of markup is traced back to a time before computers to the traditional marking up of paper manuscripts.  
This was done to indicate how a text should be formatted for print - specifying fonts, sizes, styles (like italic or bold),  
spacing and structure

**Syntax and Semantics:**
- <ins>Syntax:</ins> the rules for forming valid statements in a language, its about the structure and grammar.
- <ins>Semantic:</ins>  the meaning or interpretation of a valid statement. It's about what the statement does or conveys
> [!NOTE]
> A program can be syntactically correct but semantically incorrect (trying to divide by zero, which is grammatically fine but meaningless in a mathematical context).

**What is the structure of a HTML File ?**  
[Simple Keychain File]()  
[Proper Tag Structure]()  

**What is the DOM ?**  
The <ins>Document Object Model (DOM)</ins> is a crucial concept in Web Programming, serving as the bridge between web document (html)  
and scripting languages (JavaScript).

The DOM defines the logical structure of web documents and the way a document is accessed.  
When a Web-Browser loads a HTML page, it doesn't just display text; it builds a live, in-memory  
representation of that page called the DOM.  

**Structure of DOM:**
The DOM represents the document as a <ins>logical tree</ins> of nodes
- each part of the HTML Document (elements, attributes, text, comments) is represented as a node in this tree

**Dom Graphic:**  

<img src="https://www.javascript-kurs.de/bilder/dom-beispiel-document-object-model.jpg" 
     alt="Graphical representation of DOM Tree" 
     width="70%" 
     style="max-width: 500px; height: auto; border-radius: 8px;">  


  **Which HTML Tags exist ?**

 HTML Tag Category:

1. Document Structure Tags:
   
    `<!DOCTYPE html>`: Document type declaration (not a tag).

    `<html>`: The root of an HTML page.

    `<head>`: Contains meta-information about the HTML document.

    `<body>`: Contains the visible page content.
     
2. Metadata Tags in `<head>`:
   
    `<meta>`: Defines metadata about an HTML document.

    `<title>`: Specifies the title of the document.

    `<link>`: Links to external resources (e.g., stylesheets).

    `<style>`: Defines internal CSS.

    `<script>`: Used to embed client-side scripts (JavaScript).
    
3. Inline Text Semantic Tags in `<body>`:
   
    `<a>`: Defines a hyperlink.

    `<strong>`: Defines important text (bold by default).

    `<em>`: Defines emphasized text (italic by default).

    `<b>`: Defines bold text (without semantic importance).

    `<i>`: Defines italic text (without semantic importance).
   
4. Text Content Tags in `<body>`:
   
   `<h1> to <h6>`: Defines HTML headings.

   `<p>`: Defines a paragraph.
 
   `<pre>`: Defines preformatted text.

   `<hr>`: Defines a thematic break (horizontal rule).

   `<br>`: Inserts a single line break.
   
There are many more categories of tags in HTML like media, links and more.

**What are "standard attributes" ?**

These are global attributes that can be linked to any tag possible.  
- `<id>`: Specifies a unique ID for an HTML element.
