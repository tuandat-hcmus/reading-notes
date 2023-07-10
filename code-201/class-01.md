# Class 01 notes

This topic is about some basic concept of web, such as how the web works, basic HTML, CSS, JS, etc. It is important to get the basic knowledge before going further in front-end development.

## Getting started

1. *Compose a short poem describing how HTTP sends data between computers.*
    The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client. This message, and all other data sent between th client and the server, is sent across your internet connection using TCP/IP.

2. *Describe how HTML, CSS, and JS files are “parsed” in the browser.*
    - The browser parses the HTML file first, and that leads to the browser recognizing any `<link>` element references to external CSS stylesheets and any `<script>` element references to scripts.
    - As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.
    - The browser generates an in-memory **DOM** tree from the parsed HTML, generates an in-memory **CSSOM** structure from the parsed CSS, and compiles and executes the parsed JavaScript.
    - As the browser builds the **DOM** tree and applies the styles from the **CSSOM** tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

3. *How can you find images to add to a Website?*
    To choose an image, go to <a href="https://www.google.com/imghp?gws_rd=ssl">Google Images</a> and search for something suitable.
    - When you find the image you want, click on the image to get an enlarged view of it.
    - Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address from your browser's address bar for later use.
Note that most images on the web, including in Google Images, are copyrighted. To reduce your likelihood of violating copyright, you can use Google's license filter. Click on the Tools button, then on the resulting Usage rights option that appears below. You should choose the option Creative Commons licenses.

4. *How do you create a `String` vs a `Number` in JavaScript?*
    To signify that a value is a string, enclose it in single or double quote marks.
    Numbers don't have quotes around them.

5. *What is a `Variable` and why are they important in JavaScript?*
    Variable are containers that store values. Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in n image gallery. 

## Introduction to HTML

1. *What is an HTML attribute?*
    Attributes contain extra information about the element that won't appear in the content. 

2. *Describe the Anatomy of an HTML element.*
    The anatomy of element:
    
    - **The opening tag:** This consist of the name of the element, wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. 
    - **The content:** This is the content of the element.
    - **The closing tag:** This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.
 
 3. What is the Difference between `<article>` and `<section>` element tags?

    - `<article>` encloses a block of related content that makes sense on its own whithout the rest of the page
    - `<section>` is is similar to `<article>`, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. It's considered best practice to begin each section with a heading; also note that you can break `<article>`s up into different `<section>`s, or `<section>`s up into different `<article>`s, depending on the context.

4. *What Elements does a “typical” website include?*

    A typical website includes:
    - header
    - navigation bar
    - main content
    - sidebar
    - footer

5. *How How does metadata influence Search Engine Optimization?*

    Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines.

6. *How is the `<meta>` HTML tag used when specifying metadata?*

    `<meta>` element is a way of adding metadata to a document of HMTL. Many `<meta>` elements include `name` and `content` attributes:
    
    - `name` specifies the type of meta element it is; what type of information it contains.
    - `content` specifies the actual meta content.

## Miscellaneous

### How to start design a Website

1. *What is the first step to designing a Website?*

    The first step is project ideation, and it is a first step to reach goal.

2. *What is the most important question to answer when designing a Website?*

    The most important question is "What exactly do I want to accomplish?"

### Semantics
1. *Why should you use an `<h1>` element over a `<span>` element to display a top level heading?*

    In HTML, `h1` element is a semantic element, which gives the text it wraps around the role of "a top level heading on your page" whilw `span` has no semantic value, so it will not get any extra benefits.

2. *What are the benefits of using semantic tags in our HTML?*

    - Search engines will consider its contents as important keywords to influence the page's search rankings 
    - Screen readers can use it as a signpost to help visually impaired users navigate a page
    - Finding blocks of meaningful code is significantly easier than searching through endless `div`s with or without semantic or namespaced classes
    - Suggests to the developer the type of data that will be populated
    - Semantic naming mirrors proper custom element/component naming

### What is JavaScript?

1. *Describe 2 things that require JavaScript in the Browser?*

    - The `Geolocation API` retrieves geographical information. This is how Google Maps is able to find your location and plot it on a map
    - The `Canvas` and `WebGL API`s allow you to create animated 2D and 3D graphics. People are doing some amazing things using these web technologies

2. *How can you add JavaScript to an HTML document?*

    There are 2 ways of adding JavaScript to an HTML document: 
    
    - Internal: add JavaScript inside `<script>` element
    - External: Create a file with `.js` extension and link it with `src` attribute of `<script>` tag.

## Things I want to know more about