# 📚 Code Study Notes
## HTML:
- HTML = <ins>"Hypertext Markup Language"</ins>
- HTML was invented by Sir Tim Berners-Lee in 1991 

 
 **What is the background behind "markup" ?**  
The origins of markup is traced back to a time before computers to the traditional marking up of paper manuscripts.  
This was done to indicate how a text should be formatted for print - specifying fonts, sizes, styles (like italic or bold),  
spacing and structure.

**Syntax and Semantics:**
- <ins>Syntax:</ins> the rules for forming valid statements in a language, its about the structure and grammar.
- <ins>Semantic:</ins>  the meaning or interpretation of a valid statement. It's about what the statement does or conveys.
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
The DOM represents the document as a <ins>logical tree</ins> of nodes.
- each part of the HTML Document (elements, attributes, text, comments) is represented as a node in this tree.

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

There are global attributes that can be linked to any tag possible.  
- `<id>`: Specifies a unique ID for an HTML element  
- `<class>`: To group elements together so you can apply the same style or behaviour to them  
- `<title>`: Provide extra information that shows up as a tooltip when you hover over the element  
- `<hidden>`: Temporarily hide a element from the view
- `<lang>`: Specify the language of the content within that element

There are also <ins>element specific attributes</ins> which only can be applied to specific tags.  
Element specific tags provide <ins>functionalities</ins> that are **uniqe** to the elements purpose.   
Here are some examples:  
- For `<a>`:
  - `href`: Provides the URL of the page link goes to
  - `target`: Defines where to open the linked document
  - `download`: Prompts the user to download the linked URL
  - Example: `<a href="https://www.example.com">Visit Example</a>`
- For `<link>`:  
  - `type`: Specifies the media type of the linked resource  
  - `rel`:  Relationship between current and linked document  
  - Example: `<link rel="stylesheet" href="print.css" type="text/css" media="print">`
- For `<img>`:  
  - `src`: Path (URL) to the image file  
  - `width`: Width of the image in pixels  
  - `height`: Height of the image in pixels  
  - Example: `<img src="sun.jpg" alt="A beautiful Sun">`
- For `video`:
  - `src`: Path (URL) to the vide file  
  - `autoplay`: Video plays automatically  
  - `loop`: Repeats the video   
  - Example: `<video src="video.mp4" controls></video>`  

There are many more Element specific Tags.

## CSS:
- CSS = <ins>presentation and styling</ins> of a document  
- What is CSS used for ?  
  - Styling Text  
  - Controlling Layout  
  - Adding Colors and Background  
  - Creating Visual Effects  

**How styles connect to tags ?**  

CSS connects to HTML tags using <ins>Selectors</ins>. Selectors are patterns that tell the browsers which HTML elements    
the CSS rules should be applied to. There are different ways styles can be connected to tags:  

1. External Stylesheets (Most Common):
   - How it Works: You create a `.css` file that contains all your CSS rules. You then link this stylesheet  
     to your HTML document using the `<link>` tag in the `<head>` section of your HTML file.
     
2. Internal Style:
   - This method involves placing CSS directly within the HTML Document
   - You include CSS rules inside a `<style` tag, which is typically placed in the `<head>` section
  
3. Inline Styles:
   - Applying CSS directly to a single HTML element using the `style` attribute  

 <ins>Example Image: </ins>  

 <img src=" 
     alt="Graphical representation of DOM Tree" 
     width="70%" 
     style="max-width: 500px; height: auto; border-radius: 8px;">

 
    
   

  
 
  


  
