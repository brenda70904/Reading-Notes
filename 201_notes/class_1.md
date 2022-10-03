# Class 1 reading note

## Getting started 
### how does HTTP sends data between computers

Client use browser send an HTTP request to servers, the request and all other data send between client and the server is sent accorss internet connection using TCP/IP.
After server approve the reques, it will start sending the webliste's files to the borwser called data packets.  
![Clients and servers image](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works/simple-client-server.png)

### how does HTML, CSS, and JS files are “parsed” in the browser.
first th browser parses the HTML file, and then browser will start to check if there's any `<link>`-element references to external CSS stylesheets and any `<script>`-element references to scripts.While browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.Then, browser generates an in-memory DOM tree from the parsed HTML, and parsed CSS, and compiles and executes the parsed JavaScript.As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

### How can you find images to add to a Website?
1. find the image you want to use
2. save the image
3. insert the image src

### creating String and number
- create String with double quote or single quote
- create number don't need any quote

### What is VARIABLE? why it's important in JS?
Variables are like a container that store values. Variables can represent numeric values, characters, character strings, or memory addresses. Variables play an important role in computer programming because they enable programmers to write flexible programs.

## Introduction to HTML
### What is an HTML attribute?
HTML : HyperText Markup Language. HTML is a markup language that tess web boweser how to structure the web pages.

### Describe the Anatomy of an HTML element.
the anatomy of HTML element is the opening tag and closing tag that programmer write the content in btweeen the tag. 
![elelment](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-small.png)

### Difference between `<article>` and `<section>` element tags
The section tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document.The article tag specifies independent, self-contained content.

### What Elements does a “typical” website include?
- Header
- Navigation bar
- main content
- sidebar
- footer

### How does metadata influence Search Engine Optimization?
This helps search engines better understand the topic of your webpages and content. It also helps them display more relevant results to searchers

### How is the `<meta>` HTML tag used when specifying metadata?
<meta> tag specifies the document's character encoding.


## Miscellaneous
### What is the first step to designing a Website?
decide what do you want to accomplish with it. 

### What is the most important question to answer when designing a Website?
What is the priority. What is the most important thing needs to be done first. 

### Why should you use an <h1> element over a <span> element to display a top level heading?
Because span tag does not have semantic value. 
  
### What are the benefits of using semantic tags in our HTML?
- it influences the page's search ranking
- give suggestion to developer about what type of datat will be populated 
- easier to find block of code instead of search code from endless <div> tag

### Describe 2 things that require JavaScript in the Browser?
- store useful data
- add interaction on webpage for client

### How can you add JavaScript to an HTML document?
use <script> tag to link HTML and JavaScript

## Things I want to know more about
  I would like to learn more about how JS work and how does the browser handle the code.
